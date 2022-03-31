# replaygain-per-directory
Adds ReplayGain tags to files in each subdirectory of a given directory.

To run the script, execute it with the syntax `addrg /path/to/music`

Requires `metaflac` and `mp3gain` to properly calculate and add tags.

Currently only works with flac and mp3 files, because I'm not aware of similar programs for other audio formats. MP3 ReplayGain data is set to write to IDEv3 tags, rather than APE 2.
