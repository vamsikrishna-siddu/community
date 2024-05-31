# WG S390x architecture Charter

## Scope

The S390x architecture working group takes care of all things related to supporting s390x architecture on KubeVirt clusters.
This includes all build processes, also support of failing builds or test lanes.

### In scope

#### Code

All the code which adds the support of s390x architecture in KubeVirt. Whether this is modifying KubeVirt code itself or the build, test, CI, documentation or infrastructure code around this.

#### Binaries

All the binaries (i.e container images,binaries, packages/rpms, etc.) which are required for KubeVirt build, test, CI and infrastructure to run on s390x architecture. In other words, maintaining these binaries to work on s390x architecture.

#### Services

Infrastructure including bare metal servers and s390x prow jobs which are used for build/test the support of KubeVirt on s390x


### Out of scope

Fixing of issues that are not related to s390x.

## Roles and Organization Management

This wg follows the Roles and Organization Management outlined in [OARP]

### Additional responsibilities of Chairs

- Be welcoming to new contributors
- Resolve conflicts

[OARP]: https://stumblingabout.com/tag/oarp/


