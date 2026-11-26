# AI safety commons: the commons

This repository is the commons itself: its public log and its content. It
holds no code. Nothing here is ever run.

- `log/` holds every record, one file each, in order. It is the only authority.
- `content/` holds what the commons has published, each file named by its
  fingerprint.

Work that is not decided yet, sealed verdicts, and content that was withheld
or hidden are not kept on the main branch.

To read it, use a checkout of the commons' code and point it here:

    python3 commons.py --root /path/to/this/folder verify
    python3 commons.py --root /path/to/this/folder status

Only the clerk pushes to the main branch. The code's README explains how to
contribute.
