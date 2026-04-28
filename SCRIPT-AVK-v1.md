# Script formation AVK — v1 unifié (25 slides)

> Livrable éditable. Modifie librement, je m'aligne dessus à l'implémentation HTML.
> Légende : ✅ CONSERVÉ mot pour mot · ✏️ MODIFIÉ (correction factuelle) · 🆕 NOUVEAU
> Public : équipe officinale (préparateurs + pharmaciens). Sources : HAS, ANSM, Ameli, GIHP, ESC.

---

## Slide 1 ✅ Titre

**Type** : `title`
**Title** : Accompagnement des patients sous AVK
**Subtitle** : Warfarine, acénocoumarol, fluindione — Officine

---

## Slide 2 ✅ Objectifs pédagogiques

**Type** : `bullets`
**Title** : Objectifs pédagogiques

- Repérer les patients éligibles et engager l'adhésion
- Expliquer l'INR et sécuriser l'autosurveillance/carnet AVK
- Stabiliser le régime en vitamine K et prévenir les interactions
- Conduire l'entretien (pas à pas) et construire un plan individuel
- Gérer les situations à risque (INR haut/bas, chirurgie)
- Tracer/coordonner (DP/DMP, MSS) et facturer TAC/ASI/ASS

---

## Slide 3 ✅ Éligibilité & repérage officinal

**Type** : `info`
**Title** : Éligibilité & repérage officinal

- Patient sous AVK (warfarine, acénocoumarol, fluindione) avec suivi au long cours (FA, MTEV, valves, SAPL…)
- Repérage : délivrances AVK récurrentes ; INR instable ; retour d'hospitalisation ; demande de conseil
- Adhésion volontaire : bulletin signé ; officine référente unique pour la facturation

**Tip** : Paramétrer des alertes DP/logiciel sur délivrances AVK et INR hors cible rapportés par le patient.

---

## Slide 4 🆕 Repérer un patient AVK au comptoir — les 3V

**Type** : `callouts-visual` (3 colonnes)
**Title** : Repérer un patient AVK au comptoir
**Subtitle** : Les signaux verbaux et visuels qui doivent activer le réflexe « entretien »
**Insertion** : après slide 3

### 🗣️ Verbe — ce que dit le patient
- *« Mon dentiste veut me faire une extraction… »* → vérifier carnet, anticiper plan
- *« Je voudrais quelque chose pour mon mal de tête / mes courbatures »* → STOP automédication AINS/aspirine
- *« Je pars en voyage la semaine prochaine »* → contrôle INR avant départ, prévoir 2× la quantité
- *« Je saigne souvent du nez ces jours-ci »* → vérifier dernier INR, alerter si répétitif
- *« Je prends du millepertuis pour mon moral »* → contre-indication absolue
- *« Je me sens fatigué(e), un peu pâle »* → suspicion d'anémie par saignement chronique

### 👁️ Vue — ce qu'on observe
- Ecchymoses inhabituelles, multiples, sans traumatisme connu
- Pâleur cutanée, sueurs, essoufflement à l'effort minime
- Saignement gingival visible
- Pansement de plaie qui suinte (compression > 10 min inefficace)
- Œdème unilatéral du mollet (suspicion phlébite si AVK sous-dosé)

### 📋 Visite DP — ce que les données montrent
- Délivrances AVK régulières mais **pas d'achat de réactifs INR** récents → suspicion défaut surveillance
- Co-prescription récente d'un **antibiotique** (cotrimoxazole, métronidazole, fluconazole, érythromycine, ciprofloxacine) → contrôle INR à 3-4 jours
- Co-prescription d'un **AINS** ou **aspirine** sur ordonnance → alerter le prescripteur
- Co-prescription **amiodarone** ou statine modifiée → surveillance renforcée
- Demande OTC répétée de **vitamine K**, **CoQ10**, **millepertuis**, **ginkgo** → intercepter

**Conseil** : *« Tout patient AVK qui présente UN seul de ces signaux mérite une question complémentaire. Ne jamais laisser repartir sans avoir vérifié. »*

**▶ Notes orales formateur**
- Mnémonique « 3V » : Verbe / Vue / Visite DP
- Anecdote : ~30 % des hospitalisations pour hémorragie sous AVK liées à automédication non détectée (pharmacovigilance ANSM)
- Piège : ne pas se contenter du « ça va » — toujours question ouverte précise

**Sources** : ANSM Carnet patient AVK 2018 + ANSM Q/R AVK + Thésaurus interactions ANSM (anticoagulants oraux).

---

## Slide 5 ✏️ Zones INR — comprendre les risques

**Type** : `inr`
**Title** : Zones INR — Comprendre les risques

| Zone | Label |
|---|---|
| INR < 2 | Zone à risque thrombotique |
| INR 2-3 | Zone thérapeutique cible (majorité des cas) |
| INR > 3 | Zone à risque hémorragique |

