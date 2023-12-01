## What is this
- This is a boilerplate project for vite+react
- Project is under project folder
- The root folder is suitable for hosting as github pages
- The root folder is the target for build. See project/vite.config.ts

## How to create this project from scratch
- Follow: https://www.digitalocean.com/community/tutorials/how-to-set-up-a-react-project-with-vite
- Steps
    - Create a folder
    - Run: yarn create vite
    - Use project name as 'project'
    - Run: yarn
    - Edit vite.config.ts and set build folder as '..' (see project/vite.config.ts)
    - copy .gitignore from this repo to the root folder
    - To run the app: npm run dev
    - To build: npm run build

## How to clean the build files?
- Since the build folder is the parent folder, it is dangerous to run build clean command.
- Delete all the files except following
    - project
    - .gitignore
    - README.md
    
