<script context="module">
    export async function load({ page, fetch, session, context }) {
		return {
			status: 404,
			error: new Error(`Could not load index for level2 because thrown error explicitly in load`)
		};
	}
</script>

wont be able to see this cause explicit 404 in load