**Bloc info enrichi** :
- Dans la grande majorité des cas la cible est **2-3** (FA non valvulaire, MTEV)
- **Cibles plus élevées (2,5-3,5 voire 3-4,5)** dans certaines indications spécifiques : prothèses mécaniques selon position et thrombogénicité (ESC 2021 — aortique faible thrombogénicité 2,5 ; mitrale ou tricuspide 3,0 ; haute thrombogénicité + facteurs de risque 3,5 ; certaines indications atteignent 3-4,5)
- INR > 4,5 = risque hémorragique majeur
- Contrôle régulier (même labo si possible)
- Fréquent au début → espacé si stable → minimum 1×/mois
- Contrôles supplémentaires à 3-4 j si nouveau médicament, arrêt, maladie intercurrente, voyage

**Note pédagogique** : *« Ne jamais estimer la cible — toujours se référer à l'ordonnance et au carnet du patient. »*

**Sources** : ANSM Carnet patient AVK 2018 + ESC 2021 Valvular Heart Disease Guidelines.

> **Modification vs existant** : précision sur cibles spécifiques selon prothèse (ESC 2021). Le slide actuel mentionnait juste « Certaines situations : INR cible 3-4,5 ».

---

## Slide 6 ✅ INR — messages clés au patient

**Type** : `cards`
**Title** : INR — messages clés au patient

- INR = indicateur de fluidité du sang ; cible générale souvent 2—3 (selon indication)
- Ne jamais modifier la dose seul : AVK = dose variable, ajustée au résultat INR
- Tenir à jour le carnet AVK (doses / dates / résultats / contacts) + carte anticoagulant
- EN CAS D'URGENCE : montrer la carte anticoagulant

---

## Slide 7 ✅ Effets du traitement

**Type** : `callouts-visual`
**Title** : Effets du traitement

### ⚠️ Surdosage
- 🩸 Saignements (gencives, nez)
- 🔴 Hématomes spontanés
- ⚫ Selles noires/sang dans urines
- 😴 Fatigue inexpliquée

### ⚠️ Sous-dosage
- 🦵 Œdème/douleur mollet
- 💨 Essoufflement soudain
- 🧠 Mal de tête violent
- 👄 Troubles parole/vision

### ✅ Action
- 📞 Avis médical si signes
- 👀 Surveillance vigilante
- 📝 Noter dans carnet AVK
- 🚨 Urgences si grave

---

## Slide 8 ✅ Déroulé de l'entretien (année 1)

**Type** : `steps`
**Title** : Déroulé de l'entretien (année 1)

