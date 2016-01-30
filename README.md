# How to ...

1. Try installing with [this approach](tarbell.readthedocs.org/en/latest/create.html#install-an-existing-project-with-tarbell-install-repository-url).
1. Run `tarbell generate [name-of-build-directory]`. Note: Tarbell seems to prefer build directory names that start with an underscore, so
```bash
$ tarbell generate _output
```
1. If the `_output` directory exists, it'll ask you if you want to overwrite. Yes, you do.
1. Open the `_output/index.html` file. Copy that into the `WebEmbed` area of `web.sp.signing_day_list.0129`. Save. View.
