<template>
	<div>
		<h1>系统主页</h1>
		<h2>欢迎使用OA管理系统</h2>
	</div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export  default class HomeMain extends Vue{
	@Prop()
	private title!: string;
}
	
</script>

<style>
</style>
