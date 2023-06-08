# Layout file migration tool

This tool yelps to migrate the old layout format (`XML`) to the new one (`YAML`).

The migration is following the best effort strategy.
All characters with movements matching the default layer will be placed under
the default layers. All other cases will be moved under the `hidden` layer.

You might need to manually update the file in order to render extra layers.

For more information on the new file format can be found here:
[https://github.com/flide/8VIM/wiki/Adding-a-new-language](https://github.com/flide/8VIM/wiki/Adding-a-new-language)

## Usage

The tool requires node to be install.

```sh
npm install -g MaethorNaur/8vim-migration
8vim-migration -h
```
