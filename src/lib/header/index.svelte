<script>
	import { page } from '$app/stores';
</script>

<header class="px-20">
	<div class="logo flex items-center">
		<img
			src="https://www.leigod.com/img/logo.png"
			height={42}
			alt="雷神加速器"
		/>
	</div>
</header>

<style lang="scss" scoped>
	header {
		background-color: var(--bg);
		height: 64px;
		.logo {
			height: inherit;
			img {
				height: 42px;
			}
		}
	}
</style>