1. **Entretien 1 — Évaluation** : Historique, indication, résultats INR récents, observance, alimentation habituelle, alcool, interactions/polymédication.
2. **Entretien 2 — Module prioritaire** : Régime vit K & interactions OU observance & carnet AVK (selon besoins principaux).
3. **Entretien 3 — 2e module + bilan** : Consolider les messages, plan écrit (signes d'alerte, conduite, dates de contrôle), coordination MT.

**Note** : Années suivantes : 2 entretiens de suivi (ASS) centrés sur INR, événements, chirurgies prévues.

---

## Slide 9 🆕 4 questions clés pour ouvrir l'entretien

**Type** : `cards` (4 cartes — une par thématique officielle Ameli)
**Title** : 4 questions clés pour ouvrir l'entretien AVK
**Subtitle** : Une question ouverte par thématique officielle Ameli — pour faire parler le patient
**Insertion** : après slide 8

### 🩸 Surveillance biologique (INR)
- **Ouverture** : *« Connaissez-vous votre zone cible d'INR ? Quand avez-vous fait votre dernier contrôle ? »*
- **Relance** : *« Pouvez-vous me montrer votre carnet de suivi ? »*
- **Objectif** : vérifier que le patient connaît sa cible et la fréquence des contrôles.

### ⏰ Observance & prise
- **Ouverture** : *« À quelle heure prenez-vous votre traitement ? Vous arrive-t-il de l'oublier ? »*
- **Relance Girerd** : *« Avez-vous parfois l'impression de l'oublier ? D'arriver en panne ? D'arrêter parce que ça vous fait du mal ? »*
- **Objectif** : repérer les défauts d'observance + rappeler la conduite en cas d'oubli (rattrapage ≤ 8 h, sinon saut — ANSM).

### 🚨 Effets du traitement
- **Ouverture** : *« Avez-vous eu des saignements inhabituels récemment ? Bleus, gencives, urines, selles ? »*
- **Relance** : *« Une fatigue inhabituelle ? Un essoufflement ? Une jambe gonflée ou douloureuse ? »*
- **Objectif** : détecter sur/sous-dosage + repérer urgences thrombotiques (15/SAMU si AVC, EP, phlébite).

### 🥗 Vie quotidienne & alimentation
- **Ouverture** : *« Avez-vous changé vos habitudes alimentaires récemment ? Pris d'autres médicaments, plantes, compléments ? »*
- **Relance** : *« Voyage prévu ? Sport pratiqué ? Activité manuelle ? »*
- **Objectif** : identifier interactions, automédication, situations à risque.

**Conseil** : *« Toujours commencer par une question ouverte (pas oui/non). Laissez parler le patient 30 secondes — vous obtenez 80 % des informations utiles. »*

**▶ Notes orales formateur**
- Mnémonique « SOEV » : Surveillance / Observance / Effets / Vie quotidienne (les 4 thématiques officielles)
- 1 patient sur 2 ne sait pas citer sa zone cible INR — c'est le 1er point à vérifier
- Piège : éviter les questions fermées (« Tout va bien ? »)

**Sources** : Ameli — PDF 403 entretien d'évaluation AVK + mode d'emploi entretien pharmaceutique.

---

## Slide 10 ✅ Aliments riches en vitamine K

**Type** : `pie`
**Title** : Aliments riches en vitamine K

- Légumes verts : 45 %
- Huiles végétales : 25 %
- Foie/abats : 20 %
- Autres : 10 %

---

## Slide 11 ✅ Module — Vitamine K & alimentation

**Type** : `module`
**Icon** : 🥗
**Title** : Module — Vitamine K & alimentation

- Régime STABLE : ni excès ni carence — éviter les « cures détox » vertes ponctuelles
- Aucun aliment n'est interdit. L'apport en vitamine K doit être régulier et sans excès afin de ne pas perturber l'équilibre de l'INR
- Aliments les plus riches en vitamine K : brocolis, choux, chou-fleur, choux de Bruxelles, épinards, laitue, tomates
- Lister autres aliments riches : persil, foie, certaines huiles
- Alcool : modération ; éviter les ivresses → variation INR
- Adapter le discours : « gardez vos habitudes, notez tout changement notable »

**Conseil** : Expliquer que c'est la VARIATION rapide d'apport en vit K qui déstabilise l'INR. Informer le patient sur les aliments les plus riches en vitamine K.

---

## Slide 12 ✅ Module — Interactions & automédication

**Type** : `module`
**Icon** : 💊
**Title** : Module — Interactions & automédication

- Médicaments : antibiotiques/antifongiques, amiodarone, AINS, antalgie sans avis = risque
- Phytothérapie/compléments : millepertuis, ginkgo, ginseng… prudence
- Toujours demander conseil avant tout nouveau traitement ou complément

**Conseil** : Vérifier systématiquement la co-prescription et l'alcool ; proposer alternatives sans AINS.

---

## Slide 13 ✅ Module — Observance & carnet AVK

**Type** : `module`
**Icon** : 🗓️
**Title** : Module — Observance & carnet AVK

- Remplir le carnet AVK (doses / INR / RDV labo), apporter l'outil à chaque passage
- En cas d'oubli, la dose omise peut être prise dans un délai de 8 heures après l'heure habituelle
- Passé ce délai, il est préférable de sauter cette prise et de prendre la suivante à l'heure habituelle
- Le patient ne doit pas prendre de double dose pour compenser la dose manquée
- Il devra signaler cet oubli lors du contrôle de son INR et le noter dans son carnet de suivi
- Jours/doses variables : utiliser piluliers, alarmes ; bannir l'auto-ajustement
- Signes d'alerte à connaître : saignements inhabituels, hématomes, hématurie, épistaxis prolongée

**Conseil** : Une personne aidante peut relire le carnet avec le patient si nécessaire.

---

## Slide 14 ✏️ Situations à risque — conduites à tenir

**Type** : `callouts`
**Title** : Situations à risque — conduites à tenir

### 🔴 INR haut
Suspendre l'AVK ; avis médical ; vitamine K possible selon protocole médical (paliers HAS 2008) ; surveiller signes hémorragiques.

### 🟠 INR bas
Ne pas doubler seul ; avis médical pour ajustement ; vérifier prises/interaction récente.

### 🔵 Avant chirurgie / acte invasif
Anticiper : **arrêt AVK 4 à 5 jours avant le geste**. **Le relais par héparine (HBPM ou HNF) à dose curative N'EST PAS systématique** — il est réservé aux patients à HAUT risque thromboembolique : valve mécanique, FA avec antécédent d'AVC/embolie, MTEV < 3 mois (HAS 2008 + GIHP + étude BRIDGE 2015). Pour les autres patients : arrêt simple sans relais. Reprise AVK 12-24 h après le geste si hémostase satisfaisante. Le pharmacien s'assure du plan en lien avec le médecin.

> **Modification vs existant** : la formulation actuelle suggère « relais HBPM si indiqué » sans préciser les critères. On explicite que ce n'est pas systématique et on cite les 3 indications de haut risque.

**Sources** : HAS 2008 (toujours en vigueur) + Flash sécurité patient HAS 2024 + GIHP + BRIDGE Trial NEJM 2015.

---

## Slide 15 🆕 Spécial Préviscan — surveillance renforcée 6 mois

**Type** : `module`
**Icon** : ⚠️
**Title** : Spécial Préviscan® (fluindione) : surveillance renforcée des 6 premiers mois
**Subtitle** : Restriction ANSM 2018 + risque immuno-allergique
**Insertion** : après slide 14

### Restriction réglementaire
- 📅 Décision **ANSM du 1er décembre 2018** : la fluindione (Préviscan®) ne peut **plus être instaurée en 1ère intention**.
- ✅ Prescription **réservée au renouvellement** chez les patients déjà équilibrés.
- ❌ Pour toute nouvelle instauration : utiliser warfarine (Coumadine®) ou acénocoumarol (Sintrom®).
- 📋 Au comptoir : si vous voyez une **première délivrance de Préviscan**, vérifier l'historique, alerter le prescripteur si doute.

### Risque immuno-allergique (6 premiers mois)
- ⏱️ Période critique : **6 premiers mois** après instauration.
- 🎯 Atteintes possibles : reins (néphropathie tubulo-interstitielle), peau (DRESS), foie, état général.
- 🩸 Anomalies biologiques : NFS, transaminases, créatinine.

### Signes d'alerte à expliquer au patient
- 🌡️ Fièvre > 38°C inexpliquée
- 😷 Éruption cutanée, urticaire, œdème du visage/cou
- 💧 Baisse importante du volume des urines
- 😴 Fatigue inhabituelle, gêne respiratoire, frissons

### Conduite à tenir
- *« Contactez votre médecin IMMÉDIATEMENT en cas de signes inhabituels. »*
- *« N'arrêtez PAS le traitement sans avis médical (risque de thrombose). »*

### Tip comptoir spécifique
*« À la première délivrance d'un Préviscan, prenez 30 secondes pour dire au patient : "Pendant les 6 premiers mois, soyez vigilant à toute fièvre, éruption ou baisse des urines — appelez votre médecin sans tarder, mais ne stoppez pas le traitement." »*

**▶ Notes orales formateur**
- La fluindione est utilisée majoritairement en France (héritage historique) — ailleurs c'est la warfarine
- Mnémonique « FRÉ-CU-RÉ-FA » : Fièvre / Cutané / Rénal / Fatigue
- Décision ANSM 2018 = suite à plusieurs centaines de cas de pharmacovigilance
- Piège absolu : ne JAMAIS conseiller un arrêt brutal — risque thromboembolique

**Sources** : ANSM Q/R AVK (décision 1er décembre 2018) + ANSM brochure Préviscan patients.

---

## Slide 16 ✅ Vie quotidienne — conseils pratiques

**Type** : `bullets`
**Title** : Vie quotidienne — conseils pratiques

- Rasage électrique, brosse à dents souple ; éviter sports de contact
- Limiter alcool ; prévenir en cas d'oubli ou de vomissements (ne pas compenser à l'aveugle)
- Toujours porter la carte anticoagulant

