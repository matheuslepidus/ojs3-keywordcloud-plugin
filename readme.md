# Keyword Cloud Block Plugin
A sidebar block plugin for [Open Journal Systems](https://github.com/pkp/ojs) and [Open Monograph Press](https://github.com/pkp/omp) which displays a tag cloud of keywords.

![](snapshot.gif)

## About
This plugin creates an additional sidebar block. When added to a sidebar, it displays a tag cloud of keywords of articles.

## License
This plugin is licensed under the GNU General Public License v2. See the file
COPYING for the complete terms of this license.

## Install
 * Copy the release source or unpack the release package into the OJS i.e. OMP plugins/blocks/KeywordCloud/ folder.
 * Run `php tools/upgrade.php upgrade` from the OJS i.e. OMP folder to update shemas.
 * Go to Settings -> Website -> Plugins -> Block Plugins -> KeywordCloud Plugin and enable the plugin.

## Compatibility
This plugin is compatible with OJS 3.1.x and OMP 1.2.x.