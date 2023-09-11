<template>
  <section class="msjUserView">
    <header class="header">
      <div>
        <h1 class="tittle">Chats</h1>
        <img class="logSupport" v-bind:src="icono" alt="Icono de ayuda">
      </div>
    </header>
    <main>
        <div class="msjsUser">
            <div class="msjUserImg">
          <img class="img" v-bind:src=usuario1 alt="Imagen de usuario 1">
        </div>
        <div class="msjUserText">
         <h2>Lolo Dog</h2>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
         </div>
          <div class="msjUserTextLogo">
           <img class="img" v-bind:src=logo11 alt="logo">
           </div>
         </div>
   
       <div class="msjsUser">
                   <div class="msjUserImg">
                       <img class="img" v-bind:src=usuario2 alt="Imagen de usuario 2">
                   </div>
           
                   <div class="msjUserText">
        <h2>Lau Cat</h2>
          <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
       </div>
   
      <div class="msjUserTextLogo">
          <img class="img" v-bind:src=logo2 alt="logo">
       </div>
      </div>
   
   
   
               <div class="msjsUser">
                   <div class="msjUserImg">
                       <img class="img" v-bind:src=usuario3 alt="Imagen de usuario 3">
                   </div>
                   <div class="msjUserText">
                       <h2>Cherry Dog</h2>
                       <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                   </div>
                   <div class="msjUserTextLogo">
                       <img class="img" v-bind:src=logo3 alt="logo">
                   </div>
               </div>
   
   
   
               <div class="msjsUser">
                   <div class="msjUserImg">
                       <img class="img" v-bind:src=usuario4 alt="Imagen de usuario 4">
                   </div>
                   <div class="msjUserText">
                       <h2>Pepe Cat</h2>
                       <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                   </div>
                   <div class="msjUserTextLogo">
                       <img class="img" v-bind:src=logo4 alt="logo">
                   </div>
               </div>
   
               <div class="msjsUser">
                   <div class="msjUserImg">
                       <img class="img" v-bind:src=usuario7 alt="Imagen de usuario 5">
                   </div>
                   <div class="msjUserText">
                       <h2>Pancho Cat</h2>
                       <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                   </div>
                   <div class="msjUserTextLogo">
                       <img class="img" v-bind:src=logo7 alt="logo">
                   </div>
               </div>
   
               <div class="msjsUser">
                   <div class="msjUserImg">
                       <img class="img" v-bind:src=usuario8 alt="Imagen de usuario 6">
                   </div>
                   <div class="msjUserText">
                       <h2>Gaby Cat</h2>
                       <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                  </div>
                  <div class="msjUserTextLogo">
                      <img class="img" v-bind:src=logo8 alt="logo">
                </div>
            </div>
   
          </main>
  </section>
</template>
<script>
import IconHelp from "./IMG/Help_icons.png"
import usuar from "./IMG/ImgUser1.jpeg"
import usuar1 from "./IMG/ImgUser2.png"
import usuar2 from "./IMG/ImgUser3.png"
import usuar3 from "./IMG/ImgUser4.jpeg"
import usuar4 from "./IMG/IMgUser5.png"
import usuar8 from "./IMG/ImgUser6.jpeg"
import logoo from "./IMG/logo_animatch.png"



export default{
  name: "MessageUser",
  data(){
    return {
      icono: IconHelp,
      usuario1: usuar,
      usuario2: usuar1,
      usuario3: usuar2,
      usuario4: usuar3,
      usuario4: usuar4,
      usuario7: usuar3,
      usuario8: usuar8,
      logo11: logoo,
      logo2: logoo,
      logo3: logoo,
      logo4: logoo,
      logo8: logoo,
      logo7: logoo,
    };
  },
};
</script>

<style>
:root{
    --Blanco: #FFFFFF;
    --SalmonClaro: #FFF9F8;
    --SalmonMedio: #FFDDD9;
    --RojoOscuro: #C82711;
    --Rojo:  #FF5454;
    --Naranja: #F57D26;
    --Verde: #26F52E;
    --Celeste: #26C3F5;
    --Violeta: #9A26F5;
    --Azul: #0075CA;
    --RosaOpaco: #c9a6a663;
    --Gris: #26262664;
    --Perla:  #F6F4EF;
    --Negro: #302929;
    --RosaClaro: #fe7f7d39;
}
.msjUserView{
    width: 35vw;
}

.msjUserView main{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 40px;
}
.msjsUser{
       width: 28vw;
       height: 5.5vw;
       border-radius: 12px;
       background-color: var(--RosaOpaco);
       border-bottom: 1px solid var(--Gris);
       padding: 10px 15px;
       display: flex;
       flex-direction: row;
       justify-content:space-evenly;
       align-items: center;
       flex: 1;
   }
   
   .msjUserImg{
       max-width: 5vw;
       max-height: 5vw;
       border-radius: 50%;
       overflow: hidden;
   }
   .msjUserImg img, .msjUserTextLogo img{
       width: 100%;
       height: 100%;
       object-fit: cover;
   }
   .msjUserText{
       max-width: 500px;
       display: flex;
       flex-direction: column;
       text-align: start;
       color: var(--Negro);
       padding-left: 18px;
       font-size: 0.8rem;;
   }
   
   .msjUserTextLogo{
       max-width: 1.9vw;
       max-height: 3.1vw;
       display: flex;
       align-self: end;
       margin-left: 5px;
       border-radius: 50%;
       overflow: hidden;
       padding-bottom: 20px;
   }






.msjUserView{
    width: 35vw;
    background-color: var(--Perla);
    border-right: 1px solid #FF5454;
}

.header {
    display: flex;
    background: linear-gradient(0deg, #ff6c6c, #facec9);
    height: 65px;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding: 2px 38px;
    border-bottom: 1px solid #ff5c6c;
}

 .header h1{
    color: white;
    font-size: 1.6rem;
    font-weight: bolder;
}

.header img{
    width: 45px;
    filter:opacity(0.7);
}

.logSupport{
    display: none;
}
</style>

