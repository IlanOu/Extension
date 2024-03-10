<template>
<!-- <ContentDoc path="/test"/> -->

<div class="mx-60 max-w-1/1 centered">
 
  <div class="topBar">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/63/Wikipedia-logo.png" alt="logo Wikipedia" class="w-20">
  
    <input type="text" class="shadowTopbar bg-[#e0dffd] placeholder-[#7766C688] text-[#7766c6] outline-none w-96 h-10 rounded-full text-sm px-4 py-2" placeholder="Rechercher sur Wikipédia"/>

    <div class="h-10 w-10 bg-[#e0dffd] rounded-full shadowTopbar cursor-pointer hover:bg-[#7766C6] transition-all ease"></div>
  </div>

  <div class="row mt-36">
    <h2 class="text-2xl font-bold text-[#7766C6]">Bienvenue sur Wikipédia</h2>
    <hr>
  </div>

  <div class="columns row my-10">
    <Block title="Présentation" class="my-2 mr-1.5 pt-5">
      <div class="divContent mt-2">
        <div>
          <p class="my-4">
            <a class="font-bold hover:underline" href="">Wikipédia</a> est un projet d’encyclopédie collective en ligne, universelle, multilingue et fonctionnant sur le principe du wiki. Ce projet vise à offrir un contenu librement réutilisable, objectif et vérifiable, que chacun peut modifier et améliorer.
          </p>
          <p class="my-4">
            <a class="font-bold hover:underline" href="">Wikipédia</a> est définie par des principes fondateurs. Son contenu est sous licence Creative Commons BY-SA. Il peut être copié et réutilisé sous la même licence, sous réserve d'en respecter les conditions.
          </p>
        </div>
        <Button value="Voir plus" class="m2-4"/>
      </div>
    </Block>
  
    <Block title="Comment contribuer ?" class="my-2 mr-1.5 pt-5">
      <div class="divContent mt-2">
        <div>
          <p class="my-4">
            Chacun peut publier immédiatement du contenu en ligne, à condition de respecter les règles essentielles établies par <a class="font-bold hover:underline" href="">la Fondation Wikimedia</a> et par la communauté ; par exemple, <a class="font-bold hover:underline" href="">la vérifiabilité du contenu</a>, <a class="font-bold hover:underline" href="">l'admissibilité des articles</a> et <a class="font-bold hover:underline" href="">garder une attitude cordiale</a>.
          </p>
          <p class="my-4">
            De nombreuses pages d’aide sont à votre disposition, notamment pour <a class="font-bold hover:underline" href="">créer un article</a>, <a class="font-bold hover:underline" href="">modifier un article</a> ou <a class="font-bold hover:underline" href="">insérer une image</a>.
          </p>
        </div>
        <Button value="Voir plus" class="m2-4"/>
      </div>
    </Block>
  </div>

  <div class="columns row my-10">
    <Block title="Actualités" class="my-2 mr-1.5 pt-5">
      <div class="divContent mt-2">
        <ul>
          <li>
            <b>10 mars</b> : au Portugal, <a class="font-bold hover:underline" href="">les élections législatives</a> ont lieu de manière anticipée en raison de la démission du <a class="font-bold hover:underline" href="">Premier ministre</a> après un scandale de corruption.
          </li>
          <li>
            <b>8 mars</b> : lors de <a class="font-bold hover:underline" href="">la Journée internationale des femmes</a>, les Irlandais refusent deux amendements soumis à <a class="font-bold hover:underline" href="">référendums constitutionnels</a>, l'un qui visait à redéfinir le terme de famille et l'autre qui visait à remplacer un article mentionnant l'importance de protéger les mères pour qu'elles ne « négligent pas les devoirs de leur foyer ».
          </li>
          <li>
            <b>7 mars</b> : la Suède met fin à deux siècles de neutralité en devenant le 32e membre de <a class="font-bold hover:underline" href="">l'Organisation du traité de l'Atlantique nord (OTAN)</a> <a class="font-bold hover:underline" href="">(carte)</a>.
          </li>
          <li>
            <b>4 mars</b> : la France devient le premier pays au monde à inscrire la liberté de recourir à <a class="font-bold hover:underline" href="">l'interruption volontaire de grossesse</a> dans sa <a class="font-bold hover:underline" href="">Constitution</a>.
          </li>
        </ul>
        <Button value="Voir plus" class="m2-4"/>
      </div>
    </Block>
  
    <Block title="Éphéméride" class="my-2 mr-1.5 pt-5" style="width: 75%;">
      <div class="divContent mt-2">
        <div>
          <ul>
            <li>
              <b>1535</b> : <a class="font-bold hover:underline" href="">Tomas de Berlanga</a>, évêque de Panama, découvre <a class="font-bold hover:underline" href="">les îles Galápagos</a>.
            </li>
            <li>
              <b>1793</b> : en France, en pleine <a class="font-bold hover:underline" href="">Terreur</a>, la <a class="font-bold hover:underline" href="">Convention nationale</a> crée <a class="font-bold hover:underline" href="">le Tribunal révolutionnaire</a>, juridiction d'exception qui enverra à la guillotine 585 personnes en seize mois.
            </li>
            <li>
              <b>1899</b> : en France est promulgué <a class="font-bold hover:underline" href="">le premier décret sur la circulation automobile</a>, qui limite la vitesse à 20 km/h en ville et 30 km/h hors agglomération.
            </li>
            <li>
              <b>1906</b> : à Courrières, dans le Pas-de-Calais, un coup de poussier dévaste 110 kilomètres de galeries de mine et tue 1 099 mineurs ;
            </li>
          </ul>

        </div>
        <Button value="Voir plus" class="m2-4"/>
      </div>
    </Block>
  </div>


  <Block title="Le saviez-vous ?" class="row m-3 my-10">
    <div class="divContent mt-2">
        <div>
          <ul>
            <li>
              <a class="font-bold hover:underline" href="">Bernard Hill (photo)</a> est le seul acteur a avoir joué dans deux des trois films qui ont reçu onze <a class="font-bold hover:underline" href="">Oscars</a> : <a class="font-bold hover:underline" href="">Titanic</a> et <a class="font-bold hover:underline" href="">Le Seigneur des anneaux : Le Retour du roi</a>.
            </li>
            <li>
              <a class="font-bold hover:underline" href=""></a>Jean-Paul Sartre a été nommé aux <a class="font-bold hover:underline" href=""></a>Oscars pour le film <a class="font-bold hover:underline" href=""></a>Les Orgueilleux en 1957.
            </li>
            <li>
              Le combat de Hampton Roads, pendant la guerre de Sécession, est le premier combat naval entre navires cuirassés.
            </li>
            <li>
              Seuls trois films ont reçu onze <a class="font-bold hover:underline" href="">Oscars</a>, le maximum à l’heure actuelle : <a class="font-bold hover:underline" href="">Ben Hur</a>, <a class="font-bold hover:underline" href="">Titanic</a> et <a class="font-bold hover:underline" href="">Le Seigneur des anneaux : Le Retour du roi</a>.
            </li>
            <li>
              Jusqu’en 1967, les femmes avaient interdiction d’entrer dans <a class="font-bold hover:underline" href="">la Bourse de Paris</a>.
            </li>
            <li>
              En 2021, au sein d’une population mondiale majoritairement masculine, le nombre d’hommes pour 100 femmes variait de 266 au Qatar à 81,9 en Arménie.
            </li>
          </ul>

        </div>
        <Button value="Voir plus" class="m2-4"/>
      </div>
  </Block>



