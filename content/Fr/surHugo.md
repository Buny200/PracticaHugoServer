C'EST QUOI LE HUGO ?
===
Hugo est un générateur de site statique

Installer Hugo sous Windows
===
Pour installer la dernière version de Hugo sur Windows, la première chose à faire est d'aller sur le lien suivant.

LIEN VERS LA PAGE DE TÉLÉCHARGEMENT
===
https://github.com/gohugoio/hugo/releases

Lorsque nous ouvrirons le lien, nous téléchargerons la dernière version portant un nom similaire à hugo_extended_x.x.x_windows-amd64.zip .

Nous allons extraire le zip et déplacer le fichier Hugo.exe vers le chemin C:\Hugo\bin que nous allons créer.

allez dans le panneau de configuration--> propriétés système--> et cliquez sur les variables d'environnement
Dans la liste qui nous montrera nous chercherons la variable PATH, et à la fin nous ajouterons ';C:\Hugo\bin', Avec ce redémarrage du système, nous aurons installé hugo et nous pourrons le démarrer.

Installer Hugo sous Linux
===
Nous vérifions si Snap est installé

```snap version```

Cela devrait nous donner une réponse comme celle-ci :

```snap    2.55.3+22.04
snapd   2.55.3+22.04
series  16
ubuntu  22.04
kernel  5.15.0-48-generic
```
Si nous obtenons quelque chose comme ci-dessus, cela signifie que nous l'avons installé et que nous pouvons continuer
Installez le paquet hugo-extended
À l'aide du gestionnaire Snap, nous allons installer le package hugo-extended.

```snap install hugo --channel=extended```