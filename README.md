# d34dmeats Repository Template test

A template for GitHub-hosted ReaPack repositories with automated
[reapack-index](https://github.com/cfillion/reapack-index)
running from GitHub Actions.

Replace the name of the repository in [index.xml](/index.xml) when using this template.
This will be the name shown in ReaPack.

```xml
<index version="1" name="Name of your repository here">
```
## linking is key
copy this and add to your reapack repositorys
```
https://github.com/D34dmeat/JSFX-Reapack/raw/master/index.xml
```




Each package file is expected to begin with a metadata header.
See [Packaging Documentation](https://github.com/cfillion/reapack-index/wiki/Packaging-Documentation) on reapack-index's wiki.

The URL to import in ReaPack is [https://github.com/`<your username>`/`<repository name>`/raw/master/index.xml](https://github.com/D34dmeat/JSFX-Reapack/raw/master/index.xml).
