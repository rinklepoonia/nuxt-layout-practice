<template>
    <div class="bg-[#F3F6FC] p-6">
        <div class="flex gap-6">
            <div class="max-w-[246px] w-full">
                <CommonSideBar />
            </div>

            <div class="flex flex-col gap-3">
                <CommonNavigation />
                <slot />
            </div>
        </div>
    </div>
</template>
<script></script>