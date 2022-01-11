To go live and deploy

build the project first to get the dist folder
run
npm run build

edit package.json file add a script called
"deploy": "vercel --prod"

then run
npm run deploy

best options
dont link to an existing project
directory code is located in just leave blank (if youre in ur proj dir)

overwrite settings:
change the output directory to point to dist folder in project dir

tips: use space to select when deploying with vercel and enter to confirm
