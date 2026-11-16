<h1 align="center">Salut, moi c'est Caddy 👋</h1>
<p align="center"><i>Développeur logiciel & Data Analyst · Fianarantsoa, Madagascar</i></p>

```elixir
defmodule Caddy do
  @moduledoc """
  Étudiant en 3e année, Génie Logiciel et Base de Données,
  à l'ENI Fianarantsoa. Comprendre avant de construire.
  """

  def profil do
    %{
      nom: "Caddy Rasolonjatovo",
      role: "Software Developer & Data Analyst",
      localisation: {"Fianarantsoa", "Madagascar"},
      langues: [malagasy: :courant, francais: :courant, anglais: :intermediaire]
    }
  end

  def stack do
    %{
      langages: ~w(Java PHP JavaScript C# Python R Elixir)a,
      backend: ~w(SpringBoot Laravel Node.js)a,
      frontend: ~w(Vue.js React Bootstrap)a,
      desktop: ~w(JavaFX QtCreator)a,
      bases_de_donnees: ~w(MySQL PostgreSQL Oracle)a,
      data: ~w(Pandas NumPy Matplotlib R)a,
      modelisation: ~w(Merise UML)a
    }
  end

  def experience do
    [
      %{
        poste: "Développeur full-stack (stage)",
        entreprise: "JIRAMA",
        lieu: "Antsirabe",
        periode: ~D[2025-09-01]..~D[2025-12-31],
        stack: [:laravel, :vuejs, :mysql, :bootstrap]
      }
    ]
  end

  def en_ce_moment do
    "Apprendre Elixir, OTP et la concurrence sur la BEAM"
    |> String.split(", ")
    |> Enum.each(&IO.puts/1)
  end
end
```

```elixir
iex> Caddy.profil().role
"Software Developer & Data Analyst"
```

### 🗂️ Projets

```elixir
Caddy.projets()
|> Enum.filter(&(&1.vedette))
```

- **[Interventions techniques](https://github.com/matrix05-c/ProjetProjet)** : planification et suivi des interventions terrain (Laravel, Vue.js, MySQL)
- **[Station-service](https://github.com/matrix05-c/php-Projet)** : suivi des ventes et gestion du stock de carburant (Laravel, Vue.js, MySQL)
- **[Bibliothèque](https://github.com/matrix05-c/gestion-bibliotheque)** : gestion des livres, prêts et usagers (JavaFX, PostgreSQL)
- **[Parking](https://github.com/matrix05-c/ParkingGestion)** : entrées, sorties et places disponibles (C#)
- **[E-commerce Data Analysis](https://github.com/matrix05-c/dataAnalyser)** : indicateurs et visualisation des ventes (Python, Pandas, NumPy, Matplotlib)

### 📫 Contact

```elixir
Caddy.contact()
#=> %{
#=>   portfolio: "https://caddy.is-a.dev",
#=>   linkedin: "linkedin.com/in/caddy-rasolonjatovo-46426b35b",
#=>   email: "caddyrasolonjatovo@gmail.com"
#=> }
```
