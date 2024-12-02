# Github Renovate Configuration

This contains all Renovate configuration files for GitHub repositories. 

To add a reference to any of these configuration files, one needs to add the following line in `renovate.json`:

```
"extends": ["local>CLOUDTRUST/configuration-renovate-github:<config_name>"]
```
if the repository is in the same organization, or
```
"extends": ["github>CLOUDTRUST/configuration-renovate-github:<config_name>"]
```
outside of it.