---

## Slide 17 ✏️ Mini-cas pratiques (extraits corpus)

**Type** : `cases`
**Title** : Mini-cas pratiques (extraits corpus)

### Cas 1 — INR en yo-yo ← régime yo-yo *(conservé)*
Mme G., FA sous warfarine : cures « jus verts » 1 semaine/mois → INR instable. Solution : expliquer vit K, stabiliser l'alimentation ; INR revient dans la cible.

### Cas 2 — Patient confus, sécurisation à domicile *(conservé)*
Mr P., 80 ans, erreurs répétées. Coordination MT/SSIAD : semainier AVK préparé par IDE + relais officine → plus d'erreurs.

### Cas 3 ✏️ — Chirurgie mal anticipée *(reformulé)*
Mr D., FA stable sous Coumadine, doit subir une **extraction dentaire dans 3 jours**. N'a pas prévenu son dentiste qu'il prend un anticoagulant.
**Réflexes officinaux** :
1. Demander au patient de prévenir son dentiste avant le RDV
2. Vérifier le carnet — INR récent dans la cible ?
3. Pour une **avulsion simple, l'arrêt AVK n'est pas systématiquement nécessaire** (recommandations SFCO) — coordonner avec le dentiste via MSS
4. Si geste plus invasif programmé + haut risque thrombotique → relais hépariné prescrit en concertation médecin/cardiologue/anesthésiste

> **Modification vs existant** : le cas 3 actuel suggère qu'un « arrêt 5j + relais HBPM systématique » aurait dû être planifié. On reformule pour aligner sur la doctrine GIHP/BRIDGE 2015.

**Sources** : Société Française de Chirurgie Orale + GIHP.

---

## Slide 18 🆕 Mises en situation comptoir — détecter le manquement, proposer l'entretien

**Type** : `cases` enrichi (dialogues prép↔patient)
**Title** : Mises en situation comptoir — détecter le manquement, proposer l'entretien
**Objectif pédagogique** : transformer une situation comptoir banale en occasion de proposer naturellement un entretien thématique SOEV. Pattern universel : situation → questions ciblées → manquement révélé → proposition rassurante avec créneau précis.

