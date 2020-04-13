<template>
	<div class="home">
		<div><circle-loading></circle-loading></div>
		<div><badge></badge></div>
		<div><bubble-loading></bubble-loading></div>
		<div><calendar></calendar></div>
		<div><floating-button></floating-button></div>
		<div><heart></heart></div>
		<div><land-mark></land-mark></div>
		<div><mail></mail></div>
		<div><play-button></play-button></div>
		<div><progress-bar></progress-bar></div>
		<div><teacup-loading></teacup-loading></div>
		<div><vue></vue></div>
	</div>
</template>

<script>
	import CircleLoading from '../components/CircleLoading.vue'
	import Badge from '../components/Badge.vue'
	import BubbleLoading from '../components/BubbleLoading.vue'
	import Calendar from '../components/Calendar.vue'
	import FloatingButton from '../components/FloatingButton.vue'
	import Heart from '../components/Heart.vue'
	import LandMark from '../components/LandMark.vue'
	import Mail from '../components/Mail.vue'
	import PlayButton from '../components/PlayButton.vue'
	import ProgressBar from '../components/ProgressBar.vue'
	import TeacupLoading from '../components/TeacupLoading.vue'
	import Vue from '../components/Vue.vue'
	
	export default {
		components: {
			CircleLoading,
			Badge,
			BubbleLoading,
			Calendar,
			FloatingButton,
			Heart,
			LandMark,
			Mail,
			PlayButton,
			ProgressBar,
			TeacupLoading,
			Vue
		}
	}
</script>

<style>
	.home {
		height: 100vh;
		display: flex;
		align-items: center;
		justify-content: center;
		flex-wrap: wrap;
		margin: 0 auto;
	}
	.home > div {
	  transform: scale(1.5);
		margin: 20px 50px
	}
</style>
