<template>
    <div class="flex-1 overflow-hidden">
        <div class="relative h-full">
            <div class="flex h-full flex-col items-center justify-center">
                <h1>How can I help you today?</h1>
            </div>
        </div>
        <div class="w-full pt-2 border-t ">
            <h1>goChat</h1>
            <textarea id="prompt-textarea" tabindex="0" data-id="root" rows="1" placeholder="Message ChatGPT…"
                class="m-0 w-full resize-none border-0 bg-transparent py-[10px] pr-10 focus:ring-0 focus-visible:ring-0 dark:bg-transparent md:py-4 md:pr-12 gizmo:md:py-3.5 gizmo:placeholder-black/50 gizmo:dark:placeholder-white/50 pl-3 md:pl-4"
                style="max-height: 200px; height: 52px; overflow-y: hidden;"></textarea>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped></style>