# konfetti-homepage

The homepage of the Konfetti project.

Part of the Konfetti project: https://github.com/rootzoll/konfetti-app

# How to run homepage locally
docker build --tag konfetti/homepage . 
docker run --name konfettiHomepage -p 8080:80 -d konfetti/homepage 

# How to run from dockerHub
docker run --name konfettiHomepage -p 8080:80 -d konfetti/homepage 
