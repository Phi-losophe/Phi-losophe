# **MANUEL DE CONSTRUCTION DU MODULE KHÉOPS-LICHEN : PROTOTYPE MVP**

## **INTRODUCTION : L'Ingénierie de la Résilience**

Le projet KHÉOPS-LICHEN ne constitue pas simplement un exercice de jardinage sous serre ; il incarne une réponse technique et philosophique aux impératifs de l'autonomie décentralisée. En tant qu'Ingénieur en Chef du projet Lichen, je vous présente ce manuel technique exhaustif, conçu pour guider la fabrication du Module Viable Minimum (MVP). Ce document synthétise des millénaires de géométrie sacrée, incarnée par la Grande Pyramide de Gizeh, avec les avancées contemporaines en biotechnologie algale et en thermodynamique passive.

L'objectif est de créer une "machine vivante" autonome. La structure pyramidale, orientée selon un angle précis de 51,84°, n'est pas un choix esthétique mais un impératif d'ingénierie pour l'optimisation solaire et la gestion des flux thermiques. Le terme "Lichen" fait référence à la symbiose fondamentale du système : une peau photovoltaïque (l'algue photobionte fournissant l'énergie) protégeant et alimentant un cœur bioréacteur (le champignon mycobionte fournissant la structure et l'humidité).

Ce manuel adopte une approche "Solarpunk" pragmatique : nous privilégions le low-tech réparable, le détournement de matériaux (upcycling) et l'intelligence systémique plutôt que la force brute technologique. Chaque vis, chaque ligne de code et chaque litre de culture de spiruline a été pensé pour maximiser l'entropie négative du système, créant de l'ordre et de la ressource (nourriture, eau, énergie) à partir du chaos ambiant.

## ---

**CHAPITRE 1 : NOMENCLATURE ET ANALYSE DES COÛTS (BILL OF MATERIALS)**

La réussite de l'assemblage du module Khéops-Lichen repose sur une préparation logistique rigoureuse. La stratégie d'approvisionnement suit une hiérarchie stricte de durabilité : Récupération \> Réemploi \> Achat Neuf. Cette approche réduit l'énergie grise incorporée dans la structure avant même sa mise en service.

Le budget estimatif pour ce prototype varie considérablement selon votre capacité à sourcer des matériaux de récupération. Les fourchettes de prix indiquées ci-dessous reflètent le marché actuel pour des composants neufs versus des solutions "système D".

### **1.1. L'OSSATURE (Structure et Mécanique)**

La structure doit résister aux charges de vent, supporter le poids du système hydrique et maintenir des angles précis pour l'efficacité de la peau solaire.

| Composant | Quantité | Spécifications Techniques | Notes d'Approvisionnement / Alternative | Est. Coût (USD) |
| :---- | :---- | :---- | :---- | :---- |
| **Montants Principaux** | 4 | Bois traité ou Cèdre, section 2x4 (38x89mm), longueur 3m | Bois de charpente FSC ou récupération de terrasses. Le bois composite est déconseillé pour la rigidité. | $20 \- $50 |
| **Solives de Base** | 4 | Bois traité, section 2x6 (38x140mm), longueur 2.5m | Planches d'échafaudage ou bois de coffrage nettoyé. | $30 \- $60 |
| **Connecteur Apex** | 1 | Impression 3D (PETG/ASA) ou Acier Soudé | Impression interne (Infill 100%, 6 parois). Ne jamais utiliser de PLA (déformation thermique). | $15 (Filament) |
| **Connecteurs d'Angle** | 4 | Impression 3D (PETG) ou Équerres Acier modifiées | Conception paramétrique pour l'angle 51.8°. | $10 |
| **Visserie Structurelle** | 1 Boîte | Vis terrasse 3" (76mm), Inox A2 ou A4 | L'inox est impératif pour éviter la corrosion due à l'humidité du bioréacteur. | $15 |
| **Actionneur Linéaire** | 1 | 12V DC, Course 100mm-150mm, Force 750N-1000N | Récupération sur vérins de lit médicalisé ou positionneurs de paraboles satellites.1 | $30 \- $50 |
| **Charnières Ventil.** | 2 | Charnières inox ou piano | Récupération quincaillerie marine. | $10 |

### **1.2. LA PEAU SOLAIRE (Énergie et Ombrage)**

Cette couche assure la production électrique et la régulation thermique du bioréacteur. Le choix entre panneaux flexibles et cellules Grätzel dépendra de votre volonté d'efficacité (Panneaux) ou d'expérimentation pédagogique (Grätzel).

| Composant | Quantité | Spécifications Techniques | Notes d'Approvisionnement / Alternative | Est. Coût (USD) |
| :---- | :---- | :---- | :---- | :---- |
| **Panneaux PV Flexibles** | 4 | 100W Monocristallin, revêtement ETFE | Privilégier l'ETFE au PET pour la durabilité UV.2 | $400 \- $600 |
| **Kit Cellules Grätzel** | 1 (Test) | Poudre TiO2, Verre conducteur FTO, Graphite, Jus de fruits rouges | Fournisseurs labo chimie ou synthèse maison (complexe mais faisable).3 | $150 (Expérimental) |
| **Système de Fixation** | 1 Rouleau | Ruban VHB 3M ou Œillets \+ Tendeurs | Le ruban VHB assure une fixation sans perçage, crucial pour l'étanchéité. | $20 |
| **Contrôleur de Charge** | 1 | MPPT 20A (Victron ou EPEVER) | Le MPPT est essentiel pour maximiser le rendement lors des variations d'ombrage. | $100 |
| **Stockage Batterie** | 1 | 12V 100Ah LiFePO4 ou AGM Deep Cycle | Batteries de secours onduleurs (UPS) ou Solaire dédié. LiFePO4 recommandé pour la longévité. | $300 \- $500 |

### **1.3. LE SYSTÈME HYDRIQUE (Récolte et Condensation)**

Un système passif exploitant le refroidissement radiatif nocturne et la tension superficielle.

| Composant | Quantité | Spécifications Techniques | Notes d'Approvisionnement / Alternative | Est. Coût (USD) |
| :---- | :---- | :---- | :---- | :---- |
| **Surface Condensation** | 4 Feuilles | Polycarbonate alvéolaire 4mm (Twin-Wall) | Matériau standard de serre. Découpe facile au cutter.4 | $120 \- $200 |
| **Peinture Radiative** | 1 Litre | Base Acrylique \+ Sulfate de Baryum (BaSO4) | Mélange DIY pour émissivité IR élevée (Refroidissement passif).5 | $30 |
| **Gouttières Internes** | 4 | Profilé U en PVC ou Aluminium | Profilés pour cloisons sèches ou tuyaux PVC fendus.6 | $10 |
| **Réservoir Collecte** | 1 | Fût alimentaire 50L \- 100L | Fûts d'olives ou de produits laitiers recyclés (HDPE). | $0 \- $20 |
| **Filtration** | 1 | Filtre bio-sable \+ Charbon Actif | DIY : Gravier, Sable grossier, Sable fin, Charbon de bois broyé. | $10 |
| **Cône Filet (Warka)** | 2 m² | Filet hydrophile (Nylon ou Polyprop.) | Filet anti-insectes ou tissu spacer 3D.7 | $15 |

### **1.4. LE POUMON VERT (Bioréacteur Spiruline)**

Le cœur biologique du système.

| Composant | Quantité | Spécifications Techniques | Notes d'Approvisionnement / Alternative | Est. Coût (USD) |
| :---- | :---- | :---- | :---- | :---- |
| **Cuve Réacteur** | 1 | Tube Acrylique ou Bonbonne Eau 18L (Polycarbonate) | Bouteilles de fontaines à eau recyclées (transparentes). | $0 \- $50 |
| **Pompe à Air** | 1 | Pompe Aquarium 5W \- 10W (Silent) | Récupération aquariophilie. Débit \> 200L/h.8 | $15 |
| **Nutriments** | Divers | Urine (Azote), Clous Rouillés (Fer), Cendres (Potasse) | Flux de déchets ménagers (Gratuit). | $0 |
| **Souche Spiruline** | 500ml | *Arthrospira platensis* vivante | Laboratoire d'algologie ou don entre cultivateurs.9 | $20 |
| **Chauffage (Option)** | 1 | Thermoplongeur Aquarium 50W | Nécessaire si T° nocturne \< 15°C. | $15 |

### **1.5. LE CERVEAU (Automation et Contrôle)**

Le système nerveux central pour la gestion autonome.

| Composant | Quantité | Spécifications Techniques | Notes d'Approvisionnement / Alternative | Est. Coût (USD) |
| :---- | :---- | :---- | :---- | :---- |
| **Microcontrôleur** | 1 | ESP32 (WROOM-32) ou Arduino Uno R4 WiFi | ESP32 préféré pour connectivité native et faible conso.10 | $8 \- $25 |
| **Capteurs Air** | 1 | DHT22 (Temp/Hum) ou BME280 | BME280 est plus précis sur l'humidité.11 | $5 \- $10 |
| **Sonde Liquide** | 1 | DS18B20 (Étanche) | Pour la température du milieu de culture. | $5 |
| **Module Relais** | 1 | 4-Channel 5V Relay Module | Isolation optocoupleur recommandée.12 | $5 |
| **Boîtier** | 1 | Boîtier de dérivation IP65 | Quincaillerie électrique standard. | $15 |
| **Alimentation** | 1 | Convertisseur DC-DC Buck (12V vers 5V) | LM2596 ou similaire pour alimenter l'ESP32 via la batterie. | $3 |

**Coût Total Estimatif (MVP) :** Entre **$1,100 et $1,700**. Ce coût peut être drastiquement réduit (vers $600-$800) par une récupération agressive des matériaux structurels et des batteries.

## ---

**CHAPITRE 2 : PHASE 1 \- L'OSSATURE (GÉOMÉTRIE ET ASSEMBLAGE)**

La pyramide Khéops-Lichen tire sa stabilité et ses propriétés thermiques de sa géométrie précise. Contrairement à une serre tunnel classique, la forme pyramidale favorise la stratification thermique (l'air chaud monte vers l'apex pour être évacué) et offre une prise au vent minimale quelle que soit la direction des rafales.

### **2.1. Théorie Géométrique et Angle Sacré**

L'angle de pente (![][image1]) de la structure est dicté par les proportions de la Grande Pyramide. Cette géométrie n'est pas choisie par mysticisme, mais pour ses propriétés géométriques uniques : elle incarne le "nombre d'or" dans sa projection triangulaire.

Pour la pyramide de Khéops originale :

* Hauteur (![][image2]) \= 280 coudées.  
* Base (![][image3]) \= 440 coudées (donc demi-base ![][image4]).

Le calcul de la pente latérale se fait par la tangente 13 :

![][image5]  
![][image6]  
Cet angle de **51,8°** est critique. Sous des latitudes tempérées (40°-50° N), il présente une face presque perpendiculaire aux rayons solaires lors des équinoxes, maximisant la capture passive d'énergie tout en permettant un ruissellement efficace de la condensation et de la neige sur le polycarbonate, évitant la stagnation d'eau nuisible aux joints.

### **2.2. Préparation et Coupe des Bois (Charpenterie)**

La construction d'une pyramide à base carrée requiert des coupes composées ("compound miters") complexes si l'on souhaite joindre les bois bord à bord. C'est souvent le point d'échec des projets DIY. Pour le module Lichen, nous simplifions cela par l'usage de connecteurs, mais il est crucial de comprendre la coupe des montants.

**Paramètres pour une Base de 2,5m :**

* **Longueur de Base (![][image7]) :** 2500 mm.  
* **Hauteur Apex (![][image2]) :** ![][image8] mm.  
* **Longueur d'Arête (Montant d'angle) :** ![][image9] mm.

