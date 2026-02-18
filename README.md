# Ansible Lab
This repo houses ansible playbooks and roles for testing and learning purposes.

## Prerequisites
- [pre-commit](https://pre-commit.com/) >= 4.2.0
- [python3](https://www.python.org/downloads/) >= 3.11+
- [pip3](https://pypi.org/project/pip/) >= 26.0.1
- [ansible](https://docs.ansible.com/projects/ansible/latest/installation_guide/installation_distros.html) >= 1.25.0

## Repo Layout
At a high level, these folders make up the `github.com/oneanupam/ansible-lab` repository.

- [`.github/`](./.github) - This folder contains the codeowners, pull request template and github action yaml files.
- [`.vscode/`](./.vscode) - It contains project-specific settings and configurations to customize how VS Code behaves for the workspace.
- [`docs/`](./docs) - This folder contains the documentations related to the repository.
- [`.pre-commit-config.yaml`](.pre-commit-config.yaml) - This file contains the plugin configuration for pre-commit.
- [`.editorconfig`](.editorconfig) - This file has the configuration for the editorconfig plugin.

## How to run pre-commit
Run the below commnad from the git repo root to set up the git hook scripts into your git hooks. It will be installed at .git/hooks/pre-commit

```bash
pre-commit install
```

now pre-commit will run automatically on git commit. Usually, it runs only for the changed files. Its good to run the hooks against all the files when adding new hooks. To manually run all pre-commit hooks on a repo, use below -

```bash
# to run hooks on all files
pre-commit run --all-files

# to run individual hook
pre-commit run <hook_id>
```

Once you have pre-commit installed, adding pre-commit plugins to your project is done with the .pre-commit-config.yaml configuration file. You can generate a very basic configuration using `pre-commit sample-config`. Every time you clone a project using pre-commit running pre-commit install should always be the first thing you do.

## How to run ansible playbook


## Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements or new suggestions. Read the [contributing.md](CONTRIBUTING.md) before starting.

## License
This project is licensed under the [MIT License](LICENSE).
