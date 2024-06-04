<template>
    <h1 class="noto-var">Noto Sans Var</h1>
    <h1 class="noto-vari">Noto Sans Variable</h1>
    <h1 class="inter-var">Inter Var</h1>
    <h1 class="inter-vari">Inter Variable</h1>
    <h1 class="intervari">InterVariable</h1>
    <h1 class="roboto-flex">Roboto Flex</h1>
    <h1 class="roboto-flex-var">Roboto Flex Var</h1>
    <h1 class="roboto-flex-vari">Roboto Flex Variable</h1>
    <h1 class="nuxt-font-stack">nuxt.com Font Stack</h1>
    <h1 class="nuxt-font-stack2">nuxt.com Font Stack (Inter (non-variable) entry removed)</h1>
</template>

<style scoped>
.noto-var {
    font-family: 'Noto Sans var';
}

.noto-vari {
    font-family: 'Noto Sans Variable';
}

.roboto-flex {
    font-family: 'Roboto Flex';
}

.roboto-flex-var {
    font-family: 'Roboto Flex var';
}

.roboto-flex-vari {
    font-family: 'Roboto Flex Variable';
}

.inter-var {
    font-family: 'Inter var experimental', 'Inter var';
}

.inter-vari {
    font-family: 'Inter Variable';
}

/* From Inter's website */
.inter-vari {
    font-family: 'InterVariable';
}

/* ripped straight from nuxt.com */
/* This works here because Inter (non-variable) is being bundled for the other page.
 * On nuxt.com, it falls straight through to system-ui
 */
.nuxt-font-stack {
    font-family: Inter var experimental, Inter var, Inter, ui-sans-serif, system-ui, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol, Noto Color Emoji;
}

/* Regular Inter Entry was removed */
.nuxt-font-stack2 {
    font-family: Inter var experimental, Inter var, ui-sans-serif, system-ui, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol, Noto Color Emoji;
}
</style>
