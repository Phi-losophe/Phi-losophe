# **Frustration Géométrique Aérodynamique : Principes de Physique de la Matière Condensée Appliqués à la Récupération d'Énergie Éolienne Non-Conventionnelle**

## **Résumé Exécutif**

Ce rapport de recherche approfondi explore la faisabilité théorique et technique d'appliquer le concept de « frustration géométrique » — originaire de la physique de la matière condensée — à la dynamique des fluides pour la conception de nouvelles technologies éoliennes. La frustration géométrique décrit des systèmes où des contraintes locales conflictuelles, imposées par la géométrie du réseau, empêchent l'émergence d'un ordre global simple, menant à des états fondamentaux dégénérés et énergétiques.  
L'analyse démontre que transposer ce concept au vent permet de concevoir des dispositifs qui, au lieu de chercher la portance laminaire comme les éoliennes classiques, exploitent la turbulence, les instabilités aéroélastiques et la rectification fluidique. Trois axes majeurs de « frustration du vent » sont identifiés : (1) La frustration directionnelle via des diodes fluidiques (Valves de Tesla) pour redresser les flux oscillants ; (2) La frustration spatiale via des métamatériaux à gradient d'indice pour concentrer l'énergie cinétique ; et (3) La frustration temporelle via des résonateurs fractals exploitant le galop aéroélastique et la turbulence multi-échelle.  
Ce document détaille les fondements physiques, les preuves expérimentales et les architectures de systèmes potentiels, proposant in fine le concept d'une « Éolienne à Impédance Frustrée » capable de valoriser les gisements éoliens complexes (urbains, turbulents) inaccessibles aux technologies actuelles.

## **1\. Introduction : De l'Ordre Cristallin au Chaos Fluide**

La transition énergétique mondiale impose une diversification des méthodes de captation des énergies renouvelables. L'énergie éolienne, dominée par le paradigme de la turbine à axe horizontal (HAWT), atteint aujourd'hui des limites asymptotiques en termes d'efficacité (limite de Betz) et d'intégration territoriale. Les turbines conventionnelles exigent des flux laminaires, stables et prévisibles ; elles « souffrent » de la turbulence, qui induit fatigue et pertes de rendement.  
La question posée — *est-il possible de frustrer géométriquement le vent?* — suggère un renversement de paradigme. Au lieu de lisser le vent ou de subir sa turbulence, peut-on concevoir des structures géométriques qui contraignent le fluide à des comportements énergétiques exploitables, par analogie avec les systèmes frustrés de la physique fondamentale?

### **1.1 Définition de la Frustration Géométrique**

Le concept de frustration géométrique trouve son origine dans l'étude des matériaux magnétiques antiferromagnétiques. Il survient lorsque l'arrangement spatial des constituants (spins) rend impossible la satisfaction simultanée de toutes les interactions locales de minimisation d'énergie.  
L'exemple canonique est le réseau triangulaire de spins antiferromagnétiques (modèle d'Ising). Si deux spins adjacents s'alignent de manière antiparallèle (état de basse énergie), le troisième spin du triangle ne peut être antiparallèle aux deux premiers simultanément. Il est « frustré ». Cette impossibilité locale a des conséquences macroscopiques profondes :

* **Dégénérescence de l'état fondamental :** Le système ne gèle pas dans un cristal ordonné unique mais fluctue entre une multitude d'états équivalents, même à zéro absolu (entropie résiduelle).  
* **Émergence de structures exotiques :** La frustration favorise l'apparition de phases complexes comme les glaces de spin (spin ices), les liquides de spin quantiques, ou des défauts topologiques stables.

### **1.2 Transposition à la Dynamique des Fluides**

