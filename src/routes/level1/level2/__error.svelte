<script context="module">
    export function load({ error, status }) {
		return {
			props: {
				title: `[level 2]${status}: ${error.message}`
			}
		};
	}
</script>

<script>
    export let title;
</script>

<h1>{title}</h1>
