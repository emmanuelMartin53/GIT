# GIT

## Set up git

```bash
cd < nom_file >

git init # intialise le projet

git add . && git commit -m "titre_du commit"
```

## Push le projet sur github

```bash
git remote -v
```

ensuite

```bash
gh repo create --public --source=. # commande qui crée le repo public sur github
```

```bash
gh repo create --private --source. # commande qui crée le repo private sur github
```

```bash
git remote -v
# => An `origin` remote is now set!

git push origin master # Push le repo sur la branche origin master
gh browse # ouvre le repo github sur le navigateur
```
