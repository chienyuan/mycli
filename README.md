# My CLI 
Move the cli command into container using podman.
## bin/gnu-date
* ex. ./bin/gnu-date -d "next Friday" -I

## bin/vsce
* podman build -f Dockerfile.vsce -t vsce
* ex.  ./bin/vsce package

## bin/yo
* podman build -f Dockerfile.yo -t yo
* ex. yo code