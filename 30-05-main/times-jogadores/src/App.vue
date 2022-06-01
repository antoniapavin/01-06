<template>
<header class="menu-superior">
  <div class="menu-esquerdo">
    <span>Home</span>
    <span>|</span>
    <span>Jogadores</span>
    <span>|</span>
    <span>Times</span>
  </div>
  <div class="menu-direito">
    <span>Sair</span>
  </div>
  </header> 
  <RouterView />
</template>

<style>
@import "@/assets/base.css";
#app {
  max-width: 1280px;
  margin: 0 auto;
  /*padding: 2rem; */
  height: 100vh;
  font-weight: normal;
  background-color: #d4d1e1;
}

header,
footer {
  background-color: #143265;
  color: white;
  height: 15%;
  font-size: 1.3rem;
  display: flex;
  align-items: center;
  padding-left: 2rem;
}
header span {
  padding: 0 20px;
 
}
header.menu-superior {
  /*display: flex;
  align-items: center;*/
  justify-content: space-between;
}   

main {
  height: 70%;
}
</style>
