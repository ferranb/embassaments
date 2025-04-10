# Embassaments de Catalunya

La informació dels embassaments de Catalunya està disponible ens aquestes xarxes socials:

- Bluesky:
  - https://bsky.app/profile/embassamentscat.bsky.social
  - Cada hora dia i nit.
- Twitter:
  - https://x.com/Embassamentscat
  - Cada hora entre les 8:00 i les 23:00 inclosses. Això és degut a la límitació de l'API de twitter amb el número màxim de piulades per dia. 
- Instagram:
  - https://www.instagram.com/embassaments

Les dades s'obtenen de l'API de dades obertes de l'[Agència Catalana de l'Aigua (ACA)](https://aca.gencat.cat/ca/inici/index.html) i es publiquen automàticament a les xarxes socials anteriors amb criteris diferents. També es fan algunes publicacions manualment de manera puntual. 

La primera dada es va publicar a twitter el [22 de Maig del 2024](https://x.com/Embassamentscat/status/1793296839057301744).

# [Preguntes frequents](#preguntesfrequents)

## Sobre el projecte

**Aquest projecte pertany a algun organisme oficial?** 

No. Aquest projecte no té cap mena de relació amb cap organisme públic ni privat, ni cap partit polític, associació o fundació. Està gestionat per una persona individual.

## Sobre les dades

**D'on surten les dades?** 

L'Agència Catalana de l'Aigua disposa d'un conjunt de dades obertes que actualitza constantment. A l'apartat següent hi trobaràs més detall.

**Per què només es publiquen dades de les conques internes?**

És una qüestió relacionada amb les dades obertes. Ara mateix, les dades s'obtenen de l'API de l'ACA, que només proporciona informació tractable de les conques internes. Quan hi hagi temps, es mirarà d'afegir la resta :-)

**Per què hi ha tanta diferència entre el percentatge indicat i les dades que publica l'ACA a la pàgina d'estat dels embassamnets?**

La dada que apareix a [Estat dels embassaments](https://aca.gencat.cat/ca/laigua/estat-del-medi-hidric/recursos-disponibles/estat-de-les-reserves-daigua-als-embassaments/) s'actualitza diàriament cap a les 12:00 i correspon a unes dades d'hores anteriors. En canvi, les dades que es publiquen en aquests comptes són les més recents disponibles mitjançant l'API.

**Per què hi ha tanta diferència entre el percentatge indicat i les dades que publica embalses.net?**

A [embalses.net](https://www.embalses.net) es publiquen dues sèries de dades sobre els embassaments de Catalunya. Per una banda, les dades de [totes les conques de Catalunya](https://www.embalses.net/comunidad-10-cataluna.html) i, per l'altra, les dades de les [conques internes](https://www.embalses.net/cuenca-11-cataluna-interna.html).

A dia d'avui, aquesta projecte publica les dades de les conques internes, perquè són les dades que proporciona l'ACA. Més endavant, quan sigui possible, també es publicaran les de la resta de conques.

## Sobre els embassaments

**Per què hi ha embassaments que superen el 100% de capacitat?**

Per cada embassament, l'ACA esbleix volum màxim de referència. Quan una xifa supera el 100%, és perquè el volum actual és superior a aquest llindar. En alguns casos, això pot indicar que l'embassament està sobreei.

**Per què tal embassament està buit si tal altre està ple o tal riu no se què?**

No ho sabem. Això s'ha de preguntar-ho directament a l'[ACA](https://x.com/aigua_cat).

**Si ha plogut tant, com pot ser que tal embassament estigui buit?**

Perquè, com diuen els metereòlegs, a més de ploure, ha de ploure bé. En el cas dels embassaments de les conques internes, cal que plogui a les zones indicades en aquest [mapa](https://x.com/aigua_cat/status/1662007831199989760) que l'ACA va publicar en el seu moment.

**Per què Gaià i el Pasteral apareixen per separat?**

Perquè no entren dins del còmput de les conques internes. 

**Què volen dir les fases?**

A [aquesta pàgina](https://sequera.gencat.cat/ca/accions/el-semafor-de-la-sequera/index.html) de l'ACA s'hi expliquen els criteris que defineixen cada fase.

## Sobre les imatges del radar

**Per què les imatges del radar no mostren precipitació sí en realitat està plovent?**

[Aquí](https://x.com/meteocat/status/1892876743951675486), els del Meteocat, ho expliquen molt bé.

**D'on surten les imatges del radar que es publiquen?**

Malauradament no s'ha trobat cap API que les publiqui així que es fa servir [web scraping](https://ca.wikipedia.org/wiki/Web_scraping).

## Sobre l'automatització

**Totes les publicacions es fan mitjançant un bot?**

- Les publicacions de les dades en format text i els gràfics de la "gota" són totalment automatitzades. 
- La resta de gràfics es generen automàticament, però es publiquen manualment.
- Les respostes als comentaris, de moment, són manuals.

**Es publicarà el codi font de l'automatització en algun moment?** 

Aquesta és la idea, sí. Quan? No se sap.

## Altres... però no menys importants

**El [tuit](https://x.com/Embassamentscat/status/1903815824713929078) sobre el debat dels límits de l'humor és seriós?** 

Aquesta pregunta, és seriosa?

**Ja em puc dutxar?**

I tant. Com més aviat, millor, sisplau!

# [Dades obertes](#dadesobertes)

Informe diari de l'estat dels embassaments:

- [Estat dels embassaments](https://aca.gencat.cat/ca/laigua/estat-del-medi-hidric/recursos-disponibles/estat-de-les-reserves-daigua-als-embassaments/). Aquí hi trobaràs la xifra oficial de l'ACA de l'estat actual dels embassaments. Aquesta dada es publica cada dia, capa a les 12 del migdia, i pots consultar-ne el detall a l'[Informe diari de l'estat de tots els embassaments a tot catalunya](https://info.aca.gencat.cat/ca/aca/informacio/informesdwh/dades_embassaments_ca.pdf).

Eines visuals amb dades a temps real:
  - [Dades a temps real de l'ACA](https://aplicacions.aca.gencat.cat/sdim2/visor/) amb la plataforma [Sentilo](https://www.sentilo.io/).
  - [Eina visual de l'ACA sobre l'estat dels embassaments](https://aca.gencat.cat/ca/laigua/consulta-de-dades/dades-obertes/visualitzacio-interactiva-dades/estat-embassaments/).
  - [Un altre visor molt interessant](https://aplicacions.aca.gencat.cat/aetr/vishid/#ara).

Dades obertes per us d'aplicacions o analístes de dades:

- [Dades obertes a temps real](https://aca.gencat.cat/ca/laigua/consulta-de-dades/dades-obertes/dades-obertes-temps-real/) on trobareu els enllaços i també el [Manual d’ús del servei API-REST de l'ACA](https://aca.gencat.cat/web/.content/20_Aigua/08_consulta_de_dades/01_dades_obertes/02_dades_obertes_temps_real/us_serveis_dades_API_REST.pdf).
- [Catàleg de dades obertes](https://aca.gencat.cat/ca/laigua/consulta-de-dades/dades-obertes/cataleg-dades-obertes/).
- [Quantitat d’aigua als embassaments de les Conques Internes de Catalunya](https://analisi.transparenciacatalunya.cat/Medi-Ambient/Quantitat-d-aigua-als-embassaments-de-les-Conques-/gn9e-3qhr/about_data). Dades obertes dels embassaments de conques internes. La granularitat és diària.
- Pels més curiosos, les crides a l'API (Application Programming Interface) que es fan servir per actualitzar les dades que es publiquen:
  - [Catàleg de sensors](https://aplicacions.aca.gencat.cat/sdim2/apirest/catalog?componentType=embassament).
  - [Crida a les darreres dades dels sensors](https://aplicacions.aca.gencat.cat/sdim2/apirest/data/EMBASSAMENT-EST).

Altres enllaços:
- [Preses i embassaments de Catalunya](https://aca.gencat.cat/ca/laigua/infraestructures/preses-i-embassaments).
- [Informació hidrològica de l'Ebre](https://www.saihebro.com/homepage/estado-cuenca-ebro).
- [Informació d'embassaments del Departament d'Agricultura Ramaderia i Alimentació](https://agricultura.gencat.cat/ca/ambits/desenvolupament-rural/infraestructures-agraries/dar_regadius/estat-embassaments-catalunya/index.html).
