cd c:\wamp\www
npx create-react-app theapp
cd theapp

curl -sL https://aws-amplify.github.io/amplify-cli/install-win -o install.cmd && install.cmd
npm install "@aws-amplify/ui-react@^3.1.0"

npm install
npm start

git init
git add .
git commit -m "initial commit"

ssh-keygen -t rsa -b 4096 -C "artidas@artidas.hu"
ssh-add "C:\Users\Admin\.ssh\id_rsa"

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