Appliquer la frustration géométrique à un fluide continu comme l'air atmosphérique nécessite une traduction conceptuelle rigoureuse. Dans un fluide, les « spins » peuvent être assimilés aux vecteurs vitesse locaux ou aux structures tourbillonnaires (vorticité).  
Une **« Frustration Aérodynamique »** peut être définie comme l'imposition de conditions aux limites géométriques (parois, obstacles) qui sont mutuellement incompatibles avec un écoulement laminaire direct, forçant le fluide à adopter des trajectoires complexes, tourbillonnaires ou oscillatoires pour conserver sa masse et sa quantité de mouvement.

#### **1.2.1 Analogies dans les Fluides Quantiques et Complexes**

La littérature scientifique récente fournit des précédents où la géométrie dicte le comportement du fluide :

* **Réseaux de Kagomé et Polaritons :** Dans des microcavités optiques structurées en réseau de Kagomé (un motif hautement frustré), des fluides quantiques de lumière (exciton-polaritons) sont forcés de se condenser dans des états de vortex rotatifs pour minimiser l'énergie du système. La frustration géométrique du réseau interdit l'état fondamental sans mouvement, générant spontanément de la vorticité.  
* **Cristaux Liquides Nématiques :** Dans les phases « twist-bend » de cristaux liquides constitués de molécules courbées, la frustration stérique (l'incompatibilité entre la forme des molécules et l'empilement parallèle) force le matériau à adopter une structure hélicoïdale spontanée à l'échelle macroscopique.

Ces exemples prouvent qu'une géométrie statique peut « frustrer » un milieu fluide au point de lui imposer une structuration dynamique (rotation, hélice, vortex) sans apport d'énergie rotative externe. L'enjeu est de transposer ce principe aux échelles macroscopiques du vent atmosphérique.

## **2\. Mécanismes de Frustration Directionnelle : La Diode Fluidique**

Le premier niveau de frustration applicable au vent est la frustration directionnelle : créer une géométrie qui permet l'écoulement dans un sens (état satisfait) mais l'interdit ou le dissipe violemment dans l'autre (état frustré). C'est le principe de la diode fluidique.

### **2.1 La Valve de Tesla : Architecture de la Frustration**

Inventée et brevetée par Nikola Tesla en 1920, la valve de Tesla (ou conduit valvulaire) est un dispositif passif sans aucune pièce mobile. Sa capacité à redresser un flux repose entièrement sur sa topologie interne.

#### **2.1.1 Principes Géométriques et Hydrodynamiques**

La valve est constituée d'une série de boucles et de bifurcations asymétriques.

