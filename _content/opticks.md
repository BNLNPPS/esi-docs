---
title: "Opticks"
layout: base5
name: opticks
---

{{ site.HR }}

#### Opticks

Here are the revised instructions to setup an environment for opticks on npps0:

* Set the following environment variables and load dependencies:

```bash
OPTICKS_HOME=/usr/local/src/esi-opticks/opticks
OPTICKS_PREFIX=/usr/local/opticks
OPTICKS_CUDA_PREFIX=/usr/local/cuda
OPTICKS_OPTIX_PREFIX=/usr/local/optix
OPTICKS_COMPUTE_CAPABILITY=89

source /opt/spack-0.21.0/share/spack/setup-env.sh
module load geant4 clhep boost cmake nlohmann-json
source $OPTICKS_HOME/opticks.bash
```

* As a one-time setup, create a special directory in your HOME and populate it with data

```bash
mkdir -p ~/.opticks/rngcache/RNG
opticks-prepare-installation
```

* Run tests provided by the package:

```bash
opticks-t
```


