# wolfi-node-with-bash

Container image containing nodejs, npm, dumb-init and bash. Based on WolfiOS and
built using the
[apko-publish](https://github.com/chainguard-images/actions/tree/main/apko-publish)
GitHub Action.

The image is inspired by the [Chainguard node
image](https://images.chainguard.dev/directory/image/node/overview), i.e. I
adapted the
[apko.yaml](https://github.com/chainguard-images/images/blob/main/images/node/config/template.apko.yaml)
file used to built that image and added `bash`.

Kudos to the Chainguard team for making it so easy and painless to build a small
and secure image!

## Licensing

The container image contains software packages that are direct or transitive
dependencies.
