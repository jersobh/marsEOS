<template>
  <q-page class="flex flex-center">
    <div class="row logo-wrap" style="margin:0 auto;width:100%;padding:0;">
    <img
      src="~assets/logo.png"
      style="max-width:60%;"
      id="float"
    >
  </div>
  <div class="row">
    <q-btn to="/story" unelevated rounded text-color="grey-10" color="grey-12" label="Begin Adventure" />
  </div>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>
<style>
.logo-wrap {
  margin: 0 auto;
width: 100%;
padding: 0px;
display: flex;
flex-wrap: wrap;
align-items: center;
align-items: center;
justify-content: center;
display: flex;
flex-wrap: wrap;
}
#float {
    position: relative;
    -webkit-animation: floatBubble 2s   normal ease-out;
    animation: floatBubble 2s   normal ease-out;
}
@-webkit-keyframes floatBubble {
    0% {
        top:200px;
    }
    100% {
        top: 0px;
    }
}
@keyframes floatBubble {
    0% {
        top:200px;
    }
    100% {
        top: 0px;
    }
}
</style>
