<script setup>

</script>

<template>
  <div class="form-container">
    <div class="styling">
      <nav class="navbar bg-dark">
        <div class="container-fluid">
          <h1 class="title">Styling</h1>
        </div>
      </nav>
      <div class="action-group p-3">
        <h3>Logo:</h3>
        <div class="btn-group" role="group" aria-label="Basic outlined example">
          <button type="button" class="btn btn-outline-primary">Farbig</button>
          <button type="button" class="btn btn-outline-primary">Transparent</button>
        </div>
        <label for="customRange2" class="form-label">Transperenz:</label>
        <input type="range" class="form-range" min="0" max="100" id="customRange2">
      </div>
    </div>
    <div class="forms">
      <nav class="navbar bg-dark">
        <div class="container-fluid">
          <h1 class="title">Informationen</h1>
        </div>
      </nav>
      <div class="input-group p-3">
        <h3>Vor- und Nachname:</h3>
        <div class="input-group flex-nowrap">
          <span class="input-group-text" id="addon-wrapping">@</span>
          <input type="text" class="form-control" placeholder="Unterschrift (Vor- und Nachname" aria-label="Username" aria-describedby="addon-wrapping">
        </div>
        <h3>Rang:</h3>
        <div class="input-group flex-nowrap">
          <span class="input-group-text" id="addon-wrapping">@</span>
          <input type="text" class="form-control" placeholder="Unterschrift (Vor- und Nachname" aria-label="Username" aria-describedby="addon-wrapping">
        </div>
        <h3>Dienstnummer:</h3>
        <div class="input-group mb-3">
          <span class="input-group-text">#</span>
          <input type="text" class="form-control" aria-label="">
        </div>

      </div>
    </div>
  </div>
</template>

<style scoped>

.action-group {
  display: flex;
  flex-direction: column;
  gap: 1vh;
}

.title {
  color: white;
}

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
  border: solid 1px white;
}

.styling {
  border: solid 1px white;
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
