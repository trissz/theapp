cd c:\wamp\www
npx create-react-app theapp
cd theapp
npm start

git init
git add .
git commit -m "initial commit"

ssh-keygen -t rsa -b 4096 -C "artidas@artidas.hu"

git remote add origin git@github.com:artidas/theapp.git
git branch -M main
git push -u origin main

  npm start
    Starts the development server.

  npm run build
    Bundles the app into static files for production.

  npm test
    Starts the test runner.

  cd theapp
  npm start
