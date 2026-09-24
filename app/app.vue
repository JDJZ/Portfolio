<template>
  <div class="site">
    <div class="nav-bar">
      <NuxtLink class="name" to="/">Zachary Richter</NuxtLink>
      <div class="filler"></div>
      <NuxtLink class="videos" to="videos">Videos</NuxtLink>
      <NuxtLink class="about" to="about">About</NuxtLink>
    </div>
    <div class="page">
      <NuxtPage />
    </div>

    <div class="footer">
      <NuxtLink class="name-footer" to="/">Zachary Richter</NuxtLink>
      <div class="filler-footer"></div>
        <a
          target="_blank"
          rel="noopener noreferrer"
          href="http://instagram.com/zack.a.r"
        >
          <Icon name="uil:instagram" class="footer-instagram" />
        </a>
        <a
          target="_blank"
          rel="noopener noreferrer"
          href="https://www.linkedin.com/in/zachary-richter/"
        >
          <Icon name="uil:linkedin" class="footer-linkedin" />
        </a>


    </div>
  </div>
</template>

<style>
html,
body {
  margin: 0px;
}

html {
  font-family: "Helvetica Neue";
}

.page {
  flex-grow: 1;
  margin: 0.5rem;
}

.site {
  min-height: 100vh;
  min-width: 100vw;
  flex-direction: column;
  display: flex;
}

.nav-bar {
  display: flex;
  margin: 0.5rem;
  border-bottom: 2px solid black;
  padding-bottom: 5px;
}

.footer {
  min-height: 50px;
  display: flex;
  margin-top: 1rem;
  text-align: center;
  align-items: center;
  /* justify-content: center; */
  background-color: rgb(229, 231, 235);
}

.filler-footer{
  flex-grow: 1;
}


.footer-instagram {
  color: black;
  font-size: 2rem;
  margin-left: 0.5rem;
  margin-right: 0.5rem;
}

.footer-linkedin {
  color: black;
  font-size: 2rem;
  margin-left: 0.5rem;
  margin-right: 0.5rem;
}

.name-footer {
  font-size: 1rem;
  margin-left: 0.5rem;
  text-decoration: none;
  color: black;
  font-weight: 800;
  text-transform: uppercase;
  letter-spacing: 0.2rem;
}

.name {
  font-size: 2rem;
  margin: 0px;
  text-decoration: none;
  color: black;
  font-weight: 800;
  text-transform: uppercase;
  letter-spacing: 0.2rem;
  align-content: center;
}

.about {
  background: #a52a2a;
  border: 1px solid #a52a2a;
  border-radius: 6px;
  box-shadow: rgba(0, 0, 0, 0.1) 1px 2px 4px;
  box-sizing: border-box;
  color: #ffffff;
  cursor: pointer;
  display: inline-block;
  font-family: nunito, roboto, proxima-nova, "proxima nova", sans-serif;
  font-size: 16px;
  font-weight: 800;
  line-height: 16px;
  min-height: 40px;
  outline: 0;
  padding: 12px 14px;
  text-align: center;
  text-rendering: geometricprecision;
  text-transform: none;
  text-decoration: none;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  vertical-align: middle;
}

.about:hover,
.about:active {
  background-color: initial;
  background-position: 0 0;
  color: #a52a2a;
}

.videos {
  background: #a52a2a;
  border: 1px solid #a52a2a;
  border-radius: 6px;
  box-shadow: rgba(0, 0, 0, 0.1) 1px 2px 4px;
  box-sizing: border-box;
  color: #ffffff;
  cursor: pointer;
  display: inline-block;
  font-family: nunito, roboto, proxima-nova, "proxima nova", sans-serif;
  font-size: 16px;
  font-weight: 800;
  line-height: 16px;
  min-height: 40px;
  margin-right: 1rem;
  outline: 0;
  padding: 12px 14px;
  text-align: center;
  text-rendering: geometricprecision;
  text-transform: none;
  text-decoration: none;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  vertical-align: middle;
}

.videos:hover,
.videos:active {
  background-color: initial;
  background-position: 0 0;
  color: #a52a2a;
}

.filler {
  flex-grow: 1;
}
</style>