* **Flux Direct (Forward) :** Le fluide emprunte un chemin central quasi-rectiligne. Les pertes de charge sont dominées par la friction visqueuse classique, qui reste modérée.  
* **Flux Inverse (Reverse \- Frustré) :** Le fluide est géométriquement contraint de se séparer à chaque bifurcation. Une partie du flux est dirigée dans une boucle de retour qui réinjecte le fluide dans le canal principal avec une composante de vitesse opposée au flux incident.  
  * **Mécanisme de Frustration :** Il se crée un conflit cinétique entre le flux principal (qui veut avancer sous l'effet de la pression) et les jets secondaires (qui le repoussent). Ce conflit génère une dissipation turbulente massive et des blocages hydrauliques.

#### **2.1.2 Dépendance au Nombre de Reynolds et Diodicité**

L'efficacité de la frustration, mesurée par la **diodicité** (Di), dépend crucialement du régime d'écoulement.  
pour un même débit Q.  
Les études numériques et expérimentales révèlent un comportement non-linéaire :

* **Bas Reynolds (Re \< 50\) :** Le régime est laminaire. La viscosité domine l'inertie. Le fluide contourne les obstacles en douceur dans les deux sens. Di \\approx 1\. Il n'y a pas de frustration notable.  
* **Haut Reynolds (Re \> 1500\) :** Les forces inertielles dominent. Les jets de retour dans le sens bloquant pénètrent violemment le flux principal. La diodicité augmente rapidement, atteignant des valeurs de 2 à 4 selon les designs.

Pour l'énergie éolienne, où les nombres de Reynolds sont typiquement très élevés (10^5 \- 10^6), la valve de Tesla opère dans sa zone d'efficacité maximale. Elle devient un « mur aérodynamique » sélectif.

### **2.2 Applications Éoliennes : Rectification des Flux Oscillants**

L'intérêt majeur de la frustration directionnelle réside dans l'exploitation des flux alternatifs ou turbulents, typiques des environnements urbains ou des systèmes de colonnes d'eau oscillantes (OWC \- Oscillating Water Columns).

#### **2.2.1 Le Défi de l'Oscillation**

Dans un système OWC (utilisé pour la houle ou les rafales de vent), l'air est compressé puis aspiré. Les turbines classiques (comme la turbine Wells) sont conçues avec des profils symétriques pour tourner dans le même sens quel que soit le flux, mais elles souffrent de décrochages fréquents et d'un rendement médiocre.

#### **2.2.2 Le Pont de Diodes Fluidique**

L'intégration de diodes fluidiques permet de concevoir des systèmes de rectification pneumatique analogues aux ponts de diodes électroniques (Pont de Graetz).

* **Architecture :** Un arrangement de quatre valves de Tesla interconnectées dirige le flux d'entrée (qu'il soit positif ou négatif) vers une turbine interne unidirectionnelle toujours dans le même sens optimal.  
* **Preuves de Concept :** Des études CFD et en soufflerie sur des systèmes jumelés à diodes fluidiques montrent que l'ajout de diodes permet de réduire le flux contre-productif dans la turbine inactive, augmentant l'efficacité moyenne du cycle. Une étude spécifique a montré que l'utilisation de diodes à corps émoussé avec un bypass conique améliore significativement la rectification par rapport aux valves simples.

**Synthèse pour le Design :** Une éolienne basée sur ce principe ne « chasse » pas le vent. Elle est une boîte statique qui « avale » la turbulence et les rafales de toutes directions, les rectifie géométriquement, et alimente une turbine interne protégée et optimisée.

## **3\. Frustration Spatiale : Métamatériaux et Concentration d'Énergie**

Le deuxième niveau de frustration est spatial : manipuler l'espace perçu par le fluide pour le forcer à se concentrer, augmentant artificiellement la densité d'énergie disponible.

### **3.1 Théorie des Métamatériaux Fluides**

Les métamatériaux sont des structures artificielles périodiques dont les propriétés macroscopiques (densité, module de compressibilité) diffèrent de celles de leurs constituants. En acoustique et en électromagnétisme, ils permettent de réaliser des lentilles parfaites ou des capes d'invisibilité (cloaking).  
Appliqué aux fluides (Transformation Fluidics), l'objectif est de contrôler les équations de Navier-Stokes via une transformation de coordonnées. On conçoit des milieux poreux à gradient de perméabilité qui courbent les lignes de courant du fluide.

### **3.2 Le Concentrateur Omnidirectionnel (Wind Lens)**

Contrairement aux carénages classiques (diffuseurs) qui sont encombrants et directionnels, les concentrateurs métamatériaux utilisent des structures sub-longueur d'onde pour manipuler le champ de pression global.

#### **3.2.1 Mécanisme d'Action**

Un concentrateur métamatériau pour le vent fonctionne comme une lentille thermique ou optique. Il est composé d'un réseau de cellules unitaires (souvent des piliers ou des ailettes à gradient) disposées autour du rotor.

* **Compression du Flux :** La structure impose une variation spatiale de la viscosité et de l'inertie effective. Le vent incident, quelle que soit sa direction (omnidirectionnel), est « frustré » dans sa trajectoire rectiligne et converge vers le centre de la structure (la zone de la turbine).  
* **Amplification :** Les simulations montrent une amplification de la densité d'énergie locale jusqu'à **360%** par rapport au flux incident.  
* **Réduction de la Vitesse de Démarrage :** En accélérant le flux avant qu'il n'atteigne le rotor, ces lentilles permettent aux turbines de démarrer à des vitesses de vent très faibles, rendant exploitables des sites auparavant non viables.

