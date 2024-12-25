# Cypress Automation

1. All the tests should be created in e2e folder.
2. All page objects will be create in page-objects folder. It is good to create further sub-folder if there are multiple pages.
3. All specs should be created under specs folder. Again, sub-folders can be created based on the related specs.
4. All fixtures should be created in fixtures folder. Create sub-folders for related jsons.
5. Any custom commands should be written in command.ts
6. All file names should be kebab-case. example: google-search.page.ts
7. The page-objects files should be ending with .page.ts
8. The specs files should be ending with .specs.js

## How to run this project?

1. Run npm install
````
npm i
````
2. npm run start

## Run cypress tests

> npx cypress open
