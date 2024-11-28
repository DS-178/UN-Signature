<script setup>

</script>

<template>
  <div class="form-container">
    <div class="styling">
      <h2>Styling</h2>
      <div class="btn-group" role="group" aria-label="Basic outlined example">
        <button type="button" class="btn btn-outline-primary">Farbig</button>
        <button type="button" class="btn btn-outline-primary">Transparent</button>
      </div>
      <label for="customRange2" class="form-label">Transperenz:</label>
      <input type="range" class="form-range" min="0" max="100" id="customRange2">
    </div>
    <div class="forms">
      <h2>Informationen</h2>
      <div class="input-group">
        <div class="input-group flex-nowrap">
          <span class="input-group-text" id="addon-wrapping">@</span>
          <input type="text" class="form-control" placeholder="Unterschrift (Vor- und Nachname" aria-label="Username" aria-describedby="addon-wrapping">
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>

.form-container {
  display: flex;
  flex-direction: row-reverse;
  gap: 1vh;
  //background-color: red;
  justify-content: start;
}

.forms {
  display: flex;
  flex-direction: column;
  //background-color: #323232;
  width: 100%;
}

.styling {
  display: flex;
  flex-direction: column;
  width: 100%;
}

.input-group-text, .form-control, .btn-outline-primary {
  border-color: #ffffff;
  background-color: #323232;
  color: white;
}

.form-control {

}

</style>
