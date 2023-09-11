<template>
  <div class="body">
    <MessageUser />
    <MenChat />
  </div>
</template>

<script>
import MessageUser from "./components/MessageUser.vue";
import MenChat from "./components/MenChat.vue"

export default {
  components: {
    MessageUser,
    MenChat,
  },
  
};
</script>
<style>
*{ margin: 0;
    padding: 0;
    font-family: 'Roboto', sans-serif;
}
.body{
    max-width: 100%;
    display: flex;
    flex-direction: row;
    min-height: 100vh;
}



@media (max-width: 550px) {
    .msjUserText{
        font-size: 0.7rem;
    }
}

@media (max-width: 760px) {
    .chatUser {
        display: none;
    }

    .logSupport{
        display: inline-block;
    }

    .msjUserView{
        width:100%;
    }

    .msjsUser{
        width: 75%;
    }

    .msjUserTextLogo{
        max-width: 5vw;
        max-height: 3vw;
    }

    .msjUserImg{
        max-width: 13vw;
        max-height: 13vw;
    }

    

}

@media (min-width: 761px) and (max-width: 1020px){
    .msjUserTextLogo{
        max-width: 2.3vw;
        max-height: 2.3vw;
    }
}

</style>
