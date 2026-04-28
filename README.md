# ai-quickstart-maas-code-assistant

## Install

### On AWS OpenShift cluster

Clone this repo and cd into the cloned repo

Copy the secrets template to your home directory and edit the secrets there
```bash
cp values-secret.yaml.template ~/values-secret-ai-quickstart-maas-code-assistant.yaml
```

Install the pattern
```bash
./pattern.sh make install
```
