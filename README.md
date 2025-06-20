# 🧠 Exercices Ruby - Basés sur le projet *learn_ruby*

> 📚 **Projet personnel d’apprentissage – réutilisé dans le cadre de ma formation THP**

Ce dépôt contient une série de **petits exercices Ruby** basés sur le projet [alexch/learn_ruby](https://github.com/alexch/learn_ruby).  
Je m’en suis **servi comme support pédagogique** pour m’initier à la programmation Ruby durant ma formation intensive chez **The Hacking Project (THP)**.

Le projet d’origine utilise la méthodologie **Test-Driven Development (TDD)** avec **RSpec**, et consiste à écrire du code pour faire passer des tests unitaires déjà fournis.

---

## ⚙️ Installation et préparation

1. Forkez ce dépôt  
2. Clonez votre version locale sur votre machine  
3. Dans votre terminal, placez-vous à la racine du projet :

```bash
cd chemin/vers/le/projet
```
4. Installez RSpec si ce n’est pas déjà fait :

```bash
gem install rspec
```
## 🚀 Démarrage des exercices
Le dossier contient 7 fichiers de tests, chacun correspondant à un fichier Ruby à créer ou compléter :

- Le premier fichier lib/00_hello.rb existe déjà
- Les suivants (lib/01_temperature.rb, etc.) sont à créer

## 📝 Déroulement
1. Lancez un test avec :

```bash
rspec spec/00_hello_spec.rb
```

2. Le test vous indique ce qu’il attend, par exemple que la méthode hello retourne "Hello!"
3. Complétez la méthode dans le fichier Ruby correspondant (lib/00_hello.rb)
4. Refaites tourner les tests jusqu’à ce qu’ils passent
5. Passez ensuite au fichier/test suivant

## 💡 Méthodologie
Cette méthode, appelée développement piloté par les erreurs, consiste à :

- Lancer les tests
- Identifier les erreurs ou méthodes manquantes
- Corriger le code
- Relancer les tests
- Répéter

## ⚠️ Astuces
N’utilisez pas d’espaces dans les noms de dossiers, cela génère des erreurs difficiles à comprendre.
Exemple :

Cela permet de s’habituer aux messages d’erreur et aux traces de pile, très utiles en développement.

```bash
# Mauvais
/Documents/Mon Travail/ruby

# Bon
/Documents/mon_travail/ruby
```
## 📜 Crédits
Ce projet est un fork du dépôt original :
https://github.com/alexch/learn_ruby, son créateur original

