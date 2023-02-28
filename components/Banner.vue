<template>
    <div class="banner">
        <div class="container">
            <h1><strong>Bienvenue sur mon portfolio</strong>!</h1>
            <p>Découvrez mes projets en cours.</p>
            <a class="btn btn-flat" href="#">Je découvre les projets</a>
        </div>
    </div>
</template>
<style scoped>
.banner {
  background-size: cover;
  background-position: center;
  padding: 150px 0;
  background-image: linear-gradient(rgba(0,0,0,0.4),rgba(0,0,0,0.4)),url('./assets/img/banner.jpg')
}

.banner h1 {
  margin: 0;
  color: white;
  text-shadow: 1px 1px 3px rgba(0,0,0,0.2);
  font-size: 32px;
  font-weight: bold;
}

.banner p {
  font-size: 20px;
  color: white;
  opacity: .7;
  text-shadow: 1px 1px 3px rgba(0,0,0,0.2);
}
</style>