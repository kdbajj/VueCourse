<template>
  <div>
    <header>
      <nav>
        <ul>
          <li class="nav-item">
            <img class="logo" src="./assets/build-a-bot-logo.png"/>
            Build-a-Bot
          </li>
        </ul>
      </nav>
    </header>
    <main>
      <div class="robot-name">
        This is a test
      </div>
      <RobotBuilder />
    </main>
  </div>
</template>
<script>
// import HomePage from './home/HomePage.vue';
import RobotBuilder from './build/RobotBuilder.vue';

export default {
  name: 'App',
  components: {
    RobotBuilder,
  // HomePage,
  },
};
</script>

<style>
body {
  background: linear-gradient(to bottom, #555, #999);
  background-attachment: fixed;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  color: #1d1c1c;

}
</style>

<style scoped>
.robot-name {color: red;}
main{
  margin: 0 auto;
  padding: 30px;
  background-color: white;
  width: 1024px;
  min-height: 300px;
}

header {
  background-color: #999;
  width: 1084px;
  margin: 0 auto;
}
ul {
  padding: 3px;
  display: flex;
}
.nav-item {
  display: inline-block;
  padding: 5px 10px;
  font-size: 22px;
  border-right: 1px solid #bbb;
}
.logo {
  vertical-align: middle;
  height: 30px;
}
</style>
