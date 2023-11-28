<script lang="ts">
	export let text = 'Buy';
</script>

<button class="btn">{text}</button>

<style>
	.btn {
		outline: 0;
		display: inline-flex;
		align-items: center;
		justify-content: space-between;
		background: #40b3a2;
		min-width: 200px;
		border: 0;
		border-radius: 4px;
		box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
		box-sizing: border-box;
		padding: 16px 20px;
		color: #fff;
		font-size: 12px;
		font-weight: 600;
		letter-spacing: 1.2px;
		text-transform: uppercase;
		overflow: hidden;
		cursor: pointer;
	}

	.btn:hover {
		opacity: 0.95;
	}
</style>
