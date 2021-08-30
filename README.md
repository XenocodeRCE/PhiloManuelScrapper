# PhiloManuelScrapper
Utilitaire pour récupérer le contenu des manuels de philosophie de term gratuitement 👌

# Comment ça fonctionne ?
Suite à un trou dans la sécurité de [LibManuels](https://www.libmanuels.fr/) qui a un partenariat avec des maisons d'éditions on peut récupérer gratuitement le contenu des manuels de :
- Belin Éducation
- Delagrave
- Magnard
- Bimanuel

LibManuels propose de lire le contenu des livres mais pas de les télécharger, ce que mon utilitaire propose 😉

# Comment l'utiliser ? 
Il suffit de télécharger le logiciel, de remplire l'url sans le numéro de page et de donner un titre au manuel, puis de cliquer sur "Start".

Voici quelques URLs chinées sur le site directement :

- https://storage.libmanuels.fr/Delagrave/specimen/9782206401218/9/OEBPS/
- https://storage.libmanuels.fr/Magnard/specimen/9782210114517/17/OEBPS/
- https://storage.libmanuels.fr/Belin/specimen/9791035813338/3/OEBPS/



## Comment avoir ces URLs ? 

1. Aller sur la [bibliothèque](https://demo.lib-manuels.fr/bibliotheque) de LibManuels
2. Choisir un livre et cliquer sur **Lire**, cela va ouvrir une page avec le livre uniquement en lecture
3. Ouvrir l'inspécteur d'élements de votre navigateur (**CTRL** + **Shift** + **i** sur Chrome / Edge)
4. Cliquer dedans et appuyer sur **CTRL** + **F** pour lancer une recherche
5. Rechercher "https://storage.libmanuels.fr" et appuyer sur **Entrer**
6. Ca va mettre en surbrillance une ligne de code, prennez le lien dans l'élement "src="
 
La ligne de code à laquelle je fais référence est similaire à celle-ci :  
```html
<iframe height="2048" width="1480" title="left" src="https://storage.libmanuels.fr/Magnard/specimen/9782210114517/17/OEBPS/page002.xhtml" class="libmanuel-isipage-left faowcuh" frameborder="0" scrolling="no" style="pointer-events: auto;"></iframe>
```
Copiez tout sauf "page002.xhtml" et entrez le resultat dans le logiciel 😄
