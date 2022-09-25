<template>
    <div class="layout">
        <slot />
    </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style>
body {
    font-family: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.layout {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>
