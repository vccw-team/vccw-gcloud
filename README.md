# Google cloud SDK installer for VCCW

It installs `gcloud` to the VCCW machine.

## How to use

Run following commands.

```
$ curl -L https://raw.githubusercontent.com/vccw-team/vccw-gcloud/master/install.sh | bash
```

Or add following lines into `provision-post.sh` in your VCCW project.

```
#!/usr/bin/env bash

set -ex

curl -L https://raw.githubusercontent.com/vccw-team/vccw-gcloud/master/install.sh | bash
```

## What is installed

* Google cloud SDK
* Cloud SQL proxy

https://cloud.google.com/php/tutorials/wordpress-app-engine-flexible
