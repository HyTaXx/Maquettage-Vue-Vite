<script setup>
import Button from './components/Page/Button.vue';
import NavLink from './components/Page/NavLink.vue';
import Card from './components/Card/Card.vue';
import Card2 from './components/Card/Card2.vue';
import Card3 from './components/Card/Card3.vue';
</script>

<template>
    <header class="bg-[url('/src/assets/header.png')] w-full h-[464px] bg-cover max-[375px]:bg-[url('/src/assets/responsiveback.png')] pt-14 p-[16px] md:pt-0 md:p-0">
        <nav class="flex content-center p-[50px] ml-[104px] items-center max-[375px]:hidden">
            <div class="bg-cover bg-[url('/src/assets/logo.png')] w-[150px] h-[19px] mr-[81px]"></div>
            <div class="flex gap-6">
                <NavLink class="" textea="Offres"/>
                <NavLink class="font-bold" textea="Formations"/>
                <NavLink class="" textea="Ressources"/>
                <NavLink class="" textea="A propos"/>
            </div>
            <div class="flex gap-6 ml-[272px]">
                <Button class="text-white bg-white bg-opacity-20" textebutton="06 74 49 03 21"/>
                <Button class="text-violet-500 font-bold" textebutton="Je prends contact"/>
            </div>
        </nav>
        <section class="navbar md:hidden">
            <img class="m-auto" src="/src/assets/responsivenav.png" alt="">
        </section>
        <div class="flex flex-col mt-[40px]">
            <h1 class="m-auto text-white font-bold md:text-[48px] text-[26px] text-center ">Découvrez nos formations sur étagère !</h1>
            <p class="m-auto md:w-3/5 text-center text-white mt-5">Notre catalogue de formations soft skills est le meilleur allié de vos managers et collaborateurs. Management, vente, ressources humaines, efficacité professionnelle... Composez votre parcours de formation et mixez les modalités pédagogiques pour développer leurs compétences.</p>
        </div>
        
        <div class="flex md:flex-row absolute top-[409px] md:left-[159px] md:right-[159px] bg-white drop-shadow-md md:w-[1122px] md:h-[105px] rounded-[30px] content-center flex-col left-[16px] w-[343px] h-[190px] gap-[16px]">
            <div class="bg-[#F3EDFB] md:w-4/5 content-center m-auto p-4 rounded-full md:mr-0 md:ml-6 w-[299px] mb-0 md:mb-auto">
                <h2 class="md:m-auto md:w-full md:gap-16-px md:rounded-full hidden md:block">Quelle formation recherchez-vous ?</h2>
                <h2 class="m-auto w-full gap-16-px rounded-full md:hidden">Quelle formation recherc...</h2>
                <div class="m-auto"></div>
                <img src="/src/assets/search.png" alt="search" class="absolute md:left-[760px] md:top-[30px] top-[35px] right-[40px]">
            </div>
            <div class="bg-[#F3EDFB] md:w-1/5 rounded-full m-auto p-4 md:ml-10 md:mr-10 w-[299px] mt-0 md:mt-auto">
                <h2 class="md:text-center mr-[30px]">Filtrer</h2>
                <img src="/src/assets/open.png" alt="search" class="absolute md:left-[1010px] md:top-[50px] top-[128px] right-[50px]">
                <div></div>
            </div>
        </div>
    </header>
    <main class="md:p-[80px] md:pt-[140px] pt-[190px] p-[16px]">
        <div class="">
            <h2 class="font-bold">LES PLUS POPULAIRES 🔥</h2>
            <div class="flex flex-row gap-[20px] absolute md:right-[80px] md:top-[611px] right-[20px] top-[655px]">
                <img src="/src/assets/Vector2.png" alt="">
                <img src="/src/assets/Vector1.png" alt="">
            </div>
        </div>
        <section class="flex md:flex-row gap-[30px] mt-[14px] flex-col">
            <Card3 class="" cardtitle="MANAGEMENT & LEADERSHIP" cardtext="Accueillir un.e collègue en situation de handicap" cardImg="src/assets/plane.png" />
            <Card class="md:block hidden" cardtitle="VENTE" cardtext="Accueillir un.e collègue en situation de handicap" cardImg="/src/assets/chess.png"/>
            <Card2 class="md:block hidden" cardtitle="RH,QVT & DIVERSITE" cardtext="Accueillir un.e collègue en situation de handicap" cardImg="/src/assets/hands.png"/>
            <Card3 class="md:block hidden" cardtitle="THEMATIQUE 1" cardtext="Accueillir un.e collègue en situation de handicap" cardImg="/src/assets/orange.png"/>
        </section>
        <div class="mt-[96px]">
            <h2 class="font-bold">TOUTES LES FORMATIONS 🚀</h2>
        </div>
        <section class="flex md:flex-row gap-[30px] mt-[36px] flex-col">
            <Card3 class="" cardtitle="THEMATIQUE 1" cardtext="Accueillir un.e collègue en situation de handicap" cardImg="/src/assets/pencil.png"/>
            <Card class="" cardtitle="THEMATIQUE 1" cardtext="Accueillir un.e collègue en situation de handicap" cardImg="/src/assets/tampon.png"/>
            <Card3 class="" cardtitle="THEMATIQUE 1" cardtext="Accueillir un.e collègue en situation de handicap" cardImg="/src/assets/egg.png"/>
            <Card class="" cardtitle="THEMATIQUE 1" cardtext="Accueillir un.e collègue en situation de handicap" cardImg="/src/assets/lolypop.png"/>
        </section>
        <section class="flex md:flex-row gap-[30px] mt-[36px] flex-col">
            <Card2 class="" cardtitle="THEMATIQUE 1" cardtext="Accueillir un.e collègue en situation de handicap" cardImg="/src/assets/lemon.png"/>
            <Card class="" cardtitle="THEMATIQUE 1" cardtext="Accueillir un.e collègue en situation de handicap" cardImg="/src/assets/cameleon.png"/>
            <Card class="" cardtitle="THEMATIQUE 1" cardtext="Accueillir un.e collègue en situation de handicap" cardImg="/src/assets/cloud.png"/>
            <Card class="" cardtitle="THEMATIQUE 1" cardtext="Accueillir un.e collègue en situation de handicap" cardImg="/src/assets/redthing.png"/>
        </section>
        <section class="md:flex flex-row gap-[30px] mt-[36px] hidden">
            <Card2 class="" cardtitle="THEMATIQUE 1" cardtext="Accueillir un.e collègue en situation de handicap" cardImg="/src/assets/matches.png"/>
            <Card class="" cardtitle="THEMATIQUE 1" cardtext="Accueillir un.e collègue en situation de handicap" cardImg="/src/assets/paperclip.png"/>
            <Card class="" cardtitle="THEMATIQUE 1" cardtext="Accueillir un.e collègue en situation de handicap" cardImg="/src/assets/chair.png"/>
            <Card class="" cardtitle="THEMATIQUE 1" cardtext="Accueillir un.e collègue en situation de handicap" cardImg="/src/assets/candies.png"/>
        </section>
    </main>
    <div class="flex flex-row gap-[24px] absolute md:right-[80px] right-[90px] top-[4350px] md:top-[2350px]">
        <div class="border-2 border-red-400 rounded-full h-[28px] w-[28px] flex">
            <p class="text-orange-500 text-[24px] m-auto">1</p>
        </div>
        <p>2</p>
        <p>3</p>
        <p>4</p>
        <p>...</p>
        <p>8</p>
    </div>
    <section class="md:w-[844px] md:h-[256px] rounded-xl bg-[#F3EDFB] flex flex-col justify-center m-auto mt-[178px] mb-[48px] w-[343px] md:p-0 p-[16px]">
            <div class="flex justify-center flex-col">
            <h3 class="text-center md:text-[40px] font-bold leading-8 text-[22px] fade2">C'est votre dernier mot ?</h3>
            <p class="text-center text-base leading-5 mt-[15px] md:w-[400px] m-auto">Si vous n'avez pas trouvé ce que vous cherchez, dites-le nous.</p>
            </div>
            <div class="flex justify-center md:flex-row md:gap-[30px] mt-[26px] flex-col gap-[12px]">
                <Button class="text-white bg-[#8D4ED8] bg-opacity-100 font-bold" textebutton="Je prends contact"/>
                <Button class="text-black bg-transparent border-2 font-bold fade p-6" textebutton="Télécharger le catalogue"/>
            </div>
    </section>

    <footer class="md:h-[477px] h-[578px] md:pl-[80px] md:pt-[90px] pt-[39px] bg-black">
        <div class="flex md:flex-row flex-col md:gap-[60px] gap-[8px]">
            <div class="md:w-[208px] md:h-[144px] w-[343px] h-[102px] flex flex-col gap-[8px] pl-[16px]">
                <img class="w-[140px]" src="/src/assets/Skillsday.png" alt="SkillsDay">
                <p class="text-white text-xs">Skillsday est un organisme nouvelle génération qui a pour mission de moderniser et digitaliser la formation en entreprise pour former, vraiment!</p>
            </div>
            <div class="flex flex-col gap-[8px] pl-0 ">
                <h4 class="bg-gray-500 text-white md:bg-black md:text-gray-500 mt-auto md:p-0 p-[16px]">SOLUTIONS</h4>
                <img class="md:hidden absolute right-[15px] top-[4932px]" src="/src/assets/Vector6.png" alt="test">
                <p class="hidden md:block text-white leading-5">Développer les softs skills</p>
                <p class="hidden md:block text-white leading-5">Digitaliser les formations</p>
                <p class="hidden md:block text-white leading-5">Accompagner les déploiements</p>
            </div>
            <div class="flex flex-col gap-[8px]">
                <h4 class="bg-gray-500 text-white md:bg-black md:text-gray-500 mt-auto md:p-0 p-[16px]">FORMATIONS</h4>
                <img class="md:hidden absolute right-[15px] top-[4995px]" src="/src/assets/Vector6.png" alt="test">
                <p class="hidden md:block text-white leading-5">Toutes les formations</p>
                <p class="hidden md:block text-white leading-5">Télécharger le catalogue</p>
                <p class="hidden md:block text-black leading-5">.</p>
            </div>
            <div class="flex flex-col gap-[8px]">
                <h4 class="bg-gray-500 text-white md:bg-black md:text-gray-500 mt-auto md:p-0 p-[16px]">INFORMATIONS</h4>
                <img class="md:hidden absolute right-[15px] top-[5058px]" src="/src/assets/Vector6.png" alt="test">
                <p class="hidden md:block text-white leading-5">Nous rejoindre</p>
                <p class="hidden md:block text-white leading-5">Nous contacter</p>
                <p class="hidden md:block text-white leading-5">FAQ</p>
            </div>
        </div>
        <div class="flex md:flex-row md:mt-[106px] mt-[30px] flex-col md:ml-0 ml-[16px]">
            <div class="flex flex-col md:flex-row md:gap-0 gap-[10px]">
                <p class="text-white text-[14px]">@Skillsday 2022</p>
                <p class="hidden md:block text-white text-[10px]">Mentions légales  •  Politiques de confidentialité  •  CGV</p>
                <p class="md:hidden block text-white text-[10px]">Mentions légales</p>
                <p class="md:hidden block text-white text-[10px]">Politiques de confidentialité</p>
                <p class="md:hidden block text-white text-[10px]">CGV</p>
            </div>
            <div class="flex flex-row gap-[15px] md:ml-[64px] ml-[82px] md:mt-[16px]  mt-[35px]">
                <div class="rounded-full w-[33px] h-[33px]"><img src="/src/assets/instagram.png" alt=""></div>
                <div class="rounded-full w-[33px] h-[33px]"><img src="/src/assets/linkedin.png" alt=""></div>
                <div class="rounded-full w-[33px] h-[33px]"><img src="/src/assets/share.png" alt=""></div>
                <div class="rounded-full w-[33px] h-[33px]"><img src="/src/assets/youtube.png" alt=""></div>
            </div>
        </div>
    </footer>

</template>


<style scoped>

</style>