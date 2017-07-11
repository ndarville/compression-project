To update `data.yml`, click **[Edit][]** on it (or this link).

If you don’t know how the YAML syntax works, just [open an issue][issue] instead.

These fields are required:

field     | type
----------|--------
name      | `str`
source    | `[str]`
confirmed | `bool`
updated   | `date`

All supported fields can be found in the schema file, [linter.py][linter].

If you have a suggestion for a site to include, submit it for `todo.yml` the say you would `data.yml`.


[edit]: https://github.com/ndarville/compression-project/edit/master/data.yml
[issue]: https://github.com/ndarville/compression-project/issues/new
[linter]: https://github.com/ndarville/compression-project/blob/master/ci/linter.yml
