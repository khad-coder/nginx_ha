# Création d'une Balise (Tag) Git

## Étapes à suivre

1. **Vérifiez la branche ou le commit que vous souhaitez taguer :**
   ```sh
   git checkout <branche-ou-commit>
   ```

2. **Créez une nouvelle balise :**
   ```sh
   git tag -a <nom-de-la-balise> -m "<message-de-la-balise>"
   ```
   Remplacez `<nom-de-la-balise>` par le nom souhaité pour la balise et `<message-de-la-balise>` par un message décrivant la balise.

3. **Poussez la balise vers le dépôt distant :**
   ```sh
   git push origin <nom-de-la-balise>
   ```

## Exemple

Voici un exemple de création d'une balise nommée `v1.0.0` avec le message "Première version" et de la pousser vers le dépôt distant :

```sh
git checkout main
git tag -a v1.0.0 -m "Première version"
git push origin v1.0.0
```
