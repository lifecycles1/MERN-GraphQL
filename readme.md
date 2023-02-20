npm init -y (node modules and package.json on root directory are used for the server)

mkdir server / cd serve
npm i express express/graphql graphql mongoose cors colors
npm i -D nodemon dotev
change package.json scripts to contain "start" and "dev" lines

npm run dev (server)

mkdir client / cd client
npm i @apollo/client graphql react-router-dom react-icons
include both bootstrap cdn's from getbootstrap in public/index.html header tag

npm start (client)
