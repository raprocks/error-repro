<script context="module">
	export function load({ error, status }) {
		return {
			props: {
				title: `[Level 1]${status}: ${error.message}`
			}
		};
	}
</script>

<script>
	export let title;
</script>

<h1>{title}</h1>