<script>
	import { title } from '$lib/data/meta';
	export let animated = false;
</script>

<div class="logo" class:animated>
	<img src="/pretty-barn.png" alt="Бабайкина сарайка" style="max-height: 96px; margin: 1rem" />
</div>

<style lang="scss">
	@import '$lib/scss/breakpoints.scss';

	.logo {
		width: auto;
		height: 100%;

		display: flex;
		gap: 16px;
		align-items: center;

		@include for-phone-only {
			gap: 8px;
		}
	}
</style>
