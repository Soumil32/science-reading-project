<script lang="ts">
    import '$lib/app.css'
</script>

<nav class="">
    <!--Add links to invidual pages as a sidebar-->
    <a href="/">Home</a>
</nav>

<div class="flex flex-col items-center">
    <main class="w-full md:w-1/2 lg:w-1/2 mt-5 flex flex-col gap-5">
        <slot></slot>
    </main>
</div>

<style lang="postcss">
    
</style>