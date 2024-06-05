# SIGs and WGs

## SIG

A **SIG (Special Interest Group)** is a group of people that owns a broad subject within the project - it has a scope that spans all aspects related to it (i.e. testing, structure, building etc).

It maintains or supports processes (i.e. creation of output artifacts) and handles all topics touching it's subject, i.e. issues and design proposals.

It defines mission and scope via it's charter, ownership of code via [OWNERS](https://www.kubernetes.dev/docs/guide/owners/), and defines its members roles (chairs and team leads) in [sigs.yaml].

Examples:
* [sig-network - charter](./sig-network/charter.md)
* [sig-network - kubevirt/kubevirt OWNERS_ALIASES](https://github.com/kubevirt/kubevirt/blob/a7e0311d8704663351abd4bc9bbc8511753d2838/OWNERS_ALIASES#L60)
* [sig-ci - sigs.yaml](https://github.com/kubevirt/community/blob/4f63a79c0ed810aa332cd6716d4986001d28bcd7/sigs.yaml#L119)

## WG

A **WG (Working Group)** is a group of people that owns a more specific topic within the project, possibly touching the scope of more than one SIG, with whom the WG interacts.

It defines mission and scope via it's charter, and it defines its members roles (chairs and team leads) in [sigs.yaml].


## Roles and Organization Management

All SIGs and WGs follow the Roles and Organization Management outlined in [OARP]

[OARP]: https://stumblingabout.com/tag/oarp/
[sigs.yaml]: ./sigs.yaml
