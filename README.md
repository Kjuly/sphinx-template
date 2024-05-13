# sphinx-template
Sphinx docs template, including automated deployment workflows.

## Structure

Default folder structure in this template:
```sh
/source
    _conf.py  # Shared base config file.

    /en
        _conf.py  # Override config file for "en".
        conf.py   # The final generated config file for "en", which will be updated for each build process.
        ...       #   You don't need to provide it manually.

    /zh-Hans
        _conf.py
        ...
/build
```

Regarding `_conf.py`, please refer to [sphinx-publisher - Share & Override Config File][sphinx-publisher - conf.py] for details.


  [sphinx-publisher - conf.py]: https://github.com/Kjuly/sphinx-publisher?tab=readme-ov-file#share--override-config-file
