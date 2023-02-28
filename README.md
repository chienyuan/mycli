# Tips


* bin/gnu-date
```sh
#!/bin/bash
podman run -it --rm ubuntu date "$@"
```
ex. 
./bin/gnu-date -d "next Friday" -I

* bin/vsce
podman build -f Dockerfile.vsce -t vsce
```sh
#!/bin/bash

podman run -it --rm -v $(pwd):/data vsce vsce "$@"
```

ex.
./bin/vsce package