### **3.3 Métamatériaux Acoustiques et Piégeage d'Énergie**

Le vent génère également du bruit (énergie acoustique) et des vibrations structurelles. La frustration géométrique permet de récolter cette énergie dissipée.

#### **3.3.1 Cristaux Phononiques et Résonateurs de Helmholtz**

Des métamatériaux acoustiques composés de réseaux périodiques (cristaux phononiques) peuvent créer des bandes interdites fréquentielles.

* **Piégeage de Mode (Defect Mode) :** En introduisant un défaut géométrique (une cavité de taille différente) au sein du réseau périodique, on crée un site où l'énergie acoustique est autorisée à exister mais ne peut pas s'échapper (frustration de propagation). L'énergie s'accumule localement avec une intensité énorme.  
* **Récolte Piézoélectrique :** Placer un transducteur dans cette cavité permet de convertir ce bruit concentré en électricité. Des études montrent des facteurs d'amplification de puissance allant jusqu'à 800 fois par rapport à une exposition directe.  
* **Poutres Métamatériaux à Gradient (Rainbow Trapping) :** Une poutre dotée de résonateurs de tailles graduelles (effet arc-en-ciel) ralentit et arrête les ondes de différentes fréquences à différents endroits physiques de la poutre. Cela permet une récolte d'énergie large bande (multi-fréquentielle), résolvant le problème de la résonance unique des systèmes classiques.

## **4\. Frustration Temporelle et Fractale : Exploiter la Turbulence**

Les éoliennes classiques cherchent la stabilité. La frustration géométrique suggère au contraire de chercher l'instabilité maximale pour extraire l'énergie du chaos turbulent.

### **4.1 La Turbulence de Grille Fractale**

La géométrie fractale (auto-similaire) injecte de la « frustration » à toutes les échelles du fluide.

#### **4.1.1 Non-Équilibre et Intensité Turbulente**

Lorsqu'un flux traverse une grille fractale (par exemple, un motif de carrés répété à différentes échelles), il ne génère pas une turbulence classique qui se dissipe rapidement.

* **Observation :** Les recherches montrent que la turbulence générée possède une zone de production étendue et maintient un état de « non-équilibre » où le taux de dissipation de l'énergie cinétique est anormalement bas.  
* **Conséquence :** Le sillage reste énergétiquement riche et structuré sur une longue distance. Cela crée un volume de fluide où les fluctuations de vitesse sont intenses et corrélées, idéal pour l'excitation de membranes ou de poutres oscillantes.

### **4.2 Récolteurs d'Énergie Fractales (Piezo-Aéroélastique)**

Pour convertir cette turbulence en électricité, la structure réceptrice doit elle-même être « frustrée » temporellement, c'est-à-dire capable de résonner à de multiples fréquences.

#### **4.2.1 Limitations des Poutres Cantilever Simples**

Un récolteur piézoélectrique classique (poutre encastrée) a une fréquence de résonance étroite. Si la turbulence du vent n'est pas à cette fréquence, la récolte est nulle.

#### **4.2.2 L'Apport de la Topologie Fractale**

Des chercheurs ont développé des récolteurs piézoélectriques avec des géométries fractales (courbes de Sierpinski, arbres fractals).

* **Multiplicité des Modes :** La complexité géométrique génère une densité élevée de modes propres de vibration dans les basses fréquences (\< 50 Hz), typiques du vent ambiant.  
* **Performance :** Les expériences montrent que la bande passante efficace des récolteurs fractals de niveau 2 est **2,15 fois plus large** que celle des récolteurs conventionnels. La structure « capture » l'énergie sur un large spectre de turbulence.

### **4.3 Galop et Instabilités de Bluff Bodies Fractals**

Le phénomène de **galop** (galloping) est une instabilité aéroélastique où une structure asymétrique oscille avec une grande amplitude transversalement au vent.

