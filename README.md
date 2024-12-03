# GitHub Renovate Configuration

This contains all Renovate configuration files for GitHub repositories. 

To add a reference to any of these configuration files, one needs to add the following line in `renovate.json`:

```
"extends": ["local>cloudtrust/configuration-renovate-github:<config_name>"]
```
if the repository is in the same organization, or
```
"extends": ["github>cloudtrust/configuration-renovate-github:<config_name>"]
```
outside of it.

Note: "cloudtrust" can also be in upper case as it is not case-sensitive.
