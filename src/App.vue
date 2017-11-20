<template>
<div id="app">
    <h2>Circolor!</h2>
    <!-- <div id="circle"></div> -->
    <div id="circle" v-bind:style="{backgroundColor: '#' + note.color}"></div>
</div>  
</template>

<script>
export default {
  name: 'app'
}
</script>
