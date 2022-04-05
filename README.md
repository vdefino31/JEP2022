Mesures automatiques de parole non-native : exploration pilote d'un corpus d'apprenans japonais de français et différenciation de niveaux
==

Ce répertoire fait partie d'un article des JEP (édition 2022) s'intéressant à l'évaluation automatique de la parole de Japonais apprenant le français.

Corpora
--
Les données utilisées dans cette étude sont issues du corpus CLIJAF [1], récoltées dans le cadre méthodologique général du projet IPFC [2, 3]. Un sous-ensemble du corpus est analysé, correspondant à une tâche de production orale semi-spontanée d'étudiants japonais apprenant le français en université au Japon. Cette tâche consiste en un entretien individuel semi-directif en français, mené par un locuteur natif (enseignant ou doctorant).

Six questions spécifiques ont été posées aux étudiants : 
1. _Quelles sont pour vous les plus grandes difficultés quand vous apprenez le français ?_
2. _Quelle est la meileure manière d'apprendre le français ?_
3. _Où est-ce qu'on parle le meilleur français ?_
4. _Quel est le français que vous souhaiteriez parler ?_
5. _Est-ce que vous avez déjà eu des difficultés à comprendre des francophones ?_
6. _Quelles sont pour vous les principales différences culturelles ou sociales entre la France et le Japon ?_

Les données ont été enregistrées dans les universités respectives des étudiants, transcrites orthographiquement avec alignement texte-son et séparées en tour de parole (un tour de parole étant la première réponse produite par l'apprenant, en adéquation avec la question posée).

Évaluations phonético-phonologiques, lexicales, syntaxiques et discursives
--
Un jeu de 13 paramètres phonético-linguistiques on été automatiquement extraits et mesurés à partir des productions orales des apprenants japonais de français. Ces paramètres sont : 
* basés sur le signal acoustique :
    * un indice de confiance (IC) associé à une reconnaissance de phonèmes,
    * le débit de parole (DP),
    * le pourcentage de parole (PP),
    * l'écart-type de la durée des pseudo-syllabes (ETD),
    * le nombre normalisé de pauses silencieuses (NPS),
    * un score de fluence normalisé (NF),
* basés sur les transcriptions des productions orales:
    * pour la richesse lexicale:
        * la diversité lexicale (utilisant l'index de Guiraud) (IG),
        * la densité lexicale (DL),
        * la sophistication lexicale (SL),
    * pour la complexité syntaxique :
        * la longueur moyenne des tours de parole (LP),
        * la profondeur moyenne des arbres syntaxiques (AS),
    * pour la cohésion du discours :
        * la proportion de connecteurs du discours (CD),
        * la diversité des connecteurs du discours (DC).

Évolution des paramètres phonético-linguistiques selon le niveau CECRL [4] des apprenants
--
Les Figures de ce répertoire montrent l'évolution des paramètres phonético-linguistiques selon le niveau CECRL des apprenants japonais de français.
La Table nommée « ANOVA » présente les différents résultats obtenus lors d'une analyse en variance entre les différents paramètres et le niveau CECRL.

Références
--
[1] Detey, S. (Ed.) (2011-2019). A longitudinal interphonological corpus of Japanese learners of French. JSPS: Grant-in-Aid for Scientific Research (B) 23320121 & 15h03227

[2] DETEY S. & KAWAGUCHI Y. (2008). Interphonologie du Français Contemporain (IPFC) : récolte automatisée des données et apprenants japonais. In Journées PFC : Phonologie du français contemporain : variation, interfaces, cognition, Paris : MSH.

[3] RACINE I., ZAY F., DETEY S. & KAWAGUCHI Y. (2012). Des atouts d’un corpus multitâches pour l’étude de la phonologie en L2 : l’exemple du projet "Interphonologie du français contemporain" (IPFC). In A. KAMBER & C. SKUPIEN, Eds., Recherches récentes en FLE, p. 1–19. Bern : Peter Lang.

[4] CONSEIL DE L’EUROPE (2001). Cadre européen commun de référence pour les langues : apprendre,
enseigner, évaluer (CECR). Paris : Didier.
