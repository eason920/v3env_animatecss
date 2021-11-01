<template>
  <div class="home">
    <div>
      <img 
        class="animate__animated animate__flash"
        src="https://upload.cc/i1/2019/11/20/iBj2Tn.png">
    </div>

    <div>
      <img 
        class="animate__animated animate__bounce" 
        src="https://upload.cc/i1/2019/11/20/iBj2Tn.png">
    </div>

    <div>
      <img 
        class="animate__animated animate__pulse" 
        src="https://upload.cc/i1/2019/11/20/qjDM9B.png">
    </div>


    <div>
      <img 
        class="animate__animated animate__rubberBand" 
        src="https://upload.cc/i1/2019/11/20/m96fkK.png">
    </div>

    <div>
      <img 
        class="animate__animated animate__shakeX" 
        src="https://upload.cc/i1/2019/11/20/qwASWf.png">
    </div>

    <div>
      <img
        class="animate__animated animate__shakeY" 
        src="https://upload.cc/i1/2019/11/20/kiLTqC.png">
    </div>

  </div>
</template>

<style lang="sass">
@import '~animate.css' // 二法澤一(b:1/1)

*
  padding: 0
  margin: 0
  box-sizing: border-box
  
.home div
  height: 100vh
  padding-top: 50px
  overflow: hidden

.home div:nth-child(even)
  background-color: #aaa

img
  display: block
  margin: 0 auto

</style>
