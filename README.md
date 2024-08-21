# Getting-Started-with-AWS-Lambda

Before the Workshop: AWS Lambda Pre-requisites 

### Install Python 

[Link](https://www.python.org/downloads/)

```
curl -sSf https://rye.astral.sh/get | bash

```
Output 

```
(base) ➜  ~ curl -sSf https://rye.astral.sh/get | bash
This script will automatically download and install rye (latest) for you.
######################################################################## 100.0%
Welcome to Rye!

This installer will install rye to /Users/sangambiradar/.rye
This path can be changed by exporting the RYE_HOME environment variable.

Details:
  Rye Version: 0.38.0
  Platform: macos (aarch64)

✔ Continue? · yes
✔ Select the preferred package installer · uv (fast, recommended)
? What should running `python` or `python3` do when you are not inside a Rye man✔ What should running `python` or `python3` do when you are not inside a Rye managed project? · Run a Python installed and managed by Rye
✔ Which version of Python should be used as default toolchain? · cpython@3.12
Installed binary to /Users/sangambiradar/.rye/shims/rye
Bootstrapping rye internals
Fetching requested internal toolchain 'cpython@3.12.4'
Downloading cpython@3.12.4
Checking checksum
Unpacking
Downloaded cpython@3.12.4
Updated self-python installation at /Users/sangambiradar/.rye/self

The rye directory /Users/sangambiradar/.rye/shims was not detected on PATH.
It is highly recommended that you add it.
✔ Should the installer add Rye to PATH via .profile? · yes
Added to PATH.
note: for this to take effect you will need to restart your shell or run this manually:

    source "$HOME/.rye/env"

To make it work with zsh, you might need to add this to your .zprofile:

    source "$HOME/.rye/env"

For more information read https://rye.astral.sh/guide/installation/

All done!

```

### Install AWS CLI 

Link : - https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html


### Install terraform 

Link - https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli#install-terraform 
