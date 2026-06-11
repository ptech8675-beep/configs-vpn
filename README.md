# Créer un dossier local
mkdir vpn-configs
cd vpn-configs

# Initialiser Git
git init

# Créer un fichier README
echo "# VPN Configurations" > README.md

# Ajouter les fichiers
git add .

# Commit initial
git commit -m "Initial commit"

# Ajouter le dépôt distant (remplacez par votre URL)
git remote add origin https://github.com/votre-username/vpn-configs.git

# Pousser vers GitHub
git branch -M main
git push -u origin main
