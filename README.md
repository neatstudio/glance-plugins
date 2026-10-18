# glance-plugins

Index of known plugins for the [glance](https://github.com/neatstudio/glance)
hub. The hub reads `index.json` (cached for an hour) so a plugin can be
installed by its short name.

To list a plugin: open a pull request adding an entry with `id`, `kind`,
`name`, `repo` (`github:owner/repo`), `ref` (a tag), `hub_api` and the
`permissions` it declares. `verified: true` means a maintainer ran
`check_plugin.py` at that ref and read the code.