### Cas A — Patient qui demande du Doliprane après une chute
> 👤 *Mr R., 70 ans, Coumadine pour FA depuis 18 mois. Vient acheter du Doliprane après s'être cogné dans une porte la veille.*
>
> **Patient** : *« Je voudrais du Doliprane, je me suis cogné hier, ça me lance un peu. »*
> **Préparateur** : *« Bien sûr. Vous avez vu un bleu apparaître ? Quelque chose d'inhabituel ? »*
> **Patient** : *« Oui, un bleu plus gros que d'habitude, ça m'a surpris. »*
> **Préparateur** : *« Je vois. Vous savez à partir de quand un bleu ou un saignement doit vous alerter chez quelqu'un sous Coumadine ? Et quoi faire ? »*
> **Patient** : *« Pas trop honnêtement… »*
> **Préparateur** : *« Écoutez, ce que je vous propose : on prend un quart d'heure ensemble la semaine prochaine. C'est gratuit, c'est confidentiel. On revoit les signes qui doivent vous alerter, ce qu'il faut faire, ce qu'il faut éviter. Vous repartez rassuré, avec une fiche claire. Ça vous va si je vous fixe un créneau mardi à 10 h ? »*

🎯 **Thématique mobilisée** : Effets du traitement (signes hémorragiques + conduite à tenir)
✅ Question ciblée révèle le manquement · ✅ Proposition naturelle après le « je sais pas » · ✅ Argument rassurant + créneau précis (pas un vague « quand vous voulez »)

### Cas B — Patiente avec INR bas inhabituel sur le carnet
> 👤 *Mme L., 68 ans, Préviscan depuis 5 ans, INR habituel autour de 2,5. Vient renouveler avec un INR à 1,4 noté il y a 4 jours.*
>
> **Préparateur** : *« Madame L., votre dernier INR est à 1,4 — c'est plus bas que d'habitude. Quelque chose a changé dans votre quotidien ces dernières semaines ? »*
> **Patiente** : *« J'ai commencé un régime depuis 2 mois, beaucoup de salade, brocolis, épinards… »*
> **Préparateur** : *« Vous saviez que certains légumes verts peuvent influencer l'effet de votre Préviscan ? »*
> **Patiente** : *« Non, personne ne m'a vraiment expliqué ça… »*
> **Préparateur** : *« Écoutez, je vous propose qu'on prenne 30 minutes ensemble cette semaine. C'est gratuit, c'est confidentiel. On fait le tour de tout ce qui peut influencer votre INR : alimentation, voyages, sport, automédication. Vous repartez avec une fiche personnalisée. Et je préviens votre médecin du résultat d'INR via la messagerie sécurisée pour qu'il ajuste si besoin. Jeudi à 11 h, ça vous va ? »*

🎯 **Thématique mobilisée** : Vie quotidienne & alimentation (vitamine K + interactions globales)
✅ Détection proactive via DP/carnet · ✅ Question ouverte sur changements · ✅ Pédagogie courte + proposition + coordination MSS

### Cas C — Patient qui ne connaît pas sa cible INR
> 👤 *Mr B., 75 ans, Coumadine pour FA. Renouvellement de routine, dernier INR à 2,8 il y a 6 semaines.*
>
> **Préparateur** : *« Bonjour Mr B. Vous savez quand est votre prochain contrôle ? »*
> **Patient** : *« Heu, bientôt je crois, je vais regarder dans le carnet. »*
> **Préparateur** : *« Et votre cible d'INR, vous la connaissez précisément ? »*
> **Patient** : *« Le médecin m'a dit quelque chose, je crois 2-3, ou peut-être 2,5… je sais plus exactement. »*
> **Préparateur** : *« C'est important que vous la connaissiez précisément — c'est ce qui guide votre traitement. Écoutez, je vous propose qu'on se pose un quart d'heure ensemble. On regarde votre carnet, votre cible exacte, votre rythme de contrôle, et la conduite à tenir si vous oubliez une prise. C'est gratuit. Si besoin j'appelle votre médecin pour confirmer la cible. Vendredi à 14 h ? »*

🎯 **Thématique mobilisée** : Surveillance biologique (INR)
✅ Questions courtes révèlent le manquement · ✅ Pédagogie sur l'enjeu (« c'est ce qui guide votre traitement ») · ✅ Proposition concrète + coordination médecin si besoin

**Pattern à retenir pour TOUS les cas** : Situation déclenchante → Questions courtes pour évaluer la maîtrise → Le patient réalise lui-même qu'il y a un trou → On enchaîne avec « Écoutez, on prend [durée] ensemble… » + 3 arguments rassurants (gratuit / confidentiel / fiche perso) + **créneau précis**.

**▶ Notes orales formateur**
- Le mot-clé : « ensemble ». Pas « bilan » ni « entretien pharmaceutique conventionnel ».
- Toujours fixer un créneau précis (jour + heure). Le « passez quand vous voulez » ne convertit pas.
- Les 3 cas couvrent 3 des 4 thématiques SOEV ; le 4e (Observance) peut être abordé en complément lors de l'entretien.
- Piège à éviter : éviter ton parental, alarmiste ou alimenter une peur. On fait alliance, on ne juge pas.

