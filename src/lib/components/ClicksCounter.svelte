<script>
let props = $props()

let count = $state(props.initialCount || 0)
let doubled = $derived(count * 2)

    console.log("hello world")
</script>

<h3>Clicks Counter</h3>

<button onclick={()=> count++}>
    Clicks: {count}
</button>

<span> Doubled: {doubled}</span>

