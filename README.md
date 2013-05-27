# Collected Alfred 2 workflows

Simple workflows for [Alfred version 2][alfred] that do not merit their own repository. Note you need the [Alfred Powerpack][alfred-powerpack] to enable workflows.

## Workflows included

### Refresh Finder

A straightforward port of Söderhavet’s [*Refresh Finder*][refresh-finder] utility to Alfred. Use a hotkey or the “refresh” keyword to force Finder to refresh the file listing in the frontmost window. Alternatively, all Finder windows can be refreshed (via another hotkey, or by holding down `alt` when actioning the keyword).

![Refresh Finder workflow overview](docs/refresh-finder-workflow.png)

### Tag with Tagger

Ali Rantakari’s [*Tagger.app*][tagger] to is a fantastic (and free) way to tag files according to the [OpenMeta standard][openmeta]. This workflow adds a hotkey to trigger it, and a file action for Alfred’s file browser (using the `tag` keyword).

![Tag with Tagger screenshot of tag window](docs/tag-with-tagger-window.png)

## Installing and updating

To install, download the `.alfredworkflow` files from the repo. Updates to new versions can be automated via [Alleyoop][alleyoop]: [install Alleyoop][alleyoop-download] and do `oop`.

## Bugs and support

Please use [the repository’s issues section][issues] to check for known bugs or report new ones.

## License

All workflows licensed under the [WTFPL][wtfpl]. See [LICENSE](./LICENSE) for the full license text.

[alfred]: http://www.alfredapp.com
[alfred-powerpack]: http://www.alfredapp.com/powerpack/
[alleyoop]: http://alfred.daniel.sh
[alleyoop-download]:http://alfred.daniel.sh/Workflows/Alleyoop.alfredworkflow
[issues]: ../../issues
[openmeta]: http://code.google.com/p/openmeta/
[refresh-finder]: http://soderhavet.com/refresh/refresh-finder/
[tagger]: http://hasseg.org/tagger/
[wtfpl]: http://www.wtfpl.net/
