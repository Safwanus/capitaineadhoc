<template>
  <div class="font-sans">
    <!-- Fixed header -->
    <header class="fixed top-0 left-0 right-0 bg-white border-b border-black z-50">
      <div class="max-w-6xl mx-auto p-4 flex justify-between items-center">
        <div class="flex items-center gap-2">
          <MarineLogo class="w-8 h-8" />
          <span class="text-xl font-bold uppercase">Capitaine Ad'Hoc</span>
        </div>
        <nav class="uppercase text-xs md:text-sm flex flex-wrap gap-4">
          <a href="#hero">Accueil</a>
          <a href="#mobilisation">Mobilisations</a>
          <a href="#fermeture">Fermeture</a>
          <a href="#marineland2050">Marineland2050</a>
          <a href="#association">Association</a>
          <a href="#avenir">Cap vers l’avenir</a>
          <a href="#engagements">Engagements</a>
          <a href="#helloasso">HelloAsso</a>
          <a href="#ulule">Ulule</a>
          <a href="#partenaires">Partenaires</a>
          <a href="#qrcode">QR Code</a>
        </nav>
      </div>
    </header>

    <!-- Scroll-snap container -->
    <main class="snap-y snap-mandatory h-screen overflow-y-scroll">
      <!-- Hero -->
      <section id="hero" class="h-screen snap-start flex flex-col justify-center items-center px-6 pt-20 text-center border-b border-black">
        <MarineLogo class="w-16 h-16 mb-4" />
        <h1 class="text-4xl md:text-5xl font-bold uppercase tracking-wide">Mers & Océans</h1>
        <p class="mt-4 max-w-3xl">Association Capitaine Ad’Hoc — Antibes, Côte d’Azur, France</p>
        <div class="absolute bottom-6 left-0 right-0 flex justify-center">
          <span class="animate-bounce select-none">↓</span>
        </div>
      </section>

      <!-- Mobilisation: #freepaulwatson -->
      <section id="mobilisation" class="h-screen snap-start flex flex-col justify-center px-6 border-b border-black">
        <h2 class="text-3xl md:text-4xl font-bold uppercase">Appel à mobilisation — #freepaulwatson</h2>
        <p class="mt-4 max-w-3xl">Juillet à décembre 2024</p>
        <p class="mt-4 max-w-3xl">Archibald Ad’Hoc soutient le fondateur de Greenpeace et Sea Shepherd en rencontrant des associations comme One Voice, des élus locaux, et en mobilisant sur les réseaux sociaux.</p>
        <p class="mt-4 max-w-3xl">Sans militantisme : un engagement pour libérer un innocent.</p>
        <div class="mt-8 text-sm uppercase">Campagne — Sea Shepherd</div>
        <div class="absolute bottom-6 left-0 right-0 flex justify-center">
          <span class="animate-bounce select-none">↓</span>
        </div>
      </section>

      <!-- Fermeture Marineland -->
      <section id="fermeture" class="h-screen snap-start flex flex-col justify-center px-6 border-b border-black">
        <h2 class="text-3xl md:text-4xl font-bold uppercase">Fermeture de Marineland</h2>
        <p class="mt-4 max-w-3xl">5 janvier 2025</p>
        <p class="mt-4 max-w-3xl">Paul Watson s’est battu pour la fermeture de Marineland.</p>
        <p class="mt-4 max-w-3xl">Le Capitaine Ad’Hoc, parmi les derniers visiteurs et témoin de cette catastrophe, s’engage à trouver des solutions : transformer une situation d’échec en réussite collective, gagnante pour tous.</p>
        <div class="absolute bottom-6 left-0 right-0 flex justify-center">
          <span class="animate-bounce select-none">↓</span>
        </div>
      </section>

      <!-- Marineland2050 -->
      <section id="marineland2050" class="h-screen snap-start flex flex-col justify-center px-6 border-b border-black">
        <h2 class="text-3xl md:text-4xl font-bold uppercase">Mobilisation & Projet — #Marineland2050</h2>
        <p class="mt-4 max-w-3xl">Janvier à juin 2025</p>
        <p class="mt-4 max-w-3xl">Une vingtaine d’engagements, un projet de reconversion fédérant acteurs publics et privés, mobilisant une équipe.</p>
        <p class="mt-4 max-w-3xl">Marineland est un nom lourd à porter, mais notre projet, c’est l’avenir.</p>
        <p class="mt-4 max-w-3xl">Axes : bien-être animal, emploi, innovation, spectacle, loisirs, tourisme, éducation.</p>
        <div class="absolute bottom-6 left-0 right-0 flex justify-center">
          <span class="animate-bounce select-none">↓</span>
        </div>
      </section>

      <!-- Association announcement -->
      <section id="association" class="h-screen snap-start flex flex-col justify-center px-6 border-b border-black">
        <h2 class="text-3xl md:text-4xl font-bold uppercase">Annonce au Journal Officiel</h2>
        <p class="mt-4 max-w-3xl">15 juillet 2025</p>
        <p class="mt-4 max-w-3xl">Après la signature des statuts, la constitution d’un bureau, et avec le soutien d’administrateurs et d’entreprises partenaires, l’association Capitaine Ad’Hoc “Mers & Océans” est née.</p>
        <p class="mt-4 max-w-3xl">Un statut associatif pour développer notre initiative dans un cadre juridique ouvert.</p>
        <div class="absolute bottom-6 left-0 right-0 flex justify-center">
          <span class="animate-bounce select-none">↓</span>
        </div>
      </section>

      <!-- Cap vers l'avenir -->
      <section id="avenir" class="h-screen snap-start flex flex-col justify-center px-6 border-b border-black">
        <h2 class="text-3xl md:text-4xl font-bold uppercase">Cap vers l’avenir</h2>
        <p class="mt-4 max-w-3xl">Rejoindre la flotte. Un équipage, des partenaires, des soutiens. Situation de crise, héritage et projet d’avenir. Pourquoi nous soutenir ? Devenir membre & donateurs. Journée Capitaine Ad’Hoc — Antibes. Calendrier du projet. Retour vers le futur.</p>
        <div class="absolute bottom-6 left-0 right-0 flex justify-center">
          <span class="animate-bounce select-none">↓</span>
        </div>
      </section>

      <!-- Engagements 1-12 -->
      <section id="engagements" class="h-screen snap-start flex flex-col justify-center px-6 border-b border-black">
        <h2 class="text-3xl md:text-4xl font-bold uppercase">Nos 12 engagements</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mt-6 text-sm leading-relaxed">
          <div>
            <h3 class="font-bold uppercase">#1 Biodiversité & Vie Marine</h3>
            <p class="mt-4 max-w-3xl">Protection et valorisation de la vie marine.</p>
          </div>
          <div>
            <h3 class="font-bold uppercase">#2 Emplois & Ressources</h3>
            <p class="mt-4 max-w-3xl">Création d’emplois et gestion durable des ressources.</p>
          </div>
          <div>
            <h3 class="font-bold uppercase">#3 Visiteurs & Sociétaires</h3>
            <p class="mt-4 max-w-3xl">Expérience et participation des visiteurs et sociétaires.</p>
          </div>
          <div>
            <h3 class="font-bold uppercase">#4 Scène & Spectacles</h3>
            <p class="mt-4 max-w-3xl">Programmation de scènes et spectacles responsables.</p>
          </div>
          <div>
            <h3 class="font-bold uppercase">#5 Éducation & Kid’s Club</h3>
            <p class="mt-4 max-w-3xl">Actions pédagogiques et clubs pour enfants.</p>
          </div>
          <div>
            <h3 class="font-bold uppercase">#6 Recherche & Formations</h3>
            <p class="mt-4 max-w-3xl">Recherche appliquée et formations spécialisées.</p>
          </div>
          <div>
            <h3 class="font-bold uppercase">#7 Citoyens Sauveteurs</h3>
            <p class="mt-4 max-w-3xl">Implication des citoyens dans la sauvegarde marine.</p>
          </div>
          <div>
            <h3 class="font-bold uppercase">#8 Cuisine & Saveurs</h3>
            <p class="mt-4 max-w-3xl">Valorisation des saveurs responsables de la mer.</p>
          </div>
          <div>
            <h3 class="font-bold uppercase">#9 Bien-être & Santé</h3>
            <p class="mt-4 max-w-3xl">Bien-être animal et santé des écosystèmes.</p>
          </div>
          <div>
            <h3 class="font-bold uppercase">#10 Robotique & IA</h3>
            <p class="mt-4 max-w-3xl">Technologies au service de l’océan : robotique et IA.</p>
          </div>
          <div>
            <h3 class="font-bold uppercase">#11 Réalité Virtuelle (VR)</h3>
            <p class="mt-4 max-w-3xl">Immersion et sensibilisation par la réalité virtuelle.</p>
          </div>
          <div>
            <h3 class="font-bold uppercase">#12 Voile & Navigation</h3>
            <p class="mt-4 max-w-3xl">Navigation, voile et culture maritime.</p>
          </div>
        </div>
        <div class="absolute bottom-6 left-0 right-0 flex justify-center">
          <span class="animate-bounce select-none">↓</span>
        </div>
      </section>

      <!-- HelloAsso -->
      <section id="helloasso" class="h-screen snap-start flex flex-col justify-center px-6 border-b border-black">
        <h2 class="text-3xl md:text-4xl font-bold uppercase">HelloAsso — Adhésions & Dons</h2>
        <p class="mt-4 max-w-3xl">Référence pour le développement des activités et projets associatifs, Capitaine Ad’Hoc s’appuie sur HelloAsso pour la gestion des adhésions, des dons et sa communication.</p>
        <p class="mt-4 max-w-3xl">Une plateforme française : un choix naturel et sécurisé pour nos membres et donateurs.</p>
        <div class="absolute bottom-6 left-0 right-0 flex justify-center">
          <span class="animate-bounce select-none">↓</span>
        </div>
      </section>

      <!-- Dress Code -->
      <section id="dresscode" class="h-screen snap-start flex flex-col justify-center px-6 border-b border-black">
        <h2 class="text-3xl md:text-4xl font-bold uppercase">Dress Code — Équipage & Membres</h2>
        <p class="mt-4 max-w-3xl">Portez nos couleurs : un soutien important et efficace.</p>
        <p class="mt-4 max-w-3xl">Un nom, un logo, une identité, une communauté. Nous faire connaître et se reconnaître, développer notre notoriété, participer à un élan.</p>
        <div class="absolute bottom-6 left-0 right-0 flex justify-center">
          <span class="animate-bounce select-none">↓</span>
        </div>
      </section>

      <!-- Ulule -->
      <section id="ulule" class="h-screen snap-start flex flex-col justify-center px-6 border-b border-black">
        <h2 class="text-3xl md:text-4xl font-bold uppercase">Crowdfunding — Ulule 2025</h2>
        <p class="mt-4 max-w-3xl">En novembre et décembre 2025, lancement de la campagne de collecte Capitaine Ad’Hoc avec Ulule, spécialistes français du financement participatif.</p>
        <p class="mt-4 max-w-3xl">Objectif : réunir de 5 000 à 4 millions d’euros. Déjà 50 000 projets soutenus sur Ulule.</p>
        <div class="absolute bottom-6 left-0 right-0 flex justify-center">
          <span class="animate-bounce select-none">↓</span>
        </div>
      </section>

      <!-- Partenaires -->
      <section id="partenaires" class="h-screen snap-start flex flex-col justify-center px-6 border-b border-black">
        <h2 class="text-3xl md:text-4xl font-bold uppercase">Partenaires</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mt-6 text-sm leading-relaxed">
          <div>
            <h3 class="font-bold uppercase">Banques & Financement</h3>
            <ul class="list-disc pl-6 mt-2">
              <li>Crédit Coopératif — gestion du compte bancaire Capitaine Ad’Hoc.</li>
              <li>Banque des Territoires — financement public du projet Capitaine Ad’Hoc.</li>
              <li>Caisse des Dépôts — garantie de financement public.</li>
            </ul>
            <p class="mt-4 max-w-3xl">L’épargne des Français et les banques coopératives sont des leviers pour les initiatives.</p>
          </div>
          <div>
            <h3 class="font-bold uppercase">Interlocuteurs incontournables</h3>
            <p class="mt-4 max-w-3xl">Parques Reunidos — acteur mondial des parcs d’attractions. Aquasplash, Adventure Golf, So Blue à Antibes.</p>
            <p class="mt-4 max-w-3xl">Évolution de la loi française, accusations de maltraitance animale, pertes financières : ils ont fermé Marineland. Ils ont des droits, ils respectent les lois.</p>
            <p class="mt-4 max-w-3xl">Trop souvent accusés : bâtir l’avenir avec eux est possible et souhaitable — un projet gagnant pour tous.</p>
          </div>
          <div>
            <h3 class="font-bold uppercase">Partenaires associés — PME & Start-up</h3>
            <p class="mt-4 max-w-3xl">Capitaine Ad’Hoc s’entoure de partenaires stratégiques pour contribuer au succès du projet : des PME, leaders sur leurs marchés, et des start-up, toutes impliquées dans la réalisation de nos objectifs.</p>
            <p class="mt-4 max-w-3xl">La plupart accepte de s’engager ; nous espérons fédérer ces acteurs, et d’autres.</p>
          </div>
          <div>
            <h3 class="font-bold uppercase">Collectivités locales & Labels</h3>
            <p class="mt-4 max-w-3xl">Réussir un tel projet nécessite le soutien de la Ville d’Antibes, du Département des Alpes-Maritimes, de Côte d’Azur France Tourisme et de la Région Sud.</p>
            <p class="mt-4 max-w-3xl">Une étape essentielle vers une réussite collective : enjeux économiques, sociaux et environnementaux.</p>
          </div>
          <div>
            <h3 class="font-bold uppercase">Partenaires institutionnels & Mécénat</h3>
            <p class="mt-4 max-w-3xl">Trois partenaires à convaincre — des grandes entreprises françaises, acteurs importants dans l’économie locale, implantées à Sophia Antipolis.</p>
            <p class="mt-4 max-w-3xl">Mécénat de compétences, soutien technologique et financier.</p>
            <ul class="list-disc pl-6 mt-2">
              <li>Air France</li>
              <li>Amadeus</li>
              <li>Thales</li>
            </ul>
            <p class="mt-4 max-w-3xl">Nous invitons toutes les grandes entreprises à nous soutenir, aux côtés de ces acteurs.</p>
          </div>
        </div>
      </section>

      <!-- QR Code -->
      <section id="qrcode" class="h-screen snap-start flex flex-col justify-center items-center px-6 border-b border-black text-center">
        <h2 class="text-3xl md:text-4xl font-bold uppercase">QR Code</h2>
        <p class="mt-4 max-w-3xl">Scannez pour en savoir plus (QR code à intégrer ici).</p>
        <div class="mt-8 w-40 h-40 border border-black flex items-center justify-center">QR</div>
      </section>
    </main>

    <footer class="border-t border-black p-4 text-center text-xs uppercase">
      <div>© 2025 Capitaine Ad’Hoc — Mers & Océans</div>
      <div class="mt-2">#freepaulwatson #marineland2050 #capitaineadhoc</div>
    </footer>
  </div>
</template>

<script setup>
import MarineLogo from './components/MarineLogo.vue'
</script>

<style scoped>
/* Force squared look by avoiding rounded corners everywhere */
* { border-radius: 0 !important; }
</style>
