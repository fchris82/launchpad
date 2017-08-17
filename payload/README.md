eZ with ez Launchpad
====================

This project has been generated by eZ Launchpad.

You can find the full documentation here: https://ezsystems.github.io/launchpad

You can find the Launchpad repository here: https://github.com/ezsystems/launchpad

## Install and use

1. Install the launchpad with **curl** OR **wget**:
```sh
$ curl -LSs https://ezsystems.github.io/launchpad/install_curl.bash | bash

# OR

$ wget -O - "https://ezsystems.github.io/launchpad/install_wget.bash" | bash
```

2. Start the docker containers:
```sh
$ ~/ez up
```

3. Load data:
```
$ ~/ez importdata
```

4. Ready to use and develop:
```
# View containers:
$ ~/ez ps

# Enter the engine container:
$ ~/ez enter
```