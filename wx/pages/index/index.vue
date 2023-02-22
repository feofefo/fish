<template>
	<view class="container">
		{{count}}
	</view>
</template>

<script setup>
import { ref } from "vue";
	const count = ref(10)
</script>

<style>
	.container {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
</style>
