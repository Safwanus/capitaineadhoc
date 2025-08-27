<template>
  <div class="font-sans">
    <header class="border-b border-black p-4 flex flex-wrap items-center justify-between gap-4 sticky top-0 bg-white/95 backdrop-blur">
      <div class="flex items-center gap-2">
        <MarineLogo class="w-8 h-8" />
        <span class="text-xl font-bold uppercase">Capitaine Ad’Hoc</span>
      </div>
      <nav class="flex flex-wrap gap-4 text-sm uppercase">
          <a href="#hero" class="hover:underline">Accueil</a>
          <a href="#mers-oc-ans" class="hover:underline">"Mers & Océans"</a>
          <a href="#campagne-freepaulwatson-sea-shepherd" class="hover:underline">Campagne #freepaulwatson - Sea Shepherd</a>
          <a href="#fermeture-marineland-situation-de-crise" class="hover:underline">Fermeture Marineland - Situation de crise</a>
          <a href="#mobilisation-projet-marineland2050" class="hover:underline">Mobilisation & Projet #marineland2050</a>
          <a href="#annonce-journal-officiel-15-juillet-2025" class="hover:underline">Annonce Journal Officiel - 15 Juillet 2025</a>
          <a href="#cap-vers-l-avenir" class="hover:underline">CAP VERS L’AVENIR</a>
          <a href="#rejoindre-la-flotte" class="hover:underline">Rejoindre la flotte</a>
          <a href="#un-quipage-des-partenaires-des-soutiens" class="hover:underline">Un équipage, des partenaires, des soutiens</a>
          <a href="#situation-de-crise" class="hover:underline">Situation de crise</a>
          <a href="#h-ritage-projet-d-avenir" class="hover:underline">Héritage & Projet d’avenir</a>
          <a href="#pourquoi-nous-soutenir" class="hover:underline">Pourquoi nous soutenir ?</a>
          <a href="#devenir-membre-donateurs" class="hover:underline">Devenir Membre & Donateurs</a>
          <a href="#journ-e-capitaine-ad-hoc-antibes" class="hover:underline">Journée Capitaine Ad’Hoc - Antibes</a>
          <a href="#calendrier-du-projet" class="hover:underline">Calendrier du Projet</a>
          <a href="#retour-vers-le-futur" class="hover:underline">RETOUR VERS LE FUTUR</a>
          <a href="#biodiversit-vie-marine-engagement-1" class="hover:underline">Biodiversité & Vie Marine - Engagement #1</a>
          <a href="#emplois-ressources-engagement-2" class="hover:underline">Emplois & Ressources- Engagement #2</a>
          <a href="#visiteurs-soci-taires-engagement-3" class="hover:underline">Visiteurs & Sociétaires - Engagement #3</a>
          <a href="#sc-ne-spectacles-engagement-4" class="hover:underline">Scène & Spectacles - Engagement #4</a>
          <a href="#education-kid-s-club-engagement-5" class="hover:underline">Education & Kid’s Club - Engagement #5</a>
          <a href="#recherche-formations-engagement-6" class="hover:underline">Recherche & Formations - Engagement #6</a>
          <a href="#citoyens-sauveteurs-engagement-7" class="hover:underline">Citoyens Sauveteurs - Engagement #7</a>
          <a href="#cuisine-saveurs-engagement-8" class="hover:underline">Cuisine & Saveurs - Engagement #8</a>
          <a href="#bien-tre-sant-engagement-9" class="hover:underline">Bien être & Santé - Engagement #9</a>
          <a href="#robotique-ia-engagement-10" class="hover:underline">Robotique & IA - Engagement #10</a>
          <a href="#r-alit-virtuelle-vr-engagement-11" class="hover:underline">Réalité Virtuelle VR - Engagement #11</a>
          <a href="#voile-navigation-engagement-12" class="hover:underline">Voile & Navigation - Engagement #12</a>
          <a href="#aujourd-hui-demain" class="hover:underline">AUJOURD’HUI & DEMAIN</a>
          <a href="#hello-asso-adh-sion-membres-dons" class="hover:underline">Hello Asso - Adhésion Membres & Dons</a>
          <a href="#dress-code-equipage-membres" class="hover:underline">Dress Code - Equipage & Membres</a>
          <a href="#crowdfunding-campagne-ulule-2025" class="hover:underline">Crowdfunding - Campagne Ulule 2025</a>
          <a href="#partenaires-banques-financement" class="hover:underline">Partenaires Banques & Financement</a>
          <a href="#interlocuteurs-incontournables" class="hover:underline">Interlocuteurs incontournables</a>
          <a href="#partenaires-associ-s-pme-start-up" class="hover:underline">Partenaires Associés - PME & Start-up</a>
          <a href="#collectivit-s-locales-labels" class="hover:underline">Collectivités Locales & Labels</a>
          <a href="#partenaires-institutionnels-m-c-nat" class="hover:underline">Partenaires Institutionnels & Mécénat</a>
          <a href="#qr-code" class="hover:underline">QR CODE</a>
      </nav>
    </header>

    <main>
      <Hero />
      <Section01 />
      <Section02 />
      <Section03 />
      <Section04 />
      <Section05 />
      <Section06 />
      <Section07 />
      <Section08 />
      <Section09 />
      <Section10 />
      <Section11 />
      <Section12 />
      <Section13 />
      <Section14 />
      <Section15 />
      <Section16 />
      <Section17 />
      <Section18 />
      <Section19 />
      <Section20 />
      <Section21 />
      <Section22 />
      <Section23 />
      <Section24 />
      <Section25 />
      <Section26 />
      <Section27 />
      <Section28 />
      <Section29 />
      <Section30 />
      <Section31 />
      <Section32 />
      <Section33 />
      <Section34 />
      <Section35 />
      <Section36 />
      <Section37 />
    </main>

    <footer class="p-6 border-t border-black text-center text-sm uppercase">
      <p>© 2025 Capitaine Ad’Hoc — Mers & Océans</p>
      <p class="mt-2">#freepaulwatson #marineland2050 #capitaineadhoc</p>
    </footer>
  </div>
