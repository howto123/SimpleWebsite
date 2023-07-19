# SimpleWebsite
Experimenting with really simple informative websites

Auto Deploy is currently set up:
The result is visible at https://enchanting-bubblegum-65df32.netlify.app/

Run docker-server (localhost):
docker-compose up -d

# Development
Use some local server, zb VS Code Liveserver
npm run watch

# Deployment to Docker Container
Copy static site conent to /usr/share/nginx/html folder in nginx

Autodeploy to netlify: git push to main branch