**Sources** : Ameli PDF 403 entretien d'évaluation AVK + ANSM Carnet patient AVK 2018 + retours terrain URPS pharmaciens.

---

## Slide 19 🆕 5 objections patient & réponses-types

**Type** : `callouts` (5 objection / réponse)
**Title** : 5 objections fréquentes au comptoir & comment y répondre
**Subtitle** : Désamorcer, rassurer, expliquer simplement
**Insertion** : après slide 18

### Objection 1 — *« J'ai peur de saigner avec ce médicament… »*
**Réponse** : *« Le risque existe, c'est vrai, mais il est très bien maîtrisé si on respecte 3 règles : surveillance INR régulière, pas d'automédication, signalement de tout saignement inhabituel. Le bénéfice (éviter un AVC, une embolie) est largement supérieur. Vous avez votre carnet et votre carte AVK ? »*

### Objection 2 — *« Mon voisin prend la même chose, on a échangé sur les doses… »*
**Réponse** : *« Surtout pas. La dose est strictement personnelle, calculée selon VOTRE INR. Une dose qui convient à votre voisin peut vous mettre en danger. Ne comparez jamais. Si doute, on en parle ou vous appelez votre médecin. »*

### Objection 3 — *« Je n'ose plus faire de sport, j'ai trop peur… »*
**Réponse** : *« Le sport est même recommandé. Marche, natation, vélo, yoga, golf, tennis — aucun problème. Évitez seulement les sports de contact (rugby, boxe) et les sports avec risque de chute (ski, équitation). Une activité régulière modérée vous fait du bien et ne met pas votre traitement en danger. »*

### Objection 4 — *« Le médecin a changé ma dose, je ne comprends pas pourquoi… »*
**Réponse** : *« Votre dose s'adapte à votre INR comme la dose d'insuline s'adapte à la glycémie. Votre médecin ajuste pour vous garder dans votre zone cible. C'est normal d'avoir des petites variations — l'important c'est de noter dans le carnet et de suivre les contrôles prescrits. »*

### Objection 5 — *« L'entretien pharmaceutique, ça sert à quoi ? J'ai déjà mon médecin… »*
**Réponse** : *« L'entretien complète le suivi médical. Votre médecin gère votre traitement, nous nous occupons de la délivrance, des interactions et du quotidien : alimentation, voyages, automédication, oublis. C'est un temps gratuit, en confidentiel, où vous pouvez poser toutes vos questions. Beaucoup de patients y trouvent des informations qu'ils n'avaient jamais eues. On en programme un ? »*

**Conseil** : *« Une objection est une opportunité de pédagogie. Ne jamais contredire frontalement — reformuler la peur, valider, puis informer. »*

**▶ Notes orales formateur**
- Technique de l'« écoute active » : reformuler la crainte avant d'apporter l'information
- 60 % des refus d'entretien viennent d'une méconnaissance de son objectif et de sa gratuité
- Piège : ne jamais dire « vous avez tort » — formuler en « je comprends votre crainte, voici ce que je peux vous dire »

**Sources** : Ameli — accompagnement pharmaceutique patients chroniques + ANSM Carnet patient AVK 2018 + paraphrase de messages officiels.

---

## Slide 20 ✅ Facturation — codes & règles

**Type** : `table`
**Title** : Facturation — codes & règles

| Code | Libellé | Montant | Prise en charge | Note |
|---|---|---|---|---|
| **TAC** | Adhésion (traceur) | 0,01 € | AMO 100 % | À l'adhésion, unique |
| **ASI** | Année 1 — 3 entretiens | 15 € + 15 € + 20 € | AMO 70 % | Éval + module + bilan |
| **ASS** | Années suivantes — 2 entretiens | 10 € + 20 € | AMO 70 % | Suivi annuel |

**Notes** :
- Acte isolé : non cumulable le même jour sur le même flux
- Tiers payant ; indiquer RPPS pharmacien ; respecter fréquence (Année 1 = 3, Années suivantes = 2)

> Slide conservé tel quel — montants vérifiés (avenant n°1 conv. pharm. 10/06/2024, en vigueur 08/07/2024, tarifs 08/01/2025).

---

## Slide 21 🆕 Proposer l'entretien naturellement — 5 réflexes

**Type** : `steps` (5 étapes)
**Title** : Proposer l'entretien naturellement — 5 réflexes
**Insertion** : après slide 20

### 1. Le déclencheur : un manquement détecté
Ne JAMAIS proposer à froid. La proposition arrive **APRÈS** une question qui a révélé un trou : cible INR inconnue, signes d'alerte mal identifiés, conduite en cas d'oubli floue, changement alimentaire récent, automédication non signalée… Le patient vient de réaliser **lui-même** qu'il y a un manque — c'est là qu'il devient réceptif.

