# Assayer Plugin Registry

The registry of record for independently distributed Assayer audit plugins.

`plugins.json` maps each plugin ID to its published versions. Plugin authors
publish by opening a pull request that adds or updates their version entry;
clients only ever read this file to download and verify wheels.
