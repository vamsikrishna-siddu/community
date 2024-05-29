# WG Responsibilities

All KubeVirt WGs must define a charter defining the scope and governance of the WG.

- The scope must define what areas the WG is responsible for directing and maintaining.
- The governance must outline the responsibilities within the WG as well as the roles
  owning those responsibilities.

## Steps to create a WG charter

1. Copy [the template][WG Template] into a new file under community/wg-*YOURWG*/charter.md
2. Fill out the template for your WG
3. Update [sigs.yaml] with the individuals holding the roles as defined in the template.
4. Add subprojects owned by your WG in the [sigs.yaml]
5. Create a pull request with a draft of your `charter.md` and `sigs.yaml` changes. Communicate it within your WG
   and get feedback as needed.
6. Send the WG Charter out for review to kubevirt-dev@googlegroups.com. Include the subject "WG Charter Proposal: YOURWG"
   and a link to the PR in the body.
8. Typically expect feedback within a week of sending your draft. Expect longer time if it falls over an
   event such as KubeCon/CloudNativeCon or holidays. Make any necessary changes.
9. Once accepted, the maintainers will ratify the PR by merging it.

## How to use the templates

WGs should use [the template][WG Template] as a starting point.


## Goals

The primary goal of the charters is to define the scope of the WG within KubeVirt and how the WG leaders exercise ownership of these areas by taking care of their responsibilities. A majority of the effort should be spent on these concerns.

[WG Template]: wg-charter-template.md
[sigs.yaml]: ../sigs.yaml

