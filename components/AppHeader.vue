<template>
  <header class="header">
    <div class="logo">
      <div class="logoIcon">
        <img src="~/assets/explorer.png" alt="">
      </div>
      <div class="logoText">
        EXPLORER
      </div>
    </div>
    <div>
      <button>Manage DeFi</button>
    </div>
  </header>
</template>

<script>
export default {
  name: 'AppHeader'
}
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1.2rem 0 1.2rem 0;
}

.logo {
  display: flex;
  justify-content: center;
  align-items: center;
}

.logoIcon {
  margin-right: 0.8rem;
}

.logoText {
  font-weight: 700;
}

button {
  background: rgb(54, 54, 190);
  color: white;
  font-size: 0.9rem;
  border-radius: 0.4rem;
  padding: 0.2rem 1.4rem;
}
</style>
