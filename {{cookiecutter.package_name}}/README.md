# {{cookiecutter.package_name}}

[![License {{cookiecutter.license}}](https://img.shields.io/pypi/l/{{cookiecutter.package_name}}.svg?color=green)](https://github.com/{{cookiecutter.github_username_or_organization}}/{{cookiecutter.package_name}}/raw/main/LICENSE)
[![PyPI](https://img.shields.io/pypi/v/{{cookiecutter.package_name}}.svg?color=green)](https://pypi.org/project/{{cookiecutter.package_name}})
[![Python Version](https://img.shields.io/pypi/pyversions/{{cookiecutter.package_name}}.svg?color=green)](https://python.org)
[![codecov](https://codecov.io/gh/{{cookiecutter.github_username_or_organization}}/{{cookiecutter.package_name}}/branch/main/graph/badge.svg)](https://codecov.io/gh/{{cookiecutter.github_username_or_organization}}/{{cookiecutter.package_name}})


{{cookiecutter.short_description}}

----------------------------------

This [KietzmannLab] package was generated with [Cookiecutter] using [@KietzmannLab]'s [cookiecutter-template] template.



## Installation

You can install `{{cookiecutter.package_name}}` via [pip]:

    pip install {{cookiecutter.package_name}}


{% if cookiecutter.github_repository_url != 'provide later' %}
To install latest development version :

    pip install git+https://github.com/{{cookiecutter.github_username_or_organization}}/{{cookiecutter.package_name}}.git
{% endif %}

## Contributing

Contributions are very welcome. Tests can be run with [tox], please ensure
the coverage at least stays the same before you submit a pull request.

## License

Distributed under the terms of the [{{cookiecutter.license}}] license,
"{{cookiecutter.package_name}}" is free and open source software

## Issues

If you encounter any problems, please [file an issue] along with a detailed description.


[pip]: https://pypi.org/project/pip/
[KietzmannLab]: https://github.com/KietzmannLab/
[Cookiecutter]: https://github.com/audreyr/cookiecutter
[@KietzmannLab]: https://github.com/KietzmannLab/
[MIT]: http://opensource.org/licenses/MIT
[BSD-3]: http://opensource.org/licenses/BSD-3-Clause
[GNU GPL v3.0]: http://www.gnu.org/licenses/gpl-3.0.txt
[GNU LGPL v3.0]: http://www.gnu.org/licenses/lgpl-3.0.txt
[Apache Software License 2.0]: http://www.apache.org/licenses/LICENSE-2.0
[Mozilla Public License 2.0]: https://www.mozilla.org/media/MPL/2.0/index.txt
[cookiecutter-template]: https://github.com/KietzmannLab/cookiecutter-kietzmannlab-template
{% if cookiecutter.github_repository_url != 'provide later' %}
[file an issue]: https://github.com/{{cookiecutter.github_username_or_organization}}/{{cookiecutter.package_name}}/issues
{% endif %}
[KietzmannLab]: https://github.com/KietzmannLab/
[tox]: https://tox.readthedocs.io/en/latest/
[pip]: https://pypi.org/project/pip/
[PyPI]: https://pypi.org/
