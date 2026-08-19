---
description: "Implémenter une fonctionnalité demandée dans le site HTML Jardin des compliments en respectant ses pages, son style et ses interactions"
name: "Ajouter une fonctionnalité au Jardin"
argument-hint: "Décris la fonctionnalité à ajouter, la page concernée et le comportement attendu"
agent: "agent"
---

Implémente la fonctionnalité décrite dans ma demande pour le site « Jardin des compliments ».

Contexte du projet :
- C’est un site statique en HTML, CSS et JavaScript sans framework apparent.
- Les pages sont à la racine du workspace et la navigation relie les expériences du site.
- L’interface est en français et s’adresse à un public enfant ou familial.
- Préserve l’identité visuelle ludique existante et les conventions déjà présentes dans les fichiers concernés.

Méthode obligatoire :
1. Identifie la page, le script et les styles qui contrôlent directement la fonctionnalité demandée.
2. Lis le code voisin et les liens de navigation avant de modifier quoi que ce soit.
3. Décris brièvement l’hypothèse sur le comportement attendu et les fichiers que tu vas toucher.
4. Implémente la plus petite modification complète, sans framework ni dépendance externe si le projet n’en utilise pas déjà.
5. Gère les états utiles : chargement, état initial, succès, erreur, absence de données et interaction répétée lorsque c’est pertinent.
6. Conserve les autres fonctionnalités et la compatibilité avec les petits écrans.
7. Ajoute des libellés accessibles, des éléments clavier utilisables et des alternatives textuelles pour les contenus non textuels.
8. N’ajoute pas de texte explicatif visible sur le fonctionnement de l’application ; l’interface doit rester naturelle et adaptée aux enfants.
9. Vérifie les chemins relatifs, les identifiants DOM, les événements et les liens entre pages.
10. Lance une validation ciblée adaptée au changement. Pour une interaction visuelle, ouvre la page dans un navigateur et vérifie au moins l’état initial, l’action principale et un cas limite.

Contraintes :
- Ne modifie pas des fichiers sans rapport avec la demande.
- N’écrase pas les changements existants de l’utilisateur.
- Utilise des caractères ASCII dans le code sauf si le fichier contient déjà des caractères non ASCII nécessaires au contenu français.
- N’ajoute pas de commentaire de code inutile.
- Si la demande est ambiguë, pose une seule question ciblée avant d’implémenter.

À la fin, résume en français : les fichiers modifiés, le comportement ajouté et la validation effectuée. Signale clairement toute vérification impossible.

Demande de fonctionnalité :
${input:feature:Décris la fonctionnalité à ajouter et la page concernée}
