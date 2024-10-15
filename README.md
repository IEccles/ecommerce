# ecommerce
This is a full stack that uses handlebars, TypeScript and Sequelize.
The database is locally created on your machine and called database.sqlite. When new tables or columns are created/added you can update the database with the command `npm run migrate`

# Instructions for install
Node will need to be installed to run these commands. The instructions for node installation are here https://nodejs.org/en/download/package-manager

`git clone https://github.com/IEccles/ecommerce.git`

Once cloned cd into the repo:

`cd ecommerce`

Install dependencies:

`npm i`

Run the dev version on your machine (this will automatically create the database and a login for you)

Windows:

`npm run dev:win`

Linux:

`npm run dev:linux`