</div>


<div class="bg-[#e0dffd] px-5 py-10 mt-36 text-[#7766C6] text-sm">
  <p>
    La dernière modification de cette page a été faite le 11 juin 2023 à 07:46.
  </p>
  <br>
  <p>
    Droit d'auteur : les textes sont disponibles sous licence Creative Commons attribution, partage dans les mêmes conditions ; d’autres conditions peuvent s’appliquer. Voyez les conditions d’utilisation pour plus de détails, ainsi que les crédits graphiques.
  </p>
  <p>
    Wikipedia® est une marque déposée de la Wikimedia Foundation, Inc., organisation de bienfaisance régie par le paragraphe 501(c)(3) du code fiscal des États-Unis.
  </p>
  <br>
  <p>
    <a class="font-bold hover:underline" href="">Politique de confidentialité</a> - <a class="font-bold hover:underline" href="">À propos de Wikipédia</a> - <a class="font-bold hover:underline" href="">Avertissements</a> - <a class="font-bold hover:underline" href="">Contact Code de conduite</a> - <a class="font-bold hover:underline" href="">Développeurs</a> - <a class="font-bold hover:underline" href="">Statistiques</a> - <a class="font-bold hover:underline" href="">Déclaration sur les témoins (cookies)</a> - <a class="font-bold hover:underline" href="">Version mobile</a>
  </p>
</div>


</template>

<style scoped>

.topBar{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 50rem;
}

.shadowTopbar{
  box-shadow: 0 5px 5px 0px rgba(224, 223, 253, 0.5);
  transition: all 0.25s ease;
}

.shadowTopbar:focus{
  box-shadow: 0 0px 5px 0px rgba(224, 223, 253, 0.5);
}


h2{
  align-self: flex-start;
}

hr {
    border: solid 1px #e0dffd;
}


li {
  list-style-type: circle;
  margin-left: 1rem;
  padding: 0.25rem;
}

.centered {
  display: flex;
  align-items: center;
  flex-direction: column;
}

.columns {
  display: flex;
  justify-content: center;
}

.row{
  width: 50rem;
}

.row > * {
  width: 100%;
}

.divContent{
  display: flex;
  flex-direction: column;
  align-items: flex-end;
}

</style>