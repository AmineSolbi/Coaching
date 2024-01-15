<template>
  <div
    class="lg:p-0 p-10 bg-[url('../../images/phone.png')] bg-no-repeat bg-[#0B1215] lg:bg-none text-white overflow-y-hidden">
    <div data-aos="fade-up">
      <div class="flex justify-center">
        <img src="./images/logoAdnan.png">

      </div>
      <div class="lg:grid lg:grid-cols-2 lg:gap-2 lg:p-[1%] h-screen" id="APERCU">
        <div class="lg:text-[35px] lg:m-10 font-bold text-[24px]">
          Hi , je suis <span class="text-[#FF5050]">Adnane Khouri</span><br />

          Coach professionnel. Apprenons ensemble de nombreuses disciplines et
          devenons des
          MEILLEURS
          athlètes, comme on
          dit
          <span class="text-[#FF5050]">“un esprit sain dans un corps sain”</span><br />
          <button class="bg-[#FF5050] p-4 text-[16px] rounded-lg font-bold lg:mt-5 mt-[40%]"
            @click="goto('CONSULTER LES ENTRAÎNEMENTS')">CONSULTER
            LES
            ENTRAÎNEMENTS</button>
        </div>
        <div class="lg:flex lg:justify-end hidden">
          <img src="./images/figmaimage.png">
        </div>
      </div>
    </div>
    <div class="p-[4%]" id="CONSULTER LES ENTRAÎNEMENTS" data-aos="fade-left">
      <div class=" font-bold text-[24px] text-justify"> <span class="lg:text-[#FF5050] lg:font-black lg:text-2xl">Explorez
          l'apogée</span> de
        votre
        <span class="text-[#FF5050] font-black lg:text-2xl">forme physique
        </span>avec mes
        entraînements
        <span class="text-[#FF5050] font-black lg:text-2xl">spécialisés</span>. Que vous soyez passionné <span
          class="text-[#FF5050] font-black lg:text-2xl">d'alpinisme</span>,
        de <span class="text-[#FF5050] font-black lg:text-2xl">gym</span>, de <span
          class="text-[#FF5050] font-black lg:text-2xl">football</span>
        ou d'autres disciplines, découvrez le chemin vers une
        <span class="text-[#FF5050] font-black lg:text-2xl">condition physique optimale</span> .
        Entraînez-vous avec un <span class="text-[#FF5050] font-black lg:text-2xl">coach dédié</span> à vous aider à
        atteindre
        de
        nouveaux <span class="text-[#FF5050] font-black lg:text-2xl">sommets</span>, aussi
        bien sur la <span class="text-[#FF5050] font-black lg:text-2xl">montagne</span> que
        sur
        le <span>terrain de jeu.</span>
      </div>
      <button class="bg-[#FF5050] p-4 text-[16px] rounded-lg font-bold lg:mt-5 mt-[5%]" @click="goto('Contact')">
        ME
        CONTACTEZ</button>
      <div data-aos="fade-right">
        <p class="font-bold text-4xl mt-8">GYM</p>
        <div class="lg:grid lg:grid-cols-5 lg:gap-5 mt-8 bg-white rounded-lg p-5">
          <CldVideoPlayer src="https://res.cloudinary.com/dgkjji7rx/video/upload/v1705273533/1705270187201_wnpycy.mp4" />
          <CldVideoPlayer src="https://res.cloudinary.com/dgkjji7rx/video/upload/v1705273533/1705270190634_cbjd0l.mp4" />
          <CldVideoPlayer src="https://res.cloudinary.com/dgkjji7rx/video/upload/v1705273532/1705270137521_qxuqem.mp4" />
          <CldVideoPlayer src="https://res.cloudinary.com/dgkjji7rx/video/upload/v1705273530/1705270163153_zpegf6.mp4" />
          <CldVideoPlayer src="https://res.cloudinary.com/dgkjji7rx/video/upload/v1705273530/1705270171724_r9lkkr.mp4" />
        </div>
      </div>
      <div data-aos="fade-right">
        <p class="font-bold text-4xl mt-8">PRÉPARATION PHYSIQUE</p>
        <div class="lg:grid lg:grid-cols-5 lg:gap-5 mt-8  bg-white p-5 rounded-lg">
          <CldVideoPlayer src="https://res.cloudinary.com/dgkjji7rx/video/upload/v1705273562/morning.mp4" />
          <CldVideoPlayer src="https://res.cloudinary.com/dgkjji7rx/video/upload/v1705273562/morning.mp4" />
          <CldVideoPlayer src="https://res.cloudinary.com/dgkjji7rx/video/upload/v1705273562/morning.mp4" />
          <CldVideoPlayer src="https://res.cloudinary.com/dgkjji7rx/video/upload/v1705273562/morning.mp4" />
          <CldVideoPlayer src="https://res.cloudinary.com/dgkjji7rx/video/upload/v1705273562/morning.mp4" />
        </div>
      </div>

    </div>
    <div class="p-[1%]" data-aos="zoom-in-right">
      <div class="lg:grid lg:grid-cols-2 lg:gap-2 " id="Contact">
        <div class="lg:text-[35px] lg:m-10 font-bold text-[24px]">
          Vous pouvez me contacter
        </div>
      </div>
      <div class="ml-[3%]">
        <p class="text-xl font-bold mt-5 lg:mt-0">Réseaux sociaux :</p>
        <div class="lg:grid lg:grid-cols-3 lg:gap-4 lg:mt-5 -ml-3 mt-5 lg:tm-0">
          <div class="font-bold p-3 grid grid-cols-7">
            <img src="./images/insta.png" />
            <p>adnanekhou_</p>
          </div>
          <div class="font-bold p-3 grid grid-cols-7">
            <img src="./images/gmail.png" />
            <p>Adnanechoachingad@gmail.com</p>
          </div>
          <div class="font-bold p-3 grid grid-cols-2">
            <img src="./images/wsp.png" />
            <p class="lg:-ml-[50%] -ml-[71%]">01 01 93 53 82</p>
          </div>
        </div>


      </div>
    </div>

  </div>
</template>

<script setup>


const goto = (name) => {
  const section = document.getElementById(name);
  if (section) {
    section.scrollIntoView({ behavior: 'smooth' });

  }
};


</script>