* **Boost Fractal :** L'introduction de formes fractales sur le corps du galop (le "bluff body") modifie la séparation des vortex. Une étude récente démontre que l'utilisation de corps fractals :  
  * Réduit la vitesse critique de démarrage du galop de 0,4 m/s.  
  * Augmente la tension de sortie de **52%**.  
  * Augmente la densité de puissance de **164%** par rapport à un prisme cubique standard.  
  * **Mécanisme :** La géométrie fractale stabilise les tourbillons de sillage et augmente la force aérodynamique instationnaire qui alimente l'oscillation. C'est une exploitation positive de la frustration aérodynamique.

## **5\. Intégration Technologique : Concepts d'Éoliennes Frustrées**

Sur la base de ces principes physiques validés, nous pouvons esquisser des architectures d'éoliennes radicalement nouvelles.

### **5.1 Concept A : La « Turbine à État Solide » (Solid-State Wind Harvester)**

Ce concept vise l'élimination totale des parties rotatives externes.

| Composant | Technologie de Frustration | Fonction |
| :---- | :---- | :---- |
| **Enveloppe** | **Concentrateur Métamatériau** (Lentille omnidirectionnelle) | Capture le vent à 360°, accélère le flux (x3), protège l'intérieur. |
| **Redresseur** | **Réseau de Valves de Tesla** (Pont fluidique) | Transforme la turbulence chaotique et les rafales en un flux unidirectionnel pulsé. |
| **Générateur** | **Turbine Tesla Interne** ou **Résonateurs Fractals** | Convertit le flux accéléré en électricité. La turbine Tesla excelle avec les fluides visqueux/sales ; les résonateurs exploitent les pulsations. |
| **Sortie** | **Diffuseur Fractal** | Mélange le sillage sortant avec l'air ambiant pour réduire la contre-pression (effet de sillage réduit). |

