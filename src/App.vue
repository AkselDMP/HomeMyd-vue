<template>
  <section class="w-screen bg-[#5865F2]"> 
    <nav id="navbar" class="flex items-center justify-around p-3">
      <div class="flex items-center">
        <img class="w-9" :src="Logo" />
        <h1 class="text-white tracking-[0.190rem] font-bold text-lg m-4">
        makeyourdiscord.fr
        </h1>
        </div>
        <div>
        <ul class="flex text-white font-medium gap-5">
        <li>Maky</li>
        <li>Postuler</li>
        <li>Outils</li>
        </ul>
      </div>
    </nav>
    <!-- HomeElement -->
    <div class="flex items-center text-center text-white justify-center  flex-col	pt-24 ">
    <h1 class="text-4xl	font-bold tracking-[0.6px]">MakeYourDiscord</h1>
    <p class="text-center w-[700px] text-2xl mt-3">Le serveur qui vous aidera à créer votre communauté Discord en vous donnant accès à des outils facile d’utilisation</p>
    <button class="text-black bg-white p-2 mt-8 rounded-[5px] text-lg mb-12">Découvrir nos outils </button>
    </div>
    <!-- WAVE -->
    <div >
      <img class="absolute w-screen " :src="Wave" />
    </div>
    <!-- DISCORD ELEMENT -->
    <div id="globale" class="flex items-center justify-center ">
      <div  class="w-2/3 	bg-[#2c2f33] absolute  mt-[15vh] rounded-2xl justify-between items-center flex" id="AllPart">
        <div id="LeftPart" class="p-4 flex items-center ml-2	">
          <div class="">
            <img class="w-16 rounded-lg" :src="Logo2" />
          </div>
          <div class="p-3" id="discordInformation">
            <h1 class="text-white text-xl font-semibold tracking-[0.3px]">MakeYourDiscord</h1>
            <div id="activité" class="items-center flex">
              <p class="flex items-center text-white font-light	mt-1"><img class="w-4 mr-1" :src="Green" />987 en lignes</p>
              <p class="flex items-center text-white font-light	mt-1 ml-2"><img class="w-4 mr-1" :src="Grey" />1000 membres</p>
            </div>
          </div>
        </div>
        <div id="RightPart">
          <div class="mr-6">
            <button class="text-white bg-[#0FBD43] p-2 rounded">Rejoindre le serveur</button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from "./components/logomyd.png";
import Wave from "./components/wavee.svg";
import Logo2 from "./components/logo2.svg";
import Green from "./components/green.svg";
import Grey from './components/grey.svg';

export default {
  data: function () {
    return {
      Logo: Logo,
      Wave: Wave,
      Logo2: Logo2,
      Green: Green,
      Grey:Grey,
    };
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap");
html,
body {
  font-family: "Poppins", sans-serif;
}
</style>
