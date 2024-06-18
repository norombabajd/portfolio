<script>
    import "../app.css";
    import Header from '../components/Header.svelte';
  </script>
  
  <div class="app">
	<Header />

	<main class="justify-center">
		<slot />
	</main>

	<footer class="text-sm">
		<p>(c) John Daniel Norombaba, 2024</p>
	</footer>
</div>

<style lang="postcss">
    
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
		background-color: #131216;
	}

	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		width: 100%;
		box-sizing: border-box;
        
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 10px;
		margin: 1rem;
		color: #EBFFF8
	}

	/* footer a {
		font-weight: bold;
	} */

	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>