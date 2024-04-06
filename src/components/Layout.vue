<template>
    <div class="w-100 h-100">
        <header class="w-100" style="height: 60px;">
            <slot name="header" :msg="12"></slot>
        </header>
        <main class="w-100" style="height: calc(100% - 60px);">
            <slot></slot>
        </main>
    </div>
</template>