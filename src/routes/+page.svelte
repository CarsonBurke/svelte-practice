<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<button on:click={increment}>You have {i} apples and {i2} oranges</button>

<script>
    let i = 0
    function increment() {

        i += 1
    }
    $: i2 = i * 2
</script>