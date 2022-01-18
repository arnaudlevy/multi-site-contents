
# Vous pouvez contribuer à ce site

Selon vos envies et/ou vos compétences en code vous pouvez nous aider soit à améliorer [les contenus][site_contents] de ce site, soit directement à contribuer sur le [code source de l'applicatif][repo_app].

---

### Améliorer les contenus

Tous les contenus de ce site sont ouverts sur le repo suivant :

📁 &nbsp; [**Contenus du site**][site_contents]

N'hésitez pas à créer une issue ou proposer vos corrections 😃 !

Si faire des *pull requests* c'est pas votre truc, vous pouvez aussi nous laisser un petit mot sur [notre pad dédié aux retours][pad_feedbacks] ...


----

### Contribuer au code source

Ce site est propulsé par une application open source que nous avons développé en interne. Nous avons appelé cet outil "**[multi-site][repo_app]**". Cet outil permet de générer un site de type SPA (*Single Page App*) à partir d'un *repo* Github ou Gitlab ne contenant que des fichiers markdown et des images. 

💻 &nbsp; [**Code source de l'outil 'multi-site'**][repo_app]


Les technologies utilisées pour l'outil **[multi-site][repo_app]** sont les suivantes : 
- [Nuxt.js](https://nuxtjs.org) - framework js
- [Buefy](https://buefy.org/documentation) - framework css
- [Axios](https://axios-http.com/) - pour les requêtes http côté client
- [Dotenv](https://www.npmjs.com/package/dotenv) - librairie js pour charger des variables d'environnement 
- [Gray matter](https://www.npmjs.com/package/gray-matter) - librairie js permettant de transformer en objet des données de type markdown ou yaml
- [vue-Showdown](https://vue-showdown.js.org/) - plugin js permettant de transformer en html des données de type markdown

N'hésitez pas à créer une issue si vous voyez des bugs ou des choses à améliorer 😃 !


---


### Déploiement

Le site est sous déployé sur [netlify](https://www.netlify.com/).

[![Netlify Status](https://api.netlify.com/api/v1/badges/5a774814-2a6a-4da7-a8b5-1cc3d654df2a/deploy-status)](https://app.netlify.com/sites/multi-site-app-test/deploys)

---

### Licences

- Les contenus du site sont sous licence **GNU General Public License v3.0**
- Le code source de l'application "multi-site" est sous licence **GNU General Public License v3.0**



[site_contents]: https://github.com/co-demos/multi-site-contents
[pad_feedbacks]: https://hackmd.io/@multi/retours-site-multi
[repo_app]: https://github.com/co-demos/multi-site-app
