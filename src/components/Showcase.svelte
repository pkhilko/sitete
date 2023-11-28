<script lang="ts">
	import Button from './Button.svelte';
	export let imgPosition = 'right';
	const computedClassName = imgPosition === 'left' ? 'grid-container img-left' : 'grid-container';
	export let title: string;
	export let content: string;
</script>

<div class={computedClassName}>
	<div class="one">
		<h1>{title}</h1>
		<p>{content}</p>
		<Button />
	</div>
	<div class="two">
		<img
			class="img"
			src="https://www.imgacademy.com/sites/default/files/school-about-us-slider-22.jpg"
			alt="blev"
		/>
	</div>
</div>

<style>
	.grid-container {
		width: 100%;
		display: grid;
		grid-template-columns: 1fr 1fr 1fr;
		grid-template-rows: 1fr 1fr 1fr;
		grid-template-areas:
			'a b b'
			'a b b'
			'. b b';
	}
	.img-left {
		grid-template-areas:
			'b b a'
			'b b a'
			'b b .';
	}
	.one {
		grid-area: a;
		border: 2px solid #c91818;
		padding: 50px;
	}
	.two {
		grid-area: b;
		border: 2px solid #c91818;
		padding: 24px;
	}
	.img {
		display: block;
		margin-left: auto;
		margin-right: auto;
		width: 100%;
		object-fit: fill;
	}
</style>
