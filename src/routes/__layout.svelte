<script lang="ts">
    // Components
    import { Canvas } from "$components";
    
    // Imports
    import '../app.css';
</script>

<div class="flex w-screen h-screen bg-white">
    <div class="w-full h-full max-w-4xl">
        <slot />
    </div>
    <Canvas />
</div>