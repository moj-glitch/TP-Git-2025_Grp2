# Le projet

## Description du projet

Le projet est composé de 4 branches: master, Eleve3, ilan-rossi et julian-Lavis--Fabbri.


Le projet est basé sur le projet forké et nous avons créé par dessus 2 fichiers tp.md différent, puis modifié le readme.md, puis supprimé le 

fichier tp.md. Nous avons une branche avec un dossier screenshot/ et une merge request depuis Eleve3.

La branche julian Lavis--Fabbri as le readme modifié depuis Eleve3 et son fichier tp.md supprimé depuis le revert.

```bash
$ git log --graph
* commit c67cd4364b61e045c153b02ea8558a7b1100ad77 (HEAD -> julian-Lavis--Fabbri, origin/julian-Lavis--Fabbri)
| Author: Pokecraft-exe <leviathancorp.officiel@gmail.com>
| Date:   Thu Nov 13 17:05:33 2025 +0100
|
|     feat/ julian Lavis--Fabbri revert tp.md
|
*   commit 949798a0a3d82a97ab80cc02cebea3eb3ebb33b8
|\  Merge: 5093e6a 2ca03aa
| | Author: Pokecraft-exe <leviathancorp.officiel@gmail.com>
| | Date:   Thu Nov 13 17:03:17 2025 +0100
| |
| |     Merge branch 'julian-Lavis--Fabbri' of github.com:moj-glitch/TP-Git-2025_Grp2 into HEAD
| |
| *   commit 2ca03aa6be102b727b6cbee247c53b216b93824b
| |\  Merge: 5e3169e 002652d
| | | Author: Pokecraft-exe <leviathancorp.officiel@gmail.com>
| | | Date:   Thu Nov 13 16:46:09 2025 +0100
| | |
| | |     Merge branch 'Eleve3' into julian-Lavis--Fabbri
| | |
| | * commit 002652d2289324254b0639e2ed26868becb5ccef
| | | Author: Pokecraft-exe <leviathancorp.officiel@gmail.com>
| | | Date:   Thu Nov 13 15:59:40 2025 +0100
| | |
| | |     feat/Julian Lavis--Fabbri modification readme
| | |
| * | commit 5e3169e18fa5036276507b37ff58731b1ffff873
| |/  Author: Pokecraft-exe <leviathancorp.officiel@gmail.com>
| |   Date:   Thu Nov 13 16:23:33 2025 +0100
| |
| |       feat/Julian Lavis--Fabbri création tp.md
| |
* | commit 5093e6a0d1413aa851631a596f0c61f4ac1f0fa5
| | Author: Pokecraft-exe <leviathancorp.officiel@gmail.com>
| | Date:   Thu Nov 13 16:58:43 2025 +0100
| |
| |     feat/ julian Lavis--Fabbri revert tp.md
| |
* | commit 52e7cf9729eee9ecb62c474de7077ef216deaaa3
|/  Author: test <moi@moimoi.com>
|   Date:   Thu Nov 13 16:18:21 2025 +0100
|
|       branche rossi ilan
|
* commit 58b17f6963231234186910ca7cde1dcf772ed3cc (origin/master, origin/HEAD, master)
| Author: Sarah Schlegel <sschlegel@myges.fr>
| Date:   Wed Nov 12 22:01:27 2025 +0100
|
|     Instructions TP Final
|
*
```


## Qustions


- 1) Fetch récupère le projet distant mais n'applique pas les modifications au wd.
- 2) Reset annule les commit et l'historique lorsque revert annule les commit mais conserve l'historique
