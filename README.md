The Compression Project
=======================
This project was spawned by a minor series of [tweets][] about the opaque and seemingly arbitrary compression of uploaded media.

Ideally, this will encourage people to always save copies of their own media before uploading them, and for sites to be transparent about *how* and *when* they compress users’ uploads.

The easiest approach would be either a `compression.txt` similar to `robots.txt` or something in a more standardized format like `compression.json` or `.yml`.

Contributing
------------
To update `_data/sites.yml`, click **[Edit][]** on it (or this link).

If you don’t know how the YAML syntax works, just [open an issue][issue] instead.

The mandatory fields to include are currently

field     | type
----------|--------
name      | `str`
source    | `[str]`
confirmed | `bool`
updated   | `date`

All supported fields can be found in the schema file, [linter.py][linter].

I have no idea which fields I will end up using, so by all means let me know what makes sense and what doesn’t.

Future sites
------------
If you have a suggestion for a site to include, [submit it for `_data/todo.yml`][edit-todo] just as you would `sites.yml`.


[tweets]: https://twitter.com/pessimism/status/884018396047781888
[edit]: https://github.com/ndarville/compression-project/edit/master/_data/sites.yml
[issue]: https://github.com/ndarville/compression-project/issues/new
[linter]: https://github.com/ndarville/compression-project/blob/master/ci/linter.yml
[edit-todo]: https://github.com/ndarville/compression-project/edit/master/_data/todo.yml
