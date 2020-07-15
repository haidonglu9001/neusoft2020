<template>
	<div>
		<h1>系统主页</h1>
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
