<template>
  <article class="project-card">
    <p class="label">Desafio inicial</p>
    <h2>Problema observado</h2>
    <p>Como tornar as informações do projeto mais claras para a comunidade?</p>
    <button type="button">Marcar interesse</button>
  </article>
</template>

<style scoped>
.project-card {
  padding: 24px;
  background: #f4f7f5;
  border-left: 8px solid #1f8f3a;
}

.project-card h2 {
  margin: 0;
  color: #123d27;
}

.project-card > p:not(.label) {
  margin: 12px 0 20px;
  line-height: 1.6;
}

.label {
  margin: 0 0 8px;
  color: #316b47;
  font-size: 0.8rem;
  font-weight: 700;
  letter-spacing: 0.04em;
  text-transform: uppercase;
}

button {
  padding: 12px 18px;
  color: #ffffff;
  font-weight: 700;
  background: #005c2e;
  border: 0;
  border-radius: 4px;
}

button:hover {
  background: #004522;
}

button:focus-visible {
  outline: 3px solid #f3c623;
  outline-offset: 3px;
}
</style>

