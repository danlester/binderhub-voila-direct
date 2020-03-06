# binderhub-voila-direct

A test Binder repo for running Voila directly without notebook - and also no auth, so doesn't use [jhsingle-native-proxy](https://github.com/ideonate/jhsingle-native-proxy/)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/danlester/binderhub-voila-direct/master)

Has an entrypoint that strips out port from the 'jupyter notebook' command and then runs Voila on the port provided.
