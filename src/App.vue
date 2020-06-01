<template>
  <div  class="bubbles" style="background: linear-gradient(rgb(171, 233, 248), rgb(39, 205, 247));" id="app">
    <wellcome></wellcome>
    <a class="titles" style="cursor: pointer; margin-bottom: 20px;" @click="about = !about">About</a>
    <transition name="fade">
      <about v-if="about"></about>
    </transition>
    <br>
    <a class="titles" style="cursor: pointer; margin-bottom: 20px;" @click="tasks = !tasks">Direction/Task</a>
    <transition name="fade">
      <tasks v-if="tasks"></tasks>
    </transition>
    <br>
    <a class="titles" style="cursor: pointer;" @click="production = !production">Production</a>
    <transition name="fade">
      <production v-if="production"></production>
    </transition>
    <br><br>
    <a class="titles" style="cursor: pointer;" @click="skill = !skill">Skill</a>
    <transition name="fade">
      <skill v-if="skill"></skill>
    </transition>
      <div >
          <div class="bubble"></div>
          <div class="bubble"></div>
          <div class="bubble"></div>
          <div class="bubble"></div>
          <div class="bubble"></div>
      </div>
  </div>
</template>

<script>
import wellcome from './components/WellCome.vue';
import about from './components/About.vue';
import skill from './components/Skill.vue';
import production from './components/Production.vue';
import tasks from './components/tasks.vue';

export default {
  data() {
    return {
      about: false,
      production: false,
      skill: false,
      tasks: false
    }
  },
 
  components: {
   wellcome,
   about,
   skill,
   production,
   tasks
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  
  /* margin-top: 200px; */
  padding-bottom: 130px;
}

.titles {
  font-size: 30px;
  font-weight: bold;
  display: inline-block;
  position: relative;
  text-decoration: none;
  color: #ffffff;
  //  -webkit-text-stroke: 1px black;
    text-shadow: gray 3px 3px 3px;
}

.titles::after {
  position: absolute;
  content: '';
  bottom: 0;
  left: 0;
  width: 0;
  height: 1px;
  background: white;
  transition: all 0.3s ease 0s;
}

.titles:hover {
  cursor: pointer;
  
}

.titles:hover::after {
  width: 100%;
  color:  black;
}

.fade-move {
  transition: transform 1s;
}

.fade-enter {
  /* 現れる時の最初の状態 */
  opacity: 0;
}
.fade-enter-active {
  /* 現れる時のトランジションの状態 */
  transition: opacity 1s;
}
.fade-enter-to {
  /* 現れる時の最後の状態 */
  opacity: 1;
}
.fade-leave {
  /* 消える時の最初の状態 */
  opacity: 1;
}
.fade-leave-active {
  /* 消える時のトランジションの状態 */
  transition: opacity 0.5s;
  /* position: absolute;
  width: auto; */
}
.fade-leave-to {
  /* 消える時の最後の状態 */
  opacity: 0;
}

.bubbles {
// position: absolute;
width: 100%;
height: 500%;
max-height: 6000px;
z-index: 0;
// overflow: hidden;
top: 0;
left: 0;
}
 
.bubble {
position: absolute;
bottom: -40;
width: 40px;
height: 40px;
background-color: transparent;
box-shadow: 0px 0px 15px 0px rgba(255, 255, 255, 0.6) inset;
  -webkit-box-shadow: 0px 0px 15px 0px rgba(255, 255, 255, 0.6) inset;
border-radius: 50%;
animation: bubble 10s ease-in infinite;
}

.bubble:after {
    content: "";
    display: block;
    width: 20%;
    height: 20%;
    border-radius: 100%;
    background: rgba(255, 255, 255, 0.8);
    position: absolute;
    right: 15%;
    top: 15%;
    filter: blur(2px);
    -webkit-filter: blur(2px);
    transform: rotateZ(45deg) scaleY(0.8);
    -webkit-transform: rotateZ(45deg) scaleY(0.8);
}
 
.bubble:nth-child(1) {
width: 20px;
height: 20px;
left: 30%;
animation-duration: 6s;
}
 
.bubble:nth-child(2) {
left: 20%;
animation-duration: 3.5s;
}
 
.bubble:nth-child(3) {
width: 30px;
height: 30px;
left: 30%;
animation-duration: 7s;
}
 
.bubble:nth-child(4) {
width: 50px;
height: 50px;
left: 67%;
animation-duration: 6s;
}
 
.bubble:nth-child(5) {
width: 20px;
height: 20px;
left: 70%;
animation-duration: 4.5s;
}
 
@keyframes bubble {
  0% {
    bottom: -100px;
    transform: translateX(0);
  }
  50% {
    transform: translateX(100px);
  }
  100% {
    bottom: 2000px;
  }
}
</style>
