# jamdict_data (EdwardCoventry fork)

This repository is a fork of the original `jamdict_data` project:
https://github.com/neocl/jamdict_data

## Fork changes

- Merged fix from David Brown (`dbrwn`) commit:
  `a1087fbefb332344cd1433e62c18c44b22e1b8dd`
  - Commit message: `unlink zipped database after it is closed`
  - Effect: improves cleanup behavior around the compressed DB file during install/unpack flow.

## Notes

- Dictionary source/license remains with EDRDG dictionary files and upstream `jamdict_data` project terms.
- SQLAlchemy 2.x compatibility fixes are not in this fork because that issue comes from `cjklib` integration in the consuming app, not from `jamdict_data` itself.
