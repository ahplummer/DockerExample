1. Install Docker
2. Build this: `docker build -t citadel .`
3. Run this: `docker run -v $(pwd):/host -it citadel:latest /bin/bash`
4. Once you're at a command prompt, inside the container, you can `cd /host` and you will be looking at the host file system (the current directory from where you're executing the docker run command).
5. You can then build out the `citadel.sh` file with whatever you like, and run this from inside the running docker container.