**Applications :** Environnements urbains denses (toits d'immeubles), corridors de vent turbulents, zones où le bruit et les pièces mobiles sont proscrits.

### **5.2 Concept B : Le « Mât Vibrant Actif » (Smart Vortex Harvester)**

Une évolution des technologies type *Vortex Bladeless* intégrant la frustration active.

* **Structure :** Un mât cylindrique vertical flexible.  
* **Frustration Active :** Utilisation de matériaux intelligents (alliages à mémoire de forme ou raidisseurs magnétiques) pour modifier la fréquence propre du mât en temps réel.  
* **Principe :** Maintenir le système dans un état de « Lock-in » permanent. Si le vent change, la géométrie du mât s'adapte pour rester « frustrée » et continuer à osciller.  
* **Add-on Passif :** Ajout de textures de surface fractales ou de contrôleurs de turbulence passifs (SPTC \- Semi-circular Passive Turbulence Control) pour élargir la plage de fonctionnement aérodynamique.

### **5.3 Données Comparatives de Performance**

Le tableau ci-dessous synthétise les gains de performance observés dans la littérature pour ces technologies de frustration par rapport aux références conventionnelles.

| Technologie | Indicateur de Performance | Gain Observé / Valeur | Source |
| :---- | :---- | :---- | :---- |
| **Concentrateur Métamatériau** | Densité d'énergie locale | **\+360%** |  |
| **Récolteur Fractal (Galop)** | Densité de puissance | **\+164%** vs Prisme Cubique |  |
| **Récolteur Fractal (Vibration)** | Bande passante efficace | **x 2.15** vs Poutre Simple |  |
| *Valve de Tesla Optimisée* | Diodicité (Re \> 2000\) | **\> 2.0** (jusqu'à blocage efficace) |  |
| **Cristal Phononique** | Amplification acoustique | **x 800** (Puissance locale) |  |
| **Éolienne Urbaine Passive** | Facteur de capacité (UBL) | **\+66.7%** vs Standard |  |

## **6\. Conclusion et Perspectives**

La recherche confirme sans équivoque qu'il est possible de « frustrer géométriquement le vent » au sens physique du terme : utiliser la topologie et la géométrie pour contraindre l'écoulement dans des états énergétiques non-conventionnels. Ce principe offre une voie de rupture pour l'énergie éolienne.  
Alors que l'ingénierie éolienne classique du XXe siècle s'est focalisée sur l'**efficacité aérodynamique** (finesse, portance, laminarité) pour maximiser le coefficient de puissance (C\_p) dans des conditions idéales, l'ingénierie de la frustration du XXIe siècle se focalise sur la **robustesse entropique**. Elle cherche à extraire de l'énergie de la turbulence, du bruit, des rafales et du chaos directionnel.  
L'**Éolienne à Impédance Frustrée**, combinant lentilles métamatériaux, diodes fluidiques et résonateurs fractals, représente l'aboutissement théorique de cette approche. Bien que ces technologies soient majoritairement à des niveaux de maturité technologique intermédiaires (TRL 3-5), les résultats expérimentaux sur les gains de densité de puissance (+164% à \+360% localement) justifient des efforts de R\&D soutenus. Ces dispositifs ne remplaceront pas les gigantiques fermes offshore, mais ils pourraient déverrouiller le gisement éolien immense et inexploité de la couche limite urbaine et terrestre complexe.

### **Sources Citées dans le Rapport**

* : Physique de la frustration géométrique (Matière condensée, Kagome).  
* : Frustration dans les cristaux liquides.  
* : Valves de Tesla et diodes fluidiques.  
* : Rectification fluidique et OWC.  
* : Métamatériaux, lentilles à vent, transformation optics.  
* : Métamatériaux acoustiques, cristaux phononiques, harvesting piézoélectrique.  
* : Turbulence fractale et grilles.  
* : Récolteurs d'énergie fractals (vibration).  
* : VIV, Galop, Vortex Bladeless, Drapeaux inversés.  
* : Galop fractal et performance augmentée.  
* : Turbulence atmosphérique et éolien urbain.

#### **Ouvrages cités**

1\. Impact of atmospheric turbulence on performance and loads of wind turbines: Knowledge gaps and research challenges \- WES, https://wes.copernicus.org/preprints/wes-2025-42/wes-2025-42.pdf 2\. Researchers measure impact of wind reductions on wind farm energy production, https://news.northeastern.edu/2025/03/20/wind-farm-turbulence-research/ 3\. Geometrical frustration \- Wikipedia, https://en.wikipedia.org/wiki/Geometrical\_frustration 4\. Interacting Ultracold Bosonic Atoms in Geometrically Frustrated Lattices by Tsz Him Leung \- eScholarship, https://escholarship.org/content/qt3tc242vg/qt3tc242vg\_noSplash\_1442d2def5b315931f236af02278eea7.pdf 5\. Perspective: Geometrically frustrated assemblies | The Journal of Chemical Physics | AIP Publishing, https://pubs.aip.org/aip/jcp/article/145/11/110901/807670/Perspective-Geometrically-frustrated-assemblies 6\. Consider the Chemistry of Your Quantum Materials, Say Researchers at Columbia, https://quantum.columbia.edu/news/consider-chemistry-your-quantum-materials-say-researchers-columbia 7\. Controllable vortex lasing arrays in a geometrically frustrated exciton–polariton lattice at room temperature \- Oxford Academic, https://academic.oup.com/nsr/article-pdf/doi/10.1093/nsr/nwac096/49287219/nwac096.pdf 8\. Geometric frustration in twist-bend nematic droplets \- RSC Publishing, https://pubs.rsc.org/en/content/articlehtml/2025/sm/d5sm00530b 9\. Geometric Frustration in Twist-Bend Nematic Droplets \- arXiv, https://arxiv.org/html/2505.16140v1 10\. Tesla turbine \- Wikipedia, https://en.wikipedia.org/wiki/Tesla\_turbine 11\. How the Tesla Turbine Works \- Auto | HowStuffWorks, https://auto.howstuffworks.com/tesla-turbine.htm 12\. Early turbulence and pulsatile flows enhance diodicity of Tesla's macrofluidic valve \- PMC, https://pmc.ncbi.nlm.nih.gov/articles/PMC8128925/ 13\. The Effect of Bifurcated Geometry on the Diodicity of Tesla Valves \- MDPI, https://www.mdpi.com/2311-5521/9/12/294 14\. Experimental Study of Fluidic Diode for Wave Energy Conversion \- J-Stage, https://www.jstage.jst.go.jp/article/jsmepes/2018.23/0/2018.23\_E132/\_article/-char/en 15\. A Twin Unidirectional Impulse Turbine for Wave Energy Conversion—Effect of Fluidic Diode on the Performance \- Scirp.org., https://www.scirp.org/journal/paperinformation?paperid=52852 16\. Design and Optimization of Bio-inspired Fluidic Diode for Wave Energy Harvesting System, https://www.researchgate.net/publication/363839843\_Design\_and\_Optimization\_of\_Bio-inspired\_Fluidic\_Diode\_for\_Wave\_Energy\_Harvesting\_System 17\. A Study on Fluidic Diode for Wave Energy Conversion-Effect of Bypass Geometry on the Turbine Performance \- Scirp.org., https://www.scirp.org/journal/paperinformation?paperid=103103 18\. Effect of Fluidic Diode on Performance of Unidirectional Impulse Turbine \- 热科学学报, https://jts.magtechjournal.com/EN/10.1007/s11630-024-1969-1 19\. Acoustic and mechanical metamaterials for various applications – a brief review \- Frontiers, https://www.frontiersin.org/journals/materials/articles/10.3389/fmats.2025.1626945/full 20\. Design and Processing of Metamaterials \- MDPI, https://www.mdpi.com/2073-4352/15/4/374 21\. The Better to See You With: Scientists Build Record-Setting Metamaterial Flat Lens | NIST, https://www.nist.gov/news-events/news/2013/05/better-see-you-scientists-build-record-setting-metamaterial-flat-lens 22\. New metamaterial lens focuses radio waves | MIT News, https://news.mit.edu/2012/new-metamaterial-lens-focuses-radio-waves-1114 23\. Enhanced wind energy harvesting through omnidirectional airflow metamaterial concentrators | Request PDF \- ResearchGate, https://www.researchgate.net/publication/386424261\_Enhanced\_wind\_energy\_harvesting\_through\_omnidirectional\_airflow\_metamaterial\_concentrators 24\. Enhanced wind energy harvesting through ... \- AIP Publishing, https://pubs.aip.org/aip/pof/article-pdf/doi/10.1063/5.0236158/20281128/121704\_1\_5.0236158.pdf 25\. One-dimensional phononic crystal fiber for energy harvesting application \- ResearchGate, https://www.researchgate.net/publication/389079347\_One-dimensional\_phononic\_crystal\_fiber\_for\_energy\_harvesting\_application 26\. Multi-Band Enhanced Energy Harvesting from Dual Sources Using a ..., https://www.mdpi.com/1424-8220/25/23/7266 27\. Numerical study of fractal-tree-generated non-equilibrium turbulence | Journal of Fluid Mechanics | Cambridge Core, https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/numerical-study-of-fractaltreegenerated-nonequilibrium-turbulence/E57AA491165293D37CB38FCB4C8A5EA2 28\. Dissipation Scaling in Production Region of Fractal Grid Turbulence \- TSFP Conference, http://www.tsfp-conference.org/proceedings/2023/4.pdf 29\. (PDF) Realisation of Fractal Grid-Induced Turbulence Strength with PTFV: Effects of Grid Geometry \- ResearchGate, https://www.researchgate.net/publication/373978850\_Realisation\_of\_Fractal\_Grid-Induced\_Turbulence\_Strength\_with\_PTFV\_Effects\_of\_Grid\_Geometry 30\. Interaction of side-by-side fluidic harvesters in fractal grid-generated turbulence \- SPIE Digital Library, https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10595/105951E/Interaction-of-side-by-side-fluidic-harvesters-in-fractal-grid/10.1117/12.2300664.short 31\. Fractal-inspired multifrequency piezoelectric energy harvesters \- CityUHK Scholars, https://scholars.cityu.edu.hk/en/publications/fractal-inspired-multifrequency-piezoelectric-energy-harvesters/ 32\. Fractal-inspired multifrequency piezoelectric energy harvesters | Request PDF, https://www.researchgate.net/publication/378980390\_Fractal-inspired\_multifrequency\_piezoelectric\_energy\_harvesters 33\. Harvesting Wind Energy Using a Galloping Piezoelectric Beam \- The University of Texas at Austin, https://sites.utexas.edu/sirohi/files/2017/07/018\_sirohi12\_jva.pdf 34\. On the use of fractal geometry to boost galloping-based wind energy harvesting, https://ideas.repec.org/a/eee/energy/v312y2024ics0360544224032808.html 35\. On the use of fractal geometry to boost galloping-based wind energy harvesting \- ePrints Soton \- University of Southampton, https://eprints.soton.ac.uk/498177/ 36\. A Novel Small-Scale Bladeless Wind Turbine Using Vortex-Induced Vibration and a Discrete Resonance-Shifting Module \- MDPI, https://www.mdpi.com/2076-3417/14/18/8217 37\. Enhancing Low-Velocity Wind Energy Harvesting through Semi-Circular Passive Turbulence Controls on Bluff Bodies | SciEn Conference Series: Engineering, https://scienpg.com/scs/index.php/engineering/article/view/scse.2025.3.114 38\. Improving Tesla valve shape within fluid diode plates for building ventilation \- ResearchGate, https://www.researchgate.net/publication/377902102\_Improving\_Tesla\_valve\_shape\_within\_fluid\_diode\_plates\_for\_building\_ventilation 39\. Four geometric parameters of the concentrator and its position in space. \- ResearchGate, https://www.researchgate.net/figure/Four-geometric-parameters-of-the-concentrator-and-its-position-in-space\_fig3\_350519545 40\. New Metamaterial Lens Allows for Lighter, Thinner Solar Panels \- U of T Engineering News \-, https://news.engineering.utoronto.ca/new-metamaterial-lens-allows-lighter-thinner-solar-panels/ 41\. An Investigation of the Energy Harvesting Capabilities of a Novel Three-Dimensional Super-Cell Phononic Crystal with a Local Resonance Structure \- MDPI, https://www.mdpi.com/1424-8220/24/2/361 42\. Acoustic energy harvesting using phononic crystal fiber with conical input \- PubMed Central, https://pmc.ncbi.nlm.nih.gov/articles/PMC11136989/ 43\. Schematics of energy harvesting from acoustic/elastic waves using... \- ResearchGate, https://www.researchgate.net/figure/Schematics-of-energy-harvesting-from-acoustic-elastic-waves-using-various-phononic\_fig1\_387278989 44\. Wideband fractal-inspired piezoelectric energy harvesters \- Sci-Hub, https://www.sci-hub.box/10.1177/14644207211005504 45\. Study of Vortex Induced Vibrations for Harvesting Energy \- IJIRST, http://www.ijirst.org/articles/IJIRSTV2I11074.pdf 46\. A T-shaped piezoelectric cantilever for fluid energy harvesting \- ResearchGate, https://www.researchgate.net/publication/224183920\_A\_T-shaped\_piezoelectric\_cantilever\_for\_fluid\_energy\_harvesting 47\. Wind Energy Harvesting with Vertically Aligned Piezoelectric Inverted Flags \- PMC \- NIH, https://pmc.ncbi.nlm.nih.gov/articles/PMC10747501/ 48\. Passive Variable Geometry | EU Funding & Tenders Portal \- European Commission, https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/opportunities/horizon-results-platform/48340