# saytup-starter-launch

Créateur de nouveau projet Saytup en une ligne de commande.

Installez **Saytup Starter Launch** via npm :

```
npm install -g saytup-starter-launch
```

## votre première fois ?

Une fois installé globalement sur votre ordinateur (étape précédente), **Saytup Starter Launch** permet de créer un nouveau projet basé sur [Saytup Starter](https://github.com/agear-digital/saytup-starter).

Il lui suffit de connaître : 
- le nom de votre projet (il va créer le dossier)
- le repo du projet à récupérer (ce sera "agear-digital/saytup-starter")

Voici la syntaxe :

```
saytup-starter-launch nom-du-projet agear-digital/saytup-starter
```

Ou si vous êtes déjà dans le dossier de votre projet :

```
saytup-starter-launch . agear-digital/saytup-starter
```


## pour aller plus vite encore

Si vous ne souhaitez pas préciser systématiquement le chemin vers le repo de Saytup Starter, il est possible d'enregistrer votre configuration par défaut pour toutes les fois suivantes via `--configure`.

```
saytup-starter-launch --configure
Set repository: agear-digital/saytup-starter
Set key=value: (blank to skip) foo=bar
```

Puis il vous suffira de créer votre projet ainsi :

```
saytup-starter-launch nom-du-projet
```

Ou encore mieux si vous êtes déjà dans le dossier de votre projet :

```
saytup-starter-launch .
```

## License

MIT (auteur initial : Mathias Buus, cloné et adapté pour Agear Digital )