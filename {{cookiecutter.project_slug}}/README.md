# {{ cookiecutter.project_name }}

{{ cookiecutter.project_short_description }}

## Quickstart

```bash
git clone git@github.com:simplebet/{{cookiecutter.project_name}}.git
cd {{cookiecutter.project_name}}
poetry install
make test

{% if 'no' not in cookiecutter.command_line_interface|lower %}
poetry run {{cookiecutter.project_name}}
{% endif %}
```

## Credits

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
