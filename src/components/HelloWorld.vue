<template>
  <div class="hello">
    <h1>Welcome to My Vlog Today</h1>
    <h2>-- from 甜辣酱 2023/04/18</h2>
  </div>
</template>

<script>
export default {
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
  background-color: pink;
  border-radius: 40px;
  margin: 40px;
}

h1 {
  margin: 80px;
  padding: 180px 60px;
  color: rgb(124, 165, 241);
  font-size: 84px;
}

h1:hover {
  cursor: pointer;
  animation: animate 0.8s linear infinite;
}

h2{
  cursor: pointer;
  padding-bottom: 100px;
  animation: rotate 2s linear infinite;
}

@keyframes animate {
0%,
25% {
    text-shadow: 6px 6px 6px #f34f72aa;
}

50% {
  text-shadow: 6px -6px 6px #f34f72aa;
}

75% {
  text-shadow: -6px 6px 6px #f34f72aa;
}

100% {
  text-shadow: -6px -6px 6px #f34f72aa;
}
}

@keyframes rotate {
10%,
90% {
    transform: translate3d(-1.2px, 0, 0);
}

20%,
80% {
    transform: translate3d(2px, 0, 0);
}

30%,
70% {
    transform: translate3d(-4.8px, 0, 0);
}

40%,
60% {
    transform: translate3d(4.8px, 0, 0);
}

50% {
    transform: translate3d(-4.8px, 0, 0);
}


}


</style>