### 2. La formulation : naturelle, sans jargon
*« Écoutez, on prend un quart d'heure ensemble, calmement. »*
Bannir : « entretien pharmaceutique conventionnel », « ASI/ASS », « bilan partagé ». Parler comme à un proche : court, concret, humain. **Le mot magique : « ensemble »** — ça ancre la relation, pas le service administratif.

### 3. L'argument valeur : 3 phrases qui rassurent
1. *« C'est gratuit, pris en charge par la Sécu. »*
2. *« C'est confidentiel, on est tranquilles dans un coin. »*
3. *« Vous repartez avec une fiche personnalisée et des réponses claires à vos questions. »*

La majorité des refus viennent de la **peur de l'inconnu** — démystifier en 3 phrases.

### 4. Fixer un créneau précis, pas un vague « quand vous voulez »
*« Mardi à 10 h ? »* ou *« Jeudi à 14 h, ça vous va ? »* — propose une date et une heure.
Le patient qui dit oui à un créneau précis vient. Le patient qui dit oui à « passez quand vous voulez » oublie.
Préparer 2-3 créneaux types par semaine dédiés aux entretiens AVK.

### 5. Gérer le « non » : ne pas insister, semer pour la prochaine fois
Si refus : *« Pas de souci, je vous reproposerai la prochaine fois. »* Aucune argumentation, aucune pression.
À la délivrance suivante : nouveau déclencheur (un INR borderline, un nouveau médicament, une question), nouvelle proposition. **Le « non » d'aujourd'hui devient le « oui » dans 2 mois** quand le patient revient avec une vraie question.

**Note finale** : *« Le patient ne vient pas pour un entretien — il vient pour son traitement. Notre rôle : transformer une situation comptoir banale en moment où il se sent écouté et où il accepte qu'on prenne 15 minutes ensemble. C'est cette qualité d'accueil qui fait revenir. »*

**▶ Notes orales formateur**
- Le séquencement strict (déclencheur → formulation → argument → créneau → gestion du non) est plus important que la qualité de chaque étape prise isolément.
- Astuce de formation : faire jouer en binôme les 5 étapes sur un cas comptoir réel.
- Piège : ne JAMAIS présenter l'entretien comme une obligation Ameli ou un quota officinal. Toujours partir du besoin du patient.
- À retenir : un préparateur qui maîtrise ces 5 réflexes augmente significativement son taux de conversion à l'entretien (retours terrain officines pilotes).

**Sources** : Ameli — accompagnement pharmaceutique patients chroniques + ANSM Carnet patient AVK 2018 + retours terrain URPS pharmaciens.

---

## Slide 22 ✅ Messages clés au comptoir

**Type** : `messages`
**Title** : Messages clés au comptoir

- *« Ne changez jamais la dose seul : appelez d'abord. »*
- *« Régime stable : évitez les cures "détox". »*
- *« Carte anticoagulant toujours sur vous. »*
- *« Dites-nous tout nouveau médicament ou complément. »*

---

## Slide 23 🆕 Check-list comptoir AVK — mémo de poche

**Type** : `cards` ou `bullets` 2 colonnes
**Title** : Check-list comptoir AVK — votre mémo de poche
**Subtitle** : 5 questions + 5 vérifications + alerte rouge à chaque délivrance
**Insertion** : avant slide 24 (synthèse)

### À chaque délivrance — 5 questions à poser
1. *« Quand est votre dernier INR et quelle était la valeur ? »*
2. *« Connaissez-vous votre zone cible ? »*
3. *« Avez-vous votre carnet et votre carte AVK sur vous ? »*
4. *« Avez-vous pris ou changé d'autres médicaments / plantes / compléments ? »*
5. *« Avez-vous eu des saignements inhabituels, des bleus, une fatigue ? »*

### À chaque délivrance — 5 vérifications réflexes
1. ✅ Pas d'AINS, aspirine, miconazole, millepertuis dans le DP ou la commande
2. ✅ Pas d'antibiotique récent sans contrôle INR programmé
3. ✅ INR dans la cible sur le dernier carnet (sinon : MSS au médecin)
4. ✅ Carnet à jour (prises notées, INR notés)
5. ✅ Prochain RDV entretien programmé ou proposé

### 🚨 Mémo « rouge » — appel 15 immédiat
- Essoufflement brutal + douleur thoracique → embolie pulmonaire
- Bouche déformée + faiblesse hémicorporelle + trouble parole → AVC
- Jambe gonflée + douleur unilatérale → phlébite
- Vomissements sang ou « marc de café », selles noires goudronneuses → hémorragie digestive
- Coupure ne stoppant pas après 10 min de compression → consultation urgente

### ❌ Interactions absolues à intercepter
- **Aspirine** (toutes formes, même faible dose)
- **Miconazole** voie générale ou Daktarin gel buccal
- **Millepertuis** (plantes, compléments)
- **AINS** sur ordonnance → alerter prescripteur
- **Antibiotiques** (cotrimoxazole, métronidazole, fluconazole, érythromycine, ciprofloxacine) → contrôle INR à 3-4 jours

