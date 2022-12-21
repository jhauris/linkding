# FreeIPA testing

On first running docker-compose in this directory a free-ipa server will be created and data saved. See the file `freeipa-data/ipa-server-install-options` for the configuration options.

Login to the free ipa server at https://localhost:9000 and create a new user.

Then access the running linkding server at http://localhost:9090 and log in with that newly created user. The user will have user database entries populated from the FreeIPA database.