# Docker + Node.js

1. Lägg node_modules i .dockerignore
2. Kolla denna dockerfile
3. Skriv först i terminal (döp efter namn och app namn + version och en "." om du är i rätt folder):

- docker build -t WilliamBostrom/testapp:1.0 .

3. skriv i terminal (byt ut porten som är vald med en annan port och lägg till docker image)

- docker run -p 5000:8080 sha256:361e18d3296b9bf3d218900cd2cf77

5. För dela docker

- docker volume create shared-stuff

- mount source=shared-stuff,target=/stuff
