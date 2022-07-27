<template>
  <section>
     <h1>Outras cousiñas</h1>
  <div class="about">
     
      <div class="caixa">Hola mundo cruel</div>
    <div class="caixa"><ul class="meu">
      <div class="cuentenedor"><img src="../assets/uno.jpg" class="simemson"><li class="li">Fixen unha expo dun artista</li></div> 
      <div class="cuentenedor"><img src="../assets/dos.jpg" class="simemson"><li class="li">Traballo no Cersia :(</li></div>
      <div class="cuentenedor"><img src="../assets/tres.png" class="simemson"><li class="li">Pouco máis</li> </div>
      <div class="cuentenedor"><img src="../assets/catro.jpg" class="simemson"><li class="li">Eu non sei</li> </div>
    </ul></div>
    
    <div class="caixa">
      Adiós mundo cruel
    </div>
  </div>
  </section>

</template>

<style>
.about{
  display: flex;
  flex-direction: row;

}
.caixa{
width: 100%;
  margin: 5px;
  background-color: teal;

}
.meu{
  display: grid;

}
.cuentenedor{

  grid-template-columns: 100px 100px;
  
}
  .li{
    font-size:20px;
    align-content: flex-start;
      list-style: none;
  }
  .simemson{
    width: 250px;
    height: 150px;
  }
  .cuentenedor:hover .simemson {
    border-radius:50%;
    -webkit-border-radius:50%;
    box-shadow: 0px 0px 15px 15px #1b1917;
    -webkit-box-shadow: 0px 0px 15px 15px #1d1a17;
    transform: rotateY(180deg) scale(1.3);
    -webkit-transform: rotateY(180deg) scale(1.3);
/* -webkit-transform:scale(1.3) rotateY(180deg);transform:scale(1.3) rotateY(180deg);-webkit-transform-style: preserve-3d;
transform-style: preserve-3d;*/
} 
.contenedor {overflow:hidden;}




</style>