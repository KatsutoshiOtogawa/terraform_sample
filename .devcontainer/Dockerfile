#-------------------------------------------------------------------------------------------------------------
# Copyright (c) Microsoft Corporation. All rights reserved.
# Licensed under the MIT License. See https://go.microsoft.com/fwlink/?linkid=2090316 for license information.
#-------------------------------------------------------------------------------------------------------------

# Update the VARIANT arg in devcontainer.json to pick an Ubuntu version: 20.04, 18.04
# To fully customize the contents of this image, use the following Dockerfile instead:
# https://github.com/microsoft/vscode-dev-containers/tree/v0.122.1/containers/ubuntu/.devcontainer/base.Dockerfile
ARG VARIANT="0.12.26"
FROM hashicorp/terraform:${VARIANT}

# ** [Optional] Uncomment this section to install additional packages. **
#
RUN apk update && apk upgrade 