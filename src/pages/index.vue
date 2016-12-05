<template>
  <div id="secondcomponent">
    <h4>{{test}}</h4>
    <img src="../images/duck.jpg" alt="">
  </div>
</template>

<script>
export default {
  data () {
    return {
      test: 'Hey man, this is your first page!'
    }
  }
}
</script>
<style>
	img{
		width: 20%;
	}
</style>