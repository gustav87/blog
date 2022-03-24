# Docker containerized Jekyll Blog

This is a jekyll blog served from the /docs folder, according to Github specifications. It is not hosted from root (/), because I'm using docker to containerize the blog so I don't have to install ruby on my system, and to make it more portable.

## Prerequisites
Make sure you have the following installed on your system:

- Docker https://www.docker.com/ (Latest "Stable")
- Node.js / NPM https://nodejs.org/en/

## Daily workflow
`npm start` to start your jekyll container (the first time you run this, you will download the jekyll image from Docker Hub). Visit http://localhost:4000/blog/ to see your site.

`npm stop` when you are done for the day and want to stop and delete the container.

`npm run kill` if you want to delete the image and container from your system. No files are deleted from your system by doing this. Just run `npm start` again.