Instructions de Coupe sur Scie à Onglet Radiale 14 : Si vous n'utilisez pas de connecteurs 3D et souhaitez assembler le bois directement :

1. **Réglage de l'Onglet (Miter \- Plateau tournant) :** Pour une pyramide à 4 côtés de cette pente, l'angle d'onglet est d'environ **41,0°**.  
2. **Réglage du Biseau (Bevel \- Inclinaison lame) :** L'inclinaison de la lame doit être réglée à environ **21,0°**.

*Approche Pragmatique Lichen :* Pour ce MVP, nous recommandons de couper les extrémités des montants 2x4 à **coupe droite** ou avec un simple biseau de 51,8° pour s'insérer dans les connecteurs imprimés en 3D. Cela annule la complexité des coupes composées et garantit la symétrie via la précision de l'impression 3D.

### **2.3. Les Connecteurs Biomimétiques (Impression 3D)**

L'usage de l'impression 3D permet de créer des "nœuds" structurels complexes impossibles à réaliser en menuiserie amateur.

**Connecteur Apex (Le Sommet) :**

* **Conception :** Un moyeu central comportant quatre manchons femelles orientés vers le bas à 51,8° par rapport à l'horizontale.  
* **Cheminée Centrale :** Le design intègre un cylindre creux vertical de 100mm de diamètre. Ce "puits" sert de cheminée thermique pour l'évacuation de l'air chaud et de support pour l'actionneur linéaire.  
* **Matériau :** **ASA (Acrylonitrile Styrene Acrylate)** ou **PETG**. L'ABS est acceptable mais sujet au délaminage (warping). **Interdiction formelle du PLA** : sous le soleil d'été, la température à l'apex dépassera 50°C, température de transition vitreuse du PLA, entraînant l'effondrement de la structure.16  
* **Paramètres d'impression :** Infill 60% à 100% (Motif Gyroïde), 6 périmètres de paroi (walls), hauteur de couche 0.2mm.

