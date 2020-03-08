# ApisCP Yarn Provider

This is a drop-in provider for [ApisCP](https://apiscp.com/) that installs Yarn.

## Installation

```
cd /usr/local/apnscp/resources/playbooks
git clone https://github.com/thundersquared/apiscp-yarn.git addins/apiscp-yarn
ansible-playbook addin.yml --extra-vars=addin=apiscp-yarn
```

## Usage

`yarn` will be available in user `PATH` and ready to use as long as you've installed a Node version. ApisCP provides `nvm` out of the box, a tool that allows you install Node by simply running the following command:

```
nvm install 12 # where 12 can be whatever node version, like 13.10.1
```

## Contributing

Submit a PR and have fun!
