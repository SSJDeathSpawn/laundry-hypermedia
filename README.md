# Laundry Project (Hypermedia version)

## Instructions

Setup mongodb

Your `MONGODB_URL` should be a valid connection string for a mongodb server. The docker compose file is given for convenience.

Then run these:

1. To install all the node packages
`npm i`

2. To make the tailwind.css file
`npx tailwindcss -i ./public/stylesheets/tailwind.raw.css -o ./public/stylesheets/tailwind.css`

3. Run the project
`$env.DEBUG = laundry:*; npm run watch`
