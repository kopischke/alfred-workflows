# Collected Alfred 2 workflows

Simple workflows for [Alfred version 2][alfred] that do not merit their own repository. Note you need the [Alfred Powerpack][alfred-powerpack] to enable workflows.

## Workflows included

### Refresh Finder

A straightforward port of Söderhavet’s [*Refresh Finder*][refresh-finder] utility to Alfred. Use a hotkey or the “refresh” keyword to force Finder to refresh the file listing in the frontmost window. Alternatively, all Finder windows can be refreshed (via another hotkey, or by holding down `alt` when actioning the keyword).

![Refresh Finder workflow overview](docs/refresh-finder-workflow.png)

### Tag with Tagger

Ali Rantakari’s [*Tagger.app*][tagger] is a fantastic (and free) way to tag files according to the [OpenMeta standard][openmeta]. This workflow adds a hotkey to trigger it, and a file action for Alfred’s file browser (using the `tag` keyword).

![Tag with Tagger screenshot of tag window](docs/tag-with-tagger-window.png)

### Disk space

An expanded version of [Florian Pellet’s disk space workflow](http://www.alfredforum.com/topic/678-check-available-disk-space/?hl=%2Bdisk+%2Bspace ). It has a friendlier display (including correct drive icons), handles volumes with spaces in their names, displays the correct name of the system drive and offers actions on the drives (Reveal in Finder by default, Browse in Alfred with the `fn` modifier).

![Disk space screenshot of feedback display](docs/disk-space-feedback.png)

## Google Translate

A version of [Florian Pellet’s Translation workflow](http://www.alfredforum.com/topic/120-google-translate-workflow/ ) that handles international characters correctly, both as input and output, and adds a Paste in foreground application action (with the `Cmd` modifier). It’s also more easily extensible to other languages as the logic is in a central script: adding another language is a simple matter of adding a script filter running

    ./translate '<language code>'  '<language name>' "{query}" 

in `bash` (double quotes and escape variables need to be escaped).

![Google translate screenshot of feedback display](docs/google-translate-feedback.png)

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
