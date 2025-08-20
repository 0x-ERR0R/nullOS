<template>
  <div class="terminal-container">
    <div class="terminal-top">
      <p>&gt; terminal</p>
      <div class="terminal-top-buttons">
        <p>-</p>
        <p>□</p>
        <p>×</p>
      </div>
    </div>
    <div class="terminal">
      <p>hello world.</p>
    </div>
  </div>
</template>

<style scoped>
.terminal-container {
  background-color: black;

  color: white;
  font-size: 1rem;
  font-family: var(--terminal-font);

  border-color: blue;
  border-style: solid;
  border-width: 2px;
}

.terminal-top {
  display: flex;
  justify-content: space-between;
  background-color: var(--primary);

  padding: var(--pad-s);
}

.terminal-top-buttons {
  display: flex;
  gap: var(--pad-s);
}

.terminal {
  padding: var(--pad-m);
}
</style>
