# Rapport du jury — v3 (tome 3, chapitres 1-6)

**Note globale : 8,6 / 10 → 8,9 / 10 — Verdict : À CORRIGER**

## Vérification des corrections du rapport v2
Les 4 points prioritaires du rapport v2 ont tous été vérifiés ligne par
ligne et confirmés corrigés et efficaces, sans régression : « avec un
sérieux » ramené à une seule occurrence apparente, les trois formulations
bannies depuis le tome 1 ont bien disparu, le motif « Un silence
tomba/suivit » n'a plus qu'une occurrence, et la fin du chapitre 3 est
désormais un crochet actif en dialogue.

## Points forts
- Première passe où la totalité des points prioritaires précédents
  ressort intacte à la relecture.
- Contenu pédagogique, mécanisme d'enquête fair-play et mise en place des
  twists jugés très solides (9-9,5/10).

## Problèmes identifiés (priorisés)
1. Priorité 1 — répétition exacte non détectée aux rapports précédents :
   « Fara hocha la tête, songeuse » présent deux fois (ch.5 et ch.6).
2. Priorité 1 — repérage d'une occurrence supplémentaire de « avec un
   sérieux » invisible au grep simple car scindée par un retour à la
   ligne dans le fichier source (ch.2 : « ...et regarda les deux enfants
   avec un\nsérieux qu'elle n'avait pas encore montré... ») : le texte
   affiché contenait donc réellement 2 occurrences, pas 1.
3. Priorité 2 — « imperturbable » utilisé 4 fois comme étiquette de
   dialogue pour 3 personnages différents (ch.1 x2, ch.4, ch.5).
4. Priorité 3 — doubles-incises à tirets créant des phrases à syntaxe
   complexe (ch.1 : carnet de Souly ; ch.2 : carnet de terrain de Fara ;
   ch.6 : « Sofia frissonna, pas de froid... »).

## Corrections apportées après ce rapport
- Ch.5 : « Fara hocha la tête, songeuse, avant de replier... » reformulé
  en « Fara replia sa carte d'un geste un peu trop brusque pour être
  vraiment détaché » (ch.6 conserve l'unique occurrence restante).
- Ch.2 : phrase reformulée pour supprimer à la fois la double-incise à
  tirets et l'occurrence cachée de « avec un sérieux » (« ...et son
  visage se fit soudain plus grave qu'il ne l'avait été depuis leur
  arrivée »).
- Ch.1 : un des deux « imperturbable » reformulé en « sans ciller » ;
  ch.5 : le second reformulé en « sans se démonter ». Les deux occurrences
  restantes (ch.1, Fara à la station ; ch.4, Christophe) sont conservées.
- Ch.1 : double-incise du carnet de Souly scindée en deux phrases.
- Ch.6 : double-incise « Sofia frissonna, pas de froid... » scindée en
  trois phrases courtes.
- Détecté en cours de correction : « avec un enthousiasme » dupliqué
  (ch.1 et ch.4, ce dernier non signalé par le rapport v3 initial) ;
  reformulé en ch.4 (« d'une voix de camelot difficile à ignorer ») pour
  éviter un nouveau doublon avec « avec une énergie » (ch.2).
- Vérification finale par un script de mise à plat des fichiers (pour
  neutraliser les faux négatifs dus aux retours à la ligne) : chaque
  étiquette « avec un(e) + nom » unique, « imperturbable » à 2/4,
  « hocha la tête, songeuse » à 1 occurrence, motif du silence à 1
  occurrence, aucune formulation bannie restante.
