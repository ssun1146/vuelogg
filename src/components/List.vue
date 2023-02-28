<template>
<div class="box">
	<div v-for="(v, i) in blog" :key="i">
		<h4>{{v.title}}</h4>
		<p>{{v.date}}</p>
	</div>
</div>

</template>

<script>
export default {
	name:'List',
	components:{},
	props:{
		blog:Array,
	},


}
</script>