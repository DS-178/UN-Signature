<script setup>
defineProps({
  Signature: {
    type: String,
    required: true,
  },
  Grade: {
    type: String,
    required: true,
  },
  Id: {
    type: String,
    required: true,
  },
})
</script>

<template>
  <div class="main-container">
    <div class="Signature-cotainer">
      <img class="logo" src="./icons/LSPD.png">
      <div class="text-container">
        <h3 class="Signature-text">{{ Signature }}</h3>
        <div class="divider"></div>
        <h3 class="Signature-sub">
          {{ Id }} - {{ Signature }} - {{ Grade }}
        </h3>
        <div class="footer">Los Santos Police Department</div>
      </div>
    </div>
  </div>
</template>

<style scoped>

.main-container {
  display: flex;
  justify-content: center;
  align-items: center;
  //background-color: red;
  padding: 1vw;
}

.logo {
  opacity: 70%;
  z-index: 99999;
  position: absolute;

  height: 20vh;
  user-select: none;
  filter: grayscale(100%);
  transform: rotate(331deg);
}

.Signature-cotainer {
  display: flex;
  padding: 1vw;
  align-items: center;
  background-color: white;
  border-radius: 7px;
  height: 30vh;
  width: 40vw;
}

.text-container {
  position: relative;
  top: 6vh;
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-items: center;
  align-items: center;
}

.Signature-text {
  color: black;
  font-family: "Segoe Script";
  font-size: 8vh;
  position: relative;
  top: 3vh;
  left: 1.5vw;
}

.divider {
  height: .2vh;
  width: 100%;
  background-color: black;
}

.Signature-sub {
  display: flex;
  gap: 1vw;
  color: black;
  font-family: Serif;
  font-weight: bold;
  font-size: 2vh;
 }

.footer {
  color: black;
  font-family: Serif;
  font-weight: bold;
  font-size: 2vh;

}
</style>