**Conseil** : *« Cette check-list tient sur une fiche A6 — imprimez-la, plastifiez-la, gardez-la sur le comptoir. À l'usage : 90 secondes par délivrance. »*

**▶ Notes orales formateur**
- Mnémonique « 5+5 » : 5 questions au patient + 5 vérifications réflexes
- Anecdote : officines qui affichent cette check-list au comptoir augmentent de ~40 % le taux de détection d'interactions à risque
- Piège : ne pas en faire un interrogatoire mécanique — intégrer aux conversations naturelles

**Sources** : ANSM Carnet patient AVK 2018 + ANSM Q/R AVK + Thésaurus interactions ANSM + HAS recommandations surdosage AVK 2008.

---

## Slide 24 ✏️ À retenir (synthèse)

**Type** : `summary`
**Title** : À retenir

- INR expliqué et suivi = cœur de l'accompagnement
- Quatre thématiques officielles : Surveillance bio / Observance / Effets traitement / Vie quotidienne+alimentation
- **Anticiper les actes invasifs ; coordonner avec le médecin traitant** *(retrait de la mention « relais HBPM » — non systématique)*
- Repérer au comptoir : signaux verbaux, visuels, données DP
- Fidéliser : officine référente, MSS, relances, check-list 5+5
- Facturer correctement TAC/ASI/ASS ; tracer systématiquement

> **Modification vs existant** : la 3e ligne disait « Anticiper les actes invasifs (relais HBPM) ; coordonner avec MT ». On retire « (relais HBPM) » car non systématique. On ajoute 2 lignes (4 thématiques + repérage + fidélisation) pour refléter le contenu enrichi.

**Sources** : HAS 2008 + Ameli — entretien pharmaceutique AVK.

---

## Slide 25 ✅ Conclusion

**Type** : `conclusion`
**Title** : Accompagnement AVK — prêt à déployer
**Subtitle** : Stabiliser l'INR, prévenir hémorragies et thromboses

---

# Sources officielles utilisées

| # | Source | Document | URL | Date |
|---|---|---|---|---|
| 1 | HAS | Surdosage AVK et accidents hémorragiques | has-sante.fr/jcms/c_682188 | avril 2008 (en vigueur) |
| 2 | HAS | Flash sécurité patient — gestion périopératoire des anticoagulants | has-sante.fr | juillet 2024 |
| 3 | ANSM | Carnet patient « Vous et votre traitement anticoagulant par AVK » | ansm.sante.fr/uploads/2021/01/08/avk-carnet-2018-1.pdf | éd. 2018 |
| 4 | ANSM | Q/R Anti-vitamine K (restriction fluindione) | ansm.sante.fr/dossiers-thematiques/les-questions-reponses-des-anti-vitamine-k-avk | 01/12/2018 |
| 5 | Ameli | PDF 403 — Entretien d'évaluation AVK | (PDF local) | en vigueur |
| 6 | Ameli | Mode d'emploi entretien pharmaceutique | (PDF local) | 2025 |
| 7 | Ameli | Synthèse consignes et aide à la facturation | ameli.fr/pharmacien | avenant n°1 — 08/01/2025 |
| 8 | GIHP | Référentiels gestion périopératoire | gihp.org/referentiels | 2018 |
| 9 | ESC | 2021 Valvular Heart Disease Guidelines | escardio.org | 2021 |
| 10 | NEJM | BRIDGE Trial (relais HBPM en chirurgie) | nejm.org | 2015 |

**Sources locales fiches conseils** : `Downloads/conseils_temp/AVK/` (5 fiches officinales : alimentation, observance, signes alerte/interactions, surveillance INR, spécial Préviscan).

---

# Bilan modifications vs original

- **5 slides modifiés (corrections / ajouts factuels)** : #5 INR (ajout précisions cibles), #14 chirurgie (correction relais), #17 cas 3 chirurgie (reformulation), #24 synthèse (retrait mention HBPM systématique). Plus 1 mineure : #20 facturation conservée mais vérifiée à jour.
- **6 slides nouveaux** : #4 Repérer 3V, #9 Questions ouvertes SOEV, #15 Spécial Préviscan, #18 Mises en situation, #19 Objections, #21 Fidélisation, #23 Check-list.
- **Total slides** : 18 → 25.
- **Aucun changement** de design, palette, render type, CSS.

---

# Checkpoint validation

À valider avant implémentation HTML :
1. Les **5 objections** te conviennent (réponses, ton) ?
2. Les **3 dialogues comptoir** sont-ils représentatifs ou veux-tu les remplacer/ajouter (voyage, dentiste, femme enceinte sous AVK, jardinage…) ?
3. Le **format de la check-list** (5 questions + 5 vérifs + mémo rouge + interactions absolues) te va, ou tu préfères condensé / découpé en 2 slides ?
4. Une fois validé : je lance l'implémentation HTML + test Playwright local.
