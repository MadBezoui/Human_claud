# Human_claud

Un skill pour Claude Code qui aide à écrire des textes et des designs sans les marques typiques de l'IA : tirets cadratins, point-virgules, titres en majuscules partout, deux-points dans les titres, vocabulaire générique, listes à puces partout, couleurs délavées.

Le skill couvre les réponses dans le chat, les articles, les rapports, les emails, les slides et les pages web.

## Ce qu'il évite

- La ponctuation : pas de `—`, `--`, `---` ni `;`.
- Les titres : casse de phrase, pas de deux-points, peu de titres.
- Le vocabulaire IA en français et en anglais (*delve*, *tapestry*, *au cœur de*, *force est de constater*…).
- Les structures de chatbot : ouverture « Bien sûr ! », conclusion « N'hésitez pas à… », triades réflexes.
- Les sections et sous-sections inutiles, les listes à puces à chaque paragraphe.
- Les couleurs pâles et les polices peu lisibles. La police par défaut est Avenir, sauf si une revue ou un template impose autre chose.

## Installation

Copie le fichier `SKILL.md` dans un dossier `Human_claud` de tes skills Claude Code :

```bash
mkdir -p ~/.claude/skills/Human_claud
curl -o ~/.claude/skills/Human_claud/SKILL.md https://raw.githubusercontent.com/MadBezoui/Human_claud/main/SKILL.md
```

Relance Claude Code ou ouvre une nouvelle session. Le skill se charge quand tu demandes un texte ou un design.

## Limites

Le skill ne cherche pas à tromper un détecteur d'IA. Son but est un texte naturel et lisible. Il ne retire pas les informations ni les nuances : seule la forme change.

## Licence

Usage libre. Ajoute une licence si tu veux préciser les conditions de réutilisation.