</template>

<script setup>
import MarineLogo from './components/MarineLogo.vue'
import Hero from './components/Hero.vue'
import Section01 from './components/Section01.vue'
import Section02 from './components/Section02.vue'
import Section03 from './components/Section03.vue'
import Section04 from './components/Section04.vue'
import Section05 from './components/Section05.vue'
import Section06 from './components/Section06.vue'
import Section07 from './components/Section07.vue'
import Section08 from './components/Section08.vue'
import Section09 from './components/Section09.vue'
import Section10 from './components/Section10.vue'
import Section11 from './components/Section11.vue'
import Section12 from './components/Section12.vue'
import Section13 from './components/Section13.vue'
import Section14 from './components/Section14.vue'
import Section15 from './components/Section15.vue'
import Section16 from './components/Section16.vue'
import Section17 from './components/Section17.vue'
import Section18 from './components/Section18.vue'
import Section19 from './components/Section19.vue'
import Section20 from './components/Section20.vue'
import Section21 from './components/Section21.vue'
import Section22 from './components/Section22.vue'
import Section23 from './components/Section23.vue'
import Section24 from './components/Section24.vue'
import Section25 from './components/Section25.vue'
import Section26 from './components/Section26.vue'
import Section27 from './components/Section27.vue'
import Section28 from './components/Section28.vue'
import Section29 from './components/Section29.vue'
import Section30 from './components/Section30.vue'
import Section31 from './components/Section31.vue'
import Section32 from './components/Section32.vue'
import Section33 from './components/Section33.vue'
import Section34 from './components/Section34.vue'
import Section35 from './components/Section35.vue'
import Section36 from './components/Section36.vue'
import Section37 from './components/Section37.vue'
</script>
