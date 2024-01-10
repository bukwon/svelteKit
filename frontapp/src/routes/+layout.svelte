<script>
	import './styles.css';
	import '../app.css'

	const { children } = $props();
</script>

<div>
	{@render children()}
</div>