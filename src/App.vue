<template>
  <div id="app">
    <keep-alive>
      <router-view/>
    </keep-alive>
  </div>
</template>


<style>
*{ margin : 0; padding : 0;}
ul,li{ list-style: none;}
img{ display: block;}
html,body{ height:100%;}
.clearfix:after{ content:""; display: block; clear:both;}
</style>
