# Simple web app for Pluralsight courses and Docker Deep Dive book

Exposes web server on port `8080` as per `./app.js`

See `Dockerfile` for more details

Referenced in:
- [Docker Deep Dive](https://www.amazon.com/Docker-Deep-Dive-Nigel-Poulton/dp/1521822808/ref=tmm_pap_swatch_0?_encoding=UTF8&qid=&sr=) 
- Getting Started with Docker video course (pluralsight.com)

**The app is maintained approximately once per year so may contain vulnerbilities.**

# Docker commands from tutorial
Go inside your codes folder and build image with all files (denoted by dot) and name it such as ahal/ctr-demo:2 : 
`docker image build -t ahal/ctr-demo:2 .`

Confirm image exists now
`docker image ls ahal/ctr-demo:2`

Pust image to dockerhub/ on prem registry or where you want to, workflow same
`docker image push ahal/ctr-demo:2`

Note: To push an image to Docker Hub, you must first name your local image using your Docker Hub username and the repository name that you created through Docker Hub on the web. You can add multiple images to a repository by adding a specific :<tag> to them (for example docs/base:testing ).
