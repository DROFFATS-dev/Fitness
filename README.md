# 1. Unzip the file and go into the dist folder
unzip fitness-app-deploy.zip
cd dist

# 2. Initialize git and connect to your repo
git init
git remote add origin https://github.com/DROFFATS-dev/Fitness.git

# 3. Add everything and commit
git add .
git commit -m "Deploy fitness tracker app"

# 4. Push to GitHub
git branch -M main
git push -u origin main# Fitness
