<template>
    <div class="site">
      <div class="nav-bar">
        <NuxtLink class="name" to="/">Zachary Richter</NuxtLink>
        <div class="filler"></div>
        <NuxtLink class="about" to="about">about</NuxtLink>
        
      </div>

      <NuxtPage />
    </div>
</template>

<style>
html, body{
  margin: 0px;
}

html{
  font-family: "Helvetica Neue";
}

.nav-bar{
  display: flex;
  margin: .5rem;
  border-bottom: 2px solid black;
  padding-bottom: 5px;
}

.name{
  font-size: 2rem;
  margin: 0px;
  text-decoration: none;
  color: black;
  font-weight: 800;
  text-transform: uppercase;
  letter-spacing: 0.2rem;
  align-content: center;
}

.about{
  font-size: 1rem;
  margin: 0px;
  padding: 1rem;
  background-color: brown;
  color: white;
  text-decoration: none;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 1rem;
}

.filler{
  flex-grow: 1;
}

</style>