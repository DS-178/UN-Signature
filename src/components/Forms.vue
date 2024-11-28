<script setup>

</script>

<template>
  <div class="form-container">
    <h2>Logo:</h2>
    <div class="btn-group" role="group" aria-label="Basic outlined example">
      <button type="button" class="btn btn-outline-primary">Farbig</button>
      <button type="button" class="btn btn-outline-primary">Transparent</button>
    </div>
    <div class="input-group">
      <div class="input-group flex-nowrap">
        <span class="input-group-text" id="addon-wrapping">@</span>
        <input type="text" class="form-control" placeholder="Unterschrift (Vor- und Nachname" aria-label="Username" aria-describedby="addon-wrapping">
      </div>
    </div>
  </div>
</template>

<style scoped>

.form-container {
  display: flex;
  flex-direction: column;
  gap: 1vh;
}

.input-group-text, .form-control {
  border-color: black;
}

</style>
