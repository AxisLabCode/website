<script lang="ts">
	export let content: string;
</script>

<main>
	<div class="container">
		<div class="typed-out">
			{content}
		</div>
	</div>
</main>

<style>
	.container {
		font-weight: normal;
		font-size: 50px;
		display: inline-block;
	}
	.typed-out {
		overflow: hidden;
		border-right: 0.15em solid #76abae;
		white-space: nowrap;
		animation:
			typing 1.5s steps(40, end) forwards,
			blinking 0.8s infinite;
		width: 0;
	}
	@keyframes typing {
		from {
			width: 0;
		}
		to {
			width: 100%;
		}
	}
	@keyframes blinking {
		from {
			border-color: transparent;
		}
		to {
			border-color: #76abae;
		}
	}
</style>
