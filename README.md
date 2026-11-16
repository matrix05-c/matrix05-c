<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3500&pause=1200&color=B48EE0&center=true&vCenter=true&multiline=true&width=720&height=80&lines=SELECT+*+FROM+developpeurs;WHERE+handle+%3D+'matrix05-c'%3B" alt="Requête SQL animée" />

</div>

| nom | role | ecole | ville |
|---|---|---|---|
| Caddy Rasolonjatovo | Développeur logiciel & Data Analyst | ENI Fianarantsoa (L3) | Fianarantsoa, Madagascar |

*(1 ligne)*

> Je vois mes compétences comme un modèle de données : des entités, et surtout les relations entre elles.
> Comprendre avant de construire.

## 📐 Modèle conceptuel

<p align="center">
  <img src="./assets/mcd.svg" alt="Modèle conceptuel animé : Caddy maîtrise des langages, réalise des projets, suit une formation et apprend Elixir" width="100%" />
</p>

<details>
<summary>Voir le même modèle en Mermaid</summary>

```mermaid
erDiagram
    CADDY ||--o{ LANGAGE : maitrise
    CADDY ||--o{ PROJET : realise
    CADDY ||--|| FORMATION : suit
    PROJET }o--o{ LANGAGE : utilise
    PROJET }o--o{ BASE_DE_DONNEES : stocke_dans
    CADDY ||--o{ APPRENTISSAGE : explore
```

</details>

## 🧩 Table `competences`

```sql
SELECT categorie, string_agg(outil, ', ') AS outils
FROM competences
GROUP BY categorie;
```

| categorie | outils |
|---|---|
| langages | Java, PHP, JavaScript, C#, Python, R, **Elixir** *(en apprentissage)* |
| backend | Spring Boot, Laravel, Node.js |
| frontend | Vue.js, React, Bootstrap |
| desktop | JavaFX, Qt Creator |
| bases_de_donnees | MySQL, PostgreSQL, Oracle |
| data | Pandas, NumPy, Matplotlib, R |
| modelisation | Merise, UML |
| outils | Git, GitHub, Docker, Postman, VS Code |

<p align="center">
  <img src="https://skillicons.dev/icons?i=mysql,postgres,elixir,java,php,python,r,laravel,spring,vue,docker" alt="Stack" />
</p>

## 📁 Table `projets`

```sql
SELECT nom, type, stack FROM projets ORDER BY id;
```

| nom | type | stack |
|---|---|---|
| [Interventions techniques](https://github.com/matrix05-c/ProjetProjet) | Web (stage JIRAMA) | Laravel, Vue.js, MySQL, Bootstrap |
| [Station-service](https://github.com/matrix05-c/php-Projet) | Web | Laravel, Vue.js, MySQL |
| [Bibliothèque](https://github.com/matrix05-c/gestion-bibliotheque) | Desktop | JavaFX, MaterialFX, PostgreSQL |
| [Gestion des salaires](https://github.com/matrix05-c/SalarieManagement) | Web | Laravel, Vue.js, Bootstrap |
| [Parking](https://github.com/matrix05-c/ParkingGestion) | Desktop | C#, MaterialDesign |
| [Reservia](https://github.com/matrix05-c/Reservia) | Web | React, Tailwind CSS |
| [E-commerce Data Analysis](https://github.com/matrix05-c/dataAnalyser) | Data | Python, NumPy, Pandas, Matplotlib |

## 🔄 Transaction en cours

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&duration=2200&pause=600&color=E48AC6&multiline=true&width=720&height=110&lines=BEGIN%3B;++INSERT+INTO+competences+(categorie%2C+outil%2C+niveau);++VALUES+('langages'%2C+'Elixir'%2C+'en+apprentissage')%3B;COMMIT%3B+--+bient%C3%B4t+%F0%9F%9A%80" alt="Transaction SQL animée" />

## 📬 `contact`

| canal | lien |
|---|---|
| portfolio | [caddy.is-a.dev](https://caddy.is-a.dev) |
| linkedin | [caddy-rasolonjatovo](https://www.linkedin.com/in/caddy-rasolonjatovo-46426b35b) |
| email | [caddyrasolonjatovo@gmail.com](mailto:caddyrasolonjatovo@gmail.com) |
