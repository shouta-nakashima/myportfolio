<template>
  <div style="background: linear-gradient(white, #b59ed8);" id="app">
    <wellcome></wellcome>
    <a class="titles" style="cursor: pointer; margin-bottom: 20px;" @click="about = !about">About</a>
    <transition name="fade">
      <about v-if="about"></about>
    </transition>
    <br><br>
    <a class="titles" style="cursor: pointer;" @click="production = !production">Production</a>
    <transition name="fade">
      <production v-if="production"></production>
    </transition>
    <br><br>
    <a class="titles" style="cursor: pointer;" @click="skill = !skill">Skill</a>
    <transition name="fade">
      <skill v-if="skill"></skill>
    </transition>
    
    
  </div>
</template>

<script>
import wellcome from './components/WellCome.vue';
import about from './components/About.vue';
import skill from './components/Skill.vue';
import production from './components/Production.vue';


export default {
  data() {
    return {
      about: false,
      production: false,
      skill: false
    }
  },
 
  components: {
   wellcome,
   about,
   skill,
   production
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
  margin-top: 200px;
  padding-bottom: 130px;
}
.titles {
  font-size: 30px;
  font-weight: bold;
  display: inline-block;
  position: relative;
  text-decoration: none;
  color: black;
}

.titles::after {
  position: absolute;
  content: '';
  bottom: 0;
  left: 0;
  width: 0;
  height: 1px;
  background: black;
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
</style>
