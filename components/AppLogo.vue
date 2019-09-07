<template>
  <div class='at-container'>
    <h3 class='at-item'>GOMIHIROI
    </h3>
  </div>
</template>

<style>
div.at-container {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}
.at-item {
  color: #3079ed;
  animation-name: angry-animation;
  animation-duration: 2s;
  animation-timing-function: ease;
  animation-delay: 0s;
  animation-iteration-count: infinite;
  animation-direction: normal;
}
@keyframes angry-animation {
  0%{
    opacity: 0;
    -webkit-transform: scale3d(0.3, 0.3, 0.3);
    transform: scale3d(0.3, 0.3, 0.3);
  }
  60%{
    opacity: 1;
    -webkit-transform: scale3d(1,1,1);
    transform: scale3d(1,1,1);
  }
}
</style>