**Connecteurs d'Angle (La Base) :**

* **Fonction :** Ancrer le montant oblique à la solive de base horizontale.  
* **Drainage :** Le design doit inclure des canaux d'évacuation à la base du manchon. Sans cela, l'eau de condensation ruisselant le long du montant s'accumulera dans le connecteur, faisant pourrir le bois en quelques mois.  
* **Fixation :** Prévoir des trous pour tirefonds traversants vers le sol (ancrage vent).

### **2.4. Séquence d'Assemblage**

1. **Préparation du Site :**  
   * Nivelez le sol. Décaissez sur 10cm et remplissez de gravier pour le drainage sous le bioréacteur.  
   * Posez les 4 solives de base (2x6) pour former le carré de 2,5m. Vérifiez l'équerrage en mesurant les diagonales : elles doivent être strictement égales (![][image10] mm).  
2. **Montage au Sol (Pré-assemblage) :**  
   * Insérez les extrémités supérieures des 4 montants dans le Connecteur Apex *tant que la structure est à plat*. Il est impossible d'insérer le dernier montant une fois les trois autres fixés au sol sous tension.  
3. **Élévation (L'Opération Délicate) :**  
   * Nécessite 3 personnes.  
   * Soulevez l'ensemble par l'apex. Les montants vont s'écarter naturellement.  
   * Guidez les pieds des montants dans les Connecteurs d'Angle fixés aux coins du cadre de base.  
   * *Astuce de l'Ingénieur :* Ne vissez pas immédiatement à fond. Laissez du jeu pour ajuster la verticalité.  
4. **Validation Structurelle :**  
   * Suspendez un fil à plomb depuis le centre exact du connecteur Apex. La pointe doit tomber précisément au centre géométrique du carré de base.  
   * Une fois centré, vissez définitivement les montants dans les connecteurs (vis traversantes).

### **2.5. Le Mécanisme d'Ouverture Automatique (Le Chapeau)**

L'apex est le point le plus chaud. Pour réguler la température sans électricité excessive, nous créons un "chapeau" pyramidal mobile.

Mécanique de l'Actionneur 1 :

1. **Support :** Fabriquez une traverse en acier (cornière) fixée à mi-hauteur sur deux montants opposés, près du sommet.  
2. **Montage Vérin :** Fixez la base de l'actionneur linéaire (12V) sur cette traverse, tige vers le haut, passant au travers de la cheminée du connecteur Apex.  
3. **Le Capot :** Construisez une mini-pyramide en polycarbonate (base 40cm). Fixez-la à la tête du vérin.  
4. **Guidage :** Le capot doit pouvoir monter et descendre sans tourner. Si le vérin a une tige rotative, ajoutez des tiges guides verticales.

*Note de sécurité :* Utilisez impérativement un actionneur avec **fins de course intégrées** (limit switches). Sans cela, le moteur forcera en butée et grillera ou cassera le connecteur plastique.

## ---

**CHAPITRE 3 : PHASE 2 \- LA PEAU SOLAIRE (ÉNERGIE ET PHOTOVOLTAÏQUE)**

La peau du module assure deux fonctions vitales : la production d'énergie pour l'autonomie (pompes, électronique) et l'ombrage sélectif pour le bioréacteur. La spiruline nécessite de la lumière pour la photosynthèse, mais un soleil direct de midi peut provoquer une photo-inhibition et tuer la culture.

### **3.1. Analyse Comparative : Flexible vs Grätzel**

Pour ce MVP, nous devons trancher entre l'efficacité industrielle et l'approche "Bio-Maker".

* **Option A : Panneaux Flexibles (L'approche Pragmatique).** Rendement \~20%. Robustes, faciles à monter. Ils fournissent la puissance critique.  
* **Option B : Cellules à Colorant de Grätzel (L'approche Low-Tech/Pédagogique).** Rendement \~4%. Translucides, fabriquées avec du jus de fruit et du dentifrice (TiO2). Elles sont magnifiques (vitrail violet) mais instables dans le temps (l'électrolyte liquide s'évapore ou fuit).

**Décision Ingénieur :** Nous utiliserons des **panneaux flexibles pour le bus principal d'alimentation** (Face Sud) et intégrerons une **fenêtre test de cellules Grätzel** (Face Est) pour la démonstration et le spectre lumineux spécifique.

### **3.2. Installation des Panneaux Flexibles et Gestion Thermique**

Les panneaux flexibles (souvent utilisés en nautisme ou camping-car) ont un talon d'Achille : la chaleur. Collés directement sur un support isolant (polycarbonate ou bois), ils ne peuvent dissiper leur chaleur, ce qui dégrade les cellules et réduit le rendement.2

**Protocole de Montage Ventilée :**

1. **L'Erreur à Éviter :** Ne jamais coller le panneau directement sur le polycarbonate de la serre. La chaleur du panneau cuirait le plastique et augmenterait la température interne de la serre.  
2. **La Solution "Air Gap" :**  
   * Installez des **entretoises** de 20mm sur les montants de la pyramide.  
   * Fixez un treillis rigide ou des lattes horizontales sur ces entretoises.  
   * Montez les panneaux flexibles sur ce support secondaire.  
   * *Résultat :* L'air circule *sous* le panneau, le refroidissant par convection (effet cheminée le long de la pente), améliorant son rendement et préservant le polycarbonate en dessous.

**Câblage 12V (Série-Parallèle) :**

Pour 4 panneaux de 100W (Vmp \~18V) :

* Connectez deux paires en série (2S) pour doubler la tension (\~36V). Cela réduit les pertes résistives dans les câbles vers le contrôleur.  
* Connectez ces deux paires en parallèle (2P) pour additionner l'ampérage.  
* Utilisez des connecteurs étanches MC4.  
* *Entrée de câble :* Percez le connecteur Apex ou utilisez un presse-étoupe sur le flanc haut. Ne percez jamais le panneau lui-même.

### **3.3. Fabrication des Cellules Grätzel (Protocole DIY)**

3  
Pour la fenêtre de démonstration "Solarpunk", voici la recette bio-chimique :

1. **Préparation de l'Anode (TiO2) :**  
   * Mélangez de la poudre de dioxyde de titane (TiO2 \- pigment blanc standard) avec un peu de vinaigre et de détergent pour créer une pâte fluide.  
   * Étalez cette pâte en couche microscopique (méthode "Doctor Blade") sur la face conductrice d'un verre FTO (Fluorine-doped Tin Oxide).  
   * **Cuisson (Sintérisation) :** Chauffez à 450°C pendant 30 min. Cela crée une structure poreuse nanocristalline.  
2. **Sensibilisation (Le Colorant) :**  
   * Préparez un jus concentré de mûres, framboises ou hibiscus (riche en anthocyanes).  
   * Trempez la plaque de TiO2 refroidie dans ce jus pendant 10-15 minutes. Le film blanc devient violet foncé : il est maintenant capable d'absorber les photons.19  
3. **La Cathode et l'Assemblage :**  
   * Sur une seconde plaque FTO, frottez une mine de crayon graphite (carbone) pour créer le catalyseur.  
   * Assemblez les deux plaques (face TiO2 contre face Carbone) avec un décalage pour les contacts électriques.  
   * Injectez une goutte d'électrolyte iodure/triiodure (solution de Lugol possible en low-tech) par capillarité entre les plaques.  
4. **Résultat :** Une cellule qui produit environ 0.5V sous le soleil. Mettez-en 24 en série pour charger une petite batterie tampon.

## ---

**CHAPITRE 4 : PHASE 3 \- LE SYSTÈME HYDRIQUE (EAU ATMOSPHÉRIQUE)**

L'autonomie en eau est le défi majeur. Le module Khéops-Lichen combine la récolte active (pluie) et passive (rosée/brouillard).

### **4.1. Physique du Refroidissement Radiatif**

La condensation de rosée se produit lorsque la température d'une surface descend sous le point de rosée de l'air ambiant. Pour forcer ce phénomène sans électricité, nous exploitons le refroidissement radiatif : la capacité d'un matériau à émettre sa chaleur sous forme de rayonnement infrarouge vers l'espace froid.

**La Fenêtre Atmosphérique (Sky Window) :** L'atmosphère terrestre est transparente aux longueurs d'onde infrarouges entre 8 et 13 μm. Une surface émettant fortement dans cette plage peut descendre de 5°C à 10°C *en dessous* de la température ambiante nocturne.5

Recette Peinture Radiative DIY 21 : Pour les faces Nord (à l'ombre) de la pyramide :

1. **Pigment :** Sulfate de Baryum (BaSO4) ou Carbonate de Calcium (CaCO3). Le BaSO4 est supérieur pour la réflectance UV.  
2. **Granulométrie :** Mélangez différentes tailles de particules (si possible) pour maximiser la densité optique.  
3. **Liant :** Vernis acrylique transparent ou solution polymère.  
4. **Application :** Peignez les panneaux de polycarbonate (ou feuilles métalliques) sur la face Nord. Cette surface deviendra un "aimant à rosée" la nuit.

### **4.2. Le Cône de Condensation (Inspiré de Warka Water)**

À l'intérieur de l'apex, là où l'air chaud et humide monte durant la journée, nous installons un capteur inspiré des tours Warka éthiopiennes.7

* **Construction :** Un cône en filet maillé (type moustiquaire nylon ou tissu 3D spacer) suspendu sous l'ouverture du chapeau.  
* **Fonctionnement :**  
  1. L'air humide monte par effet cheminée.  
  2. Il traverse le maillage qui offre une grande surface de contact.  
  3. La nuit, l'air extérieur froid entrant par le clapet ouvert refroidit ce maillage.  
  4. L'humidité condense en gouttelettes qui ruissellent par gravité vers la pointe du cône.  
* **Collecte :** Un entonnoir sous le cône dirige l'eau vers le réservoir central.

### **4.3. Gestion des Condensats Internes et Gouttières**

Dans une serre fermée, les plantes transpirent. Cette eau condense sur les parois froides (polycarbonate).

* **Problème :** Le polycarbonate est hydrophobe ; l'eau forme des gouttes qui tombent sur les plantes (risque fongique) au lieu de glisser.  
* **Solution Low-Tech :** Traitez la face *intérieure* du polycarbonate avec un agent tensioactif (spray anti-buée ou solution très diluée de savon liquide). Cela force la "condensation en film".23  
* Gouttières 6 : Installez un profilé en U à la base intérieure des parois, juste au-dessus des solives de bois. Ne scellez pas le bas du polycarbonate hermétiquement contre le bois ; laissez un espace de 5mm pour que le film d'eau tombe dans le profilé U, qui redirige l'eau vers le réservoir.

### **4.4. Filtration Biologique**

L'eau de toit contient des fientes et poussières.

1. **First Flush (Premier flux) :** Un simple tube vertical avec une balle flottante qui capture les premiers litres de pluie sale avant de dévier l'eau propre vers le réservoir.  
2. **Filtre Bio-Sable :** Un seau de 20L rempli de couches successives (Gravier \> Sable grossier \> Sable fin). Un biofilm biologique (*schmutzdecke*) se forme en surface et digère les pathogènes.  
3. **Charbon Actif :** Une couche finale de charbon de bois (activé maison par choc thermique) adsorbe les contaminants chimiques.

## ---

**CHAPITRE 5 : PHASE 4 \- LE POUMON VERT (BIORÉACTEUR SPIRULINE)**

La spiruline (*Arthrospira platensis*) n'est pas une simple algue, c'est une cyanobactérie extrêmophile. Elle prospère là où d'autres meurent : milieu très alcalin (pH 10), chaud (35°C). Cela la protège naturellement des contaminations.

### **5.1. Le Vaisseau (Photobioréacteur)**

Pour le MVP, nous utilisons la technique de la colonne d'eau ("Airlift Column").

* **Récipient :** Une bonbonne d'eau de fontaine (18.9L) en polycarbonate transparent est idéale pour débuter. Elle est robuste, transparente et de qualité alimentaire.  
* **Emplacement :** Placez-la au centre de la pyramide pour bénéficier de la lumière diffuse, ou côté Sud avec un ombrage partiel. La spiruline a besoin de lumière mais craint les UV directs intenses.

### **5.2. Physique de la Pompe Airlift**

24  
Les pompes centrifuges classiques (à hélice) tuent la spiruline en brisant ses filaments spirales (stress de cisaillement). La pompe Airlift utilise des bulles d'air pour mouvoir l'eau doucement.

**Montage :**

1. **Tube Riser :** Insérez un tube PVC de 25mm de diamètre à l'intérieur de la bonbonne, allant du fond jusqu'à 5cm sous la surface.  
2. **Injection d'Air :** Insérez le tuyau d'air (6mm) provenant de la pompe aquarium *à l'intérieur* du tube PVC, jusqu'en bas.  
3. **Principe :** Les bulles injectées dans le tube réduisent la densité de la colonne d'eau à l'intérieur du tube par rapport à l'eau de la bonbonne. L'eau "lourde" extérieure pousse l'eau "légère" vers le haut du tube, créant une circulation continue.  
4. **Avantage :** Ce brassage est doux et assure que chaque filament d'algue passe tour à tour à la lumière et à l'ombre (cycle lumière/obscurité), essentiel pour la croissance.

### **5.3. Recette du Milieu de Culture "Pee-Ponics" (Urine \+ Fer)**

26  
L'approche solarpunk refuse les intrants chimiques industriels (NPK). Nous bouclons le cycle des nutriments.

**Recette pour 100 Litres de Milieu :**

1. **La Base Alcaline (L'Habitat) :**  
   * Eau (de pluie filtrée ou déchlorée) : 100 L.  
   * Bicarbonate de Soude (NaHCO3) : **1 kg**. Cela tamponne le pH autour de 9-10.  
   * Sel Marin (Sel de Guérande) : **500 g**. Apporte les oligo-éléments.  
2. **La Nourriture Azotée (Urine) :**  
   * Source : Urine humaine fraîche (donneur sain, sans médicaments/contraceptifs).  
   * Dosage : **1 Litre d'urine pour 100 Litres de culture**.  
   * Traitement : Idéalement, stockez l'urine avec un peu de vinaigre blanc (10cl/L) pour stabiliser l'ammoniac et stériliser. L'urine apporte l'Azote (Urée), le Phosphore et le Potassium.  
3. **Le Complément Ferreux (Jus de Clous) :**  
   * La spiruline a besoin de fer pour la photosynthèse (chlorophylle). L'urine en manque.  
   * **Préparation (10 jours avant) :** Mettez **100g de clous rouillés** dans 1L de vinaigre blanc \+ jus de 5 citrons (acide citrique chélateur). Laissez réagir 10 jours. Le liquide devient brun foncé (acétate/citrate de fer).  
   * Dosage : **200 ml de "Jus de Clous" pour 100 Litres de culture**.

### **5.4. Ensemencement et Récolte**

1. **Démarrage :** Versez votre souche (500ml) dans le milieu préparé.  
2. **Croissance :** Attendez que la couleur passe du vert clair au vert forêt profond. Utilisez un Disque de Secchi (disque blanc au bout d'une règle). Si le disque disparaît à moins de 3cm de profondeur, il est temps de récolter.  
3. **Récolte :** Filtrez 10-20% du volume de la bonbonne à travers un tissu à mailles fines (30-50 microns, toile de sérigraphie). Vous obtiendrez une pâte verte ("fromage frais" de spiruline).  
4. **Retour :** Reversez le filtrat (l'eau claire) dans la bonbonne. Ajoutez un peu de mix Urine/Fer pour compenser la perte de nutriments.

## ---

**CHAPITRE 6 : LE CERVEAU (AUTOMATION ESP32)**

L'intelligence du module Khéops-Lichen réside dans sa capacité à réagir aux extrêmes climatiques sans intervention humaine.

### **6.1. Architecture Matérielle**

* **Contrôleur :** **ESP32** est choisi pour sa connectivité Wi-Fi/Bluetooth (monitoring à distance) et ses doubles cœurs.  
* **Alimentation :** L'ESP32 fonctionne en 3.3V, mais les modules relais nécessitent souvent 5V. Utilisez un convertisseur Buck (ex: LM2596) pour abaisser le 12V de la batterie vers 5V stable pour alimenter l'ESP32 (via pin VIN) et les relais.

### **6.2. Logique de Contrôle et Hystérésis**

27  
Pour piloter l'ouverture du toit (Vérin), il ne suffit pas d'une simple condition if (temp \> 30). Cela ferait osciller le moteur indéfiniment si la température est de 30.01°C puis 29.99°C. Il faut utiliser l'**Hystérésis**.

**Algorithme (Pseudo-Code C++) :**

C++

// Définition des seuils avec Hystérésis  
const float TEMP\_OUVERTURE \= 32.0; // Ouvre si trop chaud  
const float TEMP\_FERMETURE \= 26.0; // Ferme si redescendu à niveau acceptable

void loop() {  
  float temp \= dht.readTemperature();  
    
  // Logique Ventilation  
  if (temp \>= TEMP\_OUVERTURE &&\!estOuvert) {  
    OuvrirVerin(); // Active le relais Moteur Montée  
    estOuvert \= true;  
  }  
  else if (temp \<= TEMP\_FERMETURE && estOuvert) {  
    FermerVerin(); // Active le relais Moteur Descente (inversion polarité)  
    estOuvert \= false;  
  }  
    
  // Logique Chauffage Spiruline (Protection Froid)  
  float tempEau \= sensors.getTempCByIndex(0);  
  if (tempEau \< 18.0) {  
    DigitalWrite(RELAIS\_CHAUFFAGE, HIGH);  
  } else if (tempEau \> 20.0) {  
    DigitalWrite(RELAIS\_CHAUFFAGE, LOW);  
  }  
    
  // Deep Sleep pour économie énergie (10 min)  
  // ESP.deepSleep(600e6);   
}

### **6.3. Câblage et Sécurité**

1. **Pont en H (Inversion Moteur) :** L'actionneur linéaire a deux fils. Pour inverser le sens (monter/descendre), il faut inverser la polarité. Utilisez un module **Pont en H (L298N)** ou un montage à 2 relais SPDT pour gérer cela via l'ESP32.  
2. **Isolation :** Les pompes et moteurs génèrent du bruit électrique. Utilisez des relais optocouplés pour protéger l'ESP32.  
3. **Data Logging :** Les données (Temp air, Temp eau, Humidité) sont envoyées via MQTT ou enregistrées sur carte SD. L'analyse de ces données permet de comprendre l'inertie thermique de la pyramide (combien de temps la masse d'eau garde la chaleur la nuit).

## ---

**CONCLUSION ET PERSPECTIVES**

Le prototype KHÉOPS-LICHEN que vous allez construire est un démonstrateur de résilience. En intégrant la géométrie passive, la conversion solaire, la collecte d'eau atmosphérique et la production de protéines, il boucle les cycles essentiels à la vie.

Ce manuel décrit la version 1.0. Les itérations futures pourraient inclure :

* L'intégration de mycélium dans les parois pour l'isolation (Bio-composites).  
* L'usage de pompes piézoélectriques alimentées par la vibration du vent.  
* La connexion en essaim de plusieurs pyramides partageant leurs ressources (eau/énergie).

Ingénieur, à vos outils. Construisez, mesurez, itérez.

---

**Citations Intégrées :** .1

#### **Sources des citations**

1. Building a Greenhouse Vent Opener (with Pictures) \- Instructables, consulté le janvier 13, 2026, [https://www.instructables.com/Building-a-Greenhouse-Vent-Opener/](https://www.instructables.com/Building-a-Greenhouse-Vent-Opener/)  
2. The Pros and Cons of Flexible Solar Panels vs. Rigid, consulté le janvier 13, 2026, [https://battlebornbatteries.com/flexible-solar-panels-vs-rigid/](https://battlebornbatteries.com/flexible-solar-panels-vs-rigid/)  
3. Dye-sensitized solar cell \- Wikipedia, consulté le janvier 13, 2026, [https://en.wikipedia.org/wiki/Dye-sensitized\_solar\_cell](https://en.wikipedia.org/wiki/Dye-sensitized_solar_cell)  
4. 4mm Twin-Wall Polycarbonate Sheet \- 4' x 8' Sheet \- TekSupply, consulté le janvier 13, 2026, [https://www.teksupply.com/prod/104617.html](https://www.teksupply.com/prod/104617.html)  
5. ENERGY-FREE DEW HARVESTING ENABLED BY EMERGING RADIATIVE COOLING PAINTS \- Purdue University Graduate School, consulté le janvier 13, 2026, [https://hammer.purdue.edu/articles/thesis/\_b\_ENERGY-FREE\_DEW\_HARVESTING\_ENABLED\_BY\_EMERGING\_RADIATIVE\_COOLING\_PAINTS\_b\_/30826406](https://hammer.purdue.edu/articles/thesis/_b_ENERGY-FREE_DEW_HARVESTING_ENABLED_BY_EMERGING_RADIATIVE_COOLING_PAINTS_b_/30826406)  
6. Turn Your Greenhouse Into a Water-Saving Powerhouse: DIY Collection System That Actually Works \- Clear Pond, consulté le janvier 13, 2026, [https://clearpond.com.au/community-and-social-engagement/turn-your-greenhouse-into-a-water-saving-powerhouse-diy-collection-system-that-actually-works/](https://clearpond.com.au/community-and-social-engagement/turn-your-greenhouse-into-a-water-saving-powerhouse-diy-collection-system-that-actually-works/)  
7. Warka Tower from Warka Water uses a mesh net to collect water from humid air. \- Phoenix Zoo, consulté le janvier 13, 2026, [https://www.phoenixzoo.org/wp-content/uploads/2023/03/Lightweight-Water-Collection-System-Inspired-by-Darkling-Beetles-%E2%80%94-Innovation-%E2%80%94-AskNature.pdf](https://www.phoenixzoo.org/wp-content/uploads/2023/03/Lightweight-Water-Collection-System-Inspired-by-Darkling-Beetles-%E2%80%94-Innovation-%E2%80%94-AskNature.pdf)  
8. Aeration Pumps |The Pond Outlet Pond Supplies Pond Aerators, consulté le janvier 13, 2026, [https://www.thepondoutlet.com/pond-aerators](https://www.thepondoutlet.com/pond-aerators)  
9. Build a Spirulina Farm \- SLQ Wiki, consulté le janvier 13, 2026, [https://wiki.slq.qld.gov.au/doku.php?id=workshops:prototypes:build\_a\_spirulina\_farm:start](https://wiki.slq.qld.gov.au/doku.php?id=workshops:prototypes:build_a_spirulina_farm:start)  
10. DIY IoT Plant Watering System using Arduino, consulté le janvier 13, 2026, [https://projecthub.arduino.cc/me\_yogesh/diy-iot-plant-watering-system-using-arduino-b00eb3](https://projecthub.arduino.cc/me_yogesh/diy-iot-plant-watering-system-using-arduino-b00eb3)  
11. Arduino Greenhouse Control \- Humidity and Temperature : 3 Steps \- Instructables, consulté le janvier 13, 2026, [https://www.instructables.com/Arduino-Greenhouse-Control-Humidity-and-Temperatur/](https://www.instructables.com/Arduino-Greenhouse-Control-Humidity-and-Temperatur/)  
12. Arduino \- DHT22 \- Relay | Arduino Tutorial, consulté le janvier 13, 2026, [https://arduinogetstarted.com/tutorials/arduino-dht22-relay](https://arduinogetstarted.com/tutorials/arduino-dht22-relay)  
13. How did the ancient Egyptians measure slopes?, consulté le janvier 13, 2026, [https://web.mae.ufl.edu/uhk/EGYPTIAN-LEVEL.pdf](https://web.mae.ufl.edu/uhk/EGYPTIAN-LEVEL.pdf)  
14. Compound Miter Cuts \- Waterfront Woods, consulté le janvier 13, 2026, [https://www.waterfront-woods.com/festool/Compound\_Miter.pdf](https://www.waterfront-woods.com/festool/Compound_Miter.pdf)  
15. Miter angle chart \- WoodCentral, consulté le janvier 13, 2026, [https://www.woodcentral.com/-/miter-angle-chart/](https://www.woodcentral.com/-/miter-angle-chart/)  
16. Giza Pyramid Corner Joints for PVC Pipes (3D Printable) \- Etsy, consulté le janvier 13, 2026, [https://www.etsy.com/listing/1681466530/giza-pyramid-corner-joints-for-pvc-pipes](https://www.etsy.com/listing/1681466530/giza-pyramid-corner-joints-for-pvc-pipes)  
17. Russian Pyramid Corner Joints for PVC Pipes STL Format 3D Model Files \- Etsy, consulté le janvier 13, 2026, [https://www.etsy.com/listing/1876020795/russian-pyramid-corner-joints-for-pvc](https://www.etsy.com/listing/1876020795/russian-pyramid-corner-joints-for-pvc)  
18. Best mounting method for Flexible solar panels to an RV roof, consulté le janvier 13, 2026, [https://diysolarforum.com/threads/best-mounting-method-for-flexible-solar-panels-to-an-rv-roof.76956/](https://diysolarforum.com/threads/best-mounting-method-for-flexible-solar-panels-to-an-rv-roof.76956/)  
19. How to Build & Use a Dye-Sensitized Solar Cell (DSSC) \+ a Discussion on Energy & Efficiency \- Instructables, consulté le janvier 13, 2026, [https://www.instructables.com/How-to-Build-Use-A-Dye-Sensitized-Solar-Cell-DS/](https://www.instructables.com/How-to-Build-Use-A-Dye-Sensitized-Solar-Cell-DS/)  
20. Self-Cooling Paint ™ – A Passive Radiative Cooling Solution \- SRI International, consulté le janvier 13, 2026, [https://www.sri.com/fcd\_technology/self-cooling-paint-a-passive-radiative-cooling-solution/](https://www.sri.com/fcd_technology/self-cooling-paint-a-passive-radiative-cooling-solution/)  
21. Cooling Paint You Can Actually Make \- Hackaday, consulté le janvier 13, 2026, [https://hackaday.com/2023/07/03/cooling-paint-you-can-actually-make/](https://hackaday.com/2023/07/03/cooling-paint-you-can-actually-make/)  
22. "Warka Water: drinking of the air" by Architecture and Vision \- More Than Green, consulté le janvier 13, 2026, [https://www.morethangreen.es/en/warka-water-bebiendo-del-aire-por-architecture-and-vision/](https://www.morethangreen.es/en/warka-water-bebiendo-del-aire-por-architecture-and-vision/)  
23. Geometry and surface manipulation impact on passive dew and rain collection | Request PDF \- ResearchGate, consulté le janvier 13, 2026, [https://www.researchgate.net/publication/383635791\_Geometry\_and\_surface\_manipulation\_impact\_on\_passive\_dew\_and\_rain\_collection](https://www.researchgate.net/publication/383635791_Geometry_and_surface_manipulation_impact_on_passive_dew_and_rain_collection)  
24. DIY Airlift Pump Design: Pump Water with Compressed Air \- Countryside, consulté le janvier 13, 2026, [https://www.iamcountryside.com/self-reliance/diy-airlift-pump-design-pump-water-with-compressed-air/](https://www.iamcountryside.com/self-reliance/diy-airlift-pump-design-pump-water-with-compressed-air/)  
25. Design, Construction, and Validation of an Internally Lit Air-Lift Photobioreactor for Growing Algae \- ResearchGate, consulté le janvier 13, 2026, [https://www.researchgate.net/publication/271839995\_Design\_Construction\_and\_Validation\_of\_an\_Internally\_Lit\_Air-Lift\_Photobioreactor\_for\_Growing\_Algae](https://www.researchgate.net/publication/271839995_Design_Construction_and_Validation_of_an_Internally_Lit_Air-Lift_Photobioreactor_for_Growing_Algae)  
26. Homemade Low-tech Organic Spirulina Culture : 19 Steps ..., consulté le janvier 13, 2026, [https://www.instructables.com/Homemade-Organic-Spirulina-Culture/](https://www.instructables.com/Homemade-Organic-Spirulina-Culture/)  
27. Automating Greenhouse Ventilation with Arduino and Temperature Sensors \- Medium, consulté le janvier 13, 2026, [https://medium.com/@wwwebadvisor/automating-greenhouse-ventilation-with-arduino-and-temperature-sensors-15aa705315b8](https://medium.com/@wwwebadvisor/automating-greenhouse-ventilation-with-arduino-and-temperature-sensors-15aa705315b8)  
28. The accurate construction of the right angles of the Great Pyramid's ground plan, consulté le janvier 13, 2026, [https://web.ujaen.es/investiga/egiptologia/journalarchitecture/downloads/JAEA4/JAEA4\_Clerc.pdf](https://web.ujaen.es/investiga/egiptologia/journalarchitecture/downloads/JAEA4/JAEA4_Clerc.pdf)  
29. Dimensions of the Cheops (Khufu) pyramid and building materials involved., consulté le janvier 13, 2026, [https://www.cheops-pyramide.ch/khufu-pyramid/khufu-numbers.html](https://www.cheops-pyramide.ch/khufu-pyramid/khufu-numbers.html)  
30. Growing algae in diluted urine & Final project | Learning in public, consulté le janvier 13, 2026, [http://www.itp.jasminesoltani.com/2017/04/26/growing-algae-in-diluted-urine-final-project/](http://www.itp.jasminesoltani.com/2017/04/26/growing-algae-in-diluted-urine-final-project/)  
31. Spirulina cultivation as part of permaculture \- plants \- Permies.com, consulté le janvier 13, 2026, [https://permies.com/t/64306/Spirulina-cultivation-part-permaculture](https://permies.com/t/64306/Spirulina-cultivation-part-permaculture)  
32. What makes flexible solar panels inferior compared to rigid ones? : r/SolarDIY \- Reddit, consulté le janvier 13, 2026, [https://www.reddit.com/r/SolarDIY/comments/10eflfn/what\_makes\_flexible\_solar\_panels\_inferior/](https://www.reddit.com/r/SolarDIY/comments/10eflfn/what_makes_flexible_solar_panels_inferior/)  
33. Compound Miter Saw Calculator, consulté le janvier 13, 2026, [https://jansson.us/jcompound.html](https://jansson.us/jcompound.html)  
34. Automating a Greenhouse With LoRa\! (Part 2\) || Motorized Window Opener \- Instructables, consulté le janvier 13, 2026, [https://www.instructables.com/Automating-a-Greenhouse-With-LoRa-Part-2-Motorized/](https://www.instructables.com/Automating-a-Greenhouse-With-LoRa-Part-2-Motorized/)

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAoAAAAZCAYAAAAIcL+IAAAA3ElEQVR4XmNgGHSAFYjFgZgDXQIGGIE4HIifAPFmKI0V5ADxcyA2g/KjgVgRIQ0BYkB8CoiFkcSMgbgViQ8GINPK0cR8gXghsgDI4dcZICYggyIgnoQs4AHE/4CYB0kM5LGlDBDFYMALxIeB+D8Qz0LCIF+DNCvBFMowQILhLUwACtIZIJpZYAIgd30F4tMwAQaI5BoGiEI4gCkEScAAyDpQeF5BEoMrRA4GUFCBTItBEgP7bgoQ7wBiTiCeA8R7gJgfWREMyAPxRSheBcRCqNKoAJRiBNAFRwFRAABeBiYByZSPBgAAAABJRU5ErkJggg==>

[image2]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAAZCAYAAAA8CX6UAAAA3klEQVR4Xu2RPQ5BQRRGr0IjEZHYhEKlEq1GJ6LT6FiAlSgVVEoasQKl2gIsQKmQCL4vdzDue5m8oX0nOYU5482fSE4sA7iCc2PXdTtO26590ZDPxx5wAnuw5rrfTnDktQRluBedbOGfjqKtb1qCOjzDiw2gKTrOznlBuBJXPNgAxqKNO+bOg8xEJy9tEB1j45wgr2Nd4VT0cn1vrkcdq2oa+elYBdP4O9OxuAPuhJOHphE+ffSz85ktHMt0P2vRFTewZFoFbuECFk170xJ9JX7Edwc78J7S0u4wJ+dvnux2QnpaZwDfAAAAAElFTkSuQmCC>

[image3]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAAZCAYAAAA8CX6UAAABTklEQVR4Xu2TwStEURTGP6GoEUqhmSI7KwtJkmxsx4Ll/Auzmo3sbOwlpSQ7K2tWimytFJGlRJQFZSGF75tz78yZ+5rFrM1Xv7rvu++de8495wFttaJOUiCLZDQ8e3WQB/JEXshk43Zdd7CXXskveYd9HKX1Gvkml2TQ7VWlF3bIfOKXyS0Zdt4m7JCS82rKkfOA1lEz5IcsOe+YvKFJWcpoi+ySLudPw04vOu8Z9bIGAg1SMH8fkjL5hAWMUoZn5IJcwS5/xO1nNAsLMua8HvJFFpynq2haqj6+J9eJr9FIu9WHbNZV9ZNTWOppyip1P/EmyAeZ8mY32SNHsICSSsyHdQXZti+TGzLkzXVYoF7nHcDGQNIwxnXUNtnwxiqs1Sn+TubISljrMJWprtUUBzINIjSA6pak8Xgkh7BmnJDxsNeydKh+6MwgtvWv9QdNXkJfqafoWQAAAABJRU5ErkJggg==>

[image4]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAD8AAAAZCAYAAACGqvb0AAAChUlEQVR4Xu2XzetMURjHH6HkJZS8RHmJhRUlyctKiIWNlyjJSjbWxF8hKfUjYqPsLOwnZENWRCSRCCHCRl6+nznnmXnu+c1oZuHO4nc/9WnmnnNuc5/nPPecM2YNDQ0TkdXylfwmzxZ9o2CO3CJXlR2ByXKJXJS/92OS3Gj/GDdP3pJ/5KGir26uyw/ytfxlaTJmVEaYrZdP5BtLz/xFHrAUaGSZvCvH5G35TK6NA5y38p6cW3bUyE55XE4NbZ/l79wH5+R9ubkzIt1DEh7LBaGN+7b5IEsV/tHGJ6k9cNQlf1J+l+tCGzNGYP5srXzN58zcRiX8sG6wtNNPoATsUPovLVV6BS95sj6/6KuL7ZZmj3fZaVl6tiv5+ky+Pi+n5DaSRdJo3y1XWKpkAiVgx5MSk2vTLGXuqnwhH8jD1qM8aiCWPDyyFBRVATzTrPzpMNvMuleNJ6Nf8CSoAzez0MQfjqXWC7K+b0iHZbalRW9v2RHYYCnQp3JpbiM4nn+g4E/b+FU+ltooYCJYpfeUHQUE/dC6gcMuGzB4Sv6mXOMNGW6+WLTVBSV9Qn4qOwqoDLbohUX7wGXP1vDcqlscgwj+WGirE8qcGfU9ebGl8o54ZZAAhzGM7bfgsVawe7A7tPHlPy4gbA8cMpaHtpLplhI0jIOwSd6RK0MbrySvpsNJ7ZSl4B3WoEuWAmMiObN8tWpFe6wkqA03XbPunsmPU27lqlsHvLdlwvCnpeMuUBUsguUYjIc0kscJ8HK+ZnJJGK9DBfZVyuGGfCePVrtrg+2sDAjjYaXVo99l7WINc7bK9/KgvGBpO98f+jtwsOH9H8WM/0/4X3BE7sjfGxoaGhoaJgp/AezFpX3od195AAAAAElFTkSuQmCC>

[image5]: <data:image/png;base64,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>

[image6]: <data:image/png;base64,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>

[image7]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA0AAAAaCAYAAABsONZfAAAAuUlEQVR4XmNgGP4gAIjnAvEsNDwTiIWR1KEAXSAOAeKlQPwfiLOhfGcgZkVShxVMYoBoYkSXwAV4gfgwA0QT0SCIAaLhNLoEPgBz2hx0CVwA2WnRaHI4gSYQvwXiT0CsjyaHEyD7RxBNDgRAYighChIAKcblNJBiP3RBmNO+ArExmhwIgMTE0QVBpuNymgQQH2LAEtlrGSCaQEkIJikNxMlA/BGI/0HFwMASiH8yQDTgwyRF9igYeAAA03ssSn5UfZIAAAAASUVORK5CYII=>

[image8]: <data:image/png;base64,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>

[image9]: <data:image/png;base64,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>

[image10]: <data:image/png;base64,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>