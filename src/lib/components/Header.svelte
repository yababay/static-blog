<script>
	import { title } from '$lib/data/meta';
</script>

<header>
	<section>
		<a href="/" title="На главную"><img src="/pretty-barn.png" alt={title} /></a>
		<a href="https://t.me/babaykina_sarayka"><i class="bi bi-telegram" />Телеграм-канал</a>
	</section>
</header>

<style lang="scss">
	header,
	section {
		display: flex;
		align-items: center;
		justify-content: center;
		background-color: #cdd6c7;
	}

	section {
		width: 100%;
		padding: 1rem;
		justify-content: space-between;
		max-width: 96ch;
		img {
			max-height: 128px;
		}
		a {
			font-size: 16pt;
			text-decoration: none;
			color: #a0b89f;
			i {
				margin-right: 1rem;
			}
		}
		a:hover {
			color: #4f6a4e;
		}
	}
</style>
