
# Build

docker build -t jonfk/megacmd:latest .

# Run Interactively 

docker run --rm --name mega-get -it -v ~/Downloads/mega_downloads:/download -v ${PWD}/logs:/root/.megaCmd jonfk/megacmd:latest bash

# ref

Based on https://github.com/thelittlefireman/docker-megacmd
