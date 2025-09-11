# Mineração de Repositórios de Software

## Objetivo

Desenvolver uma ferramenta de linha de comando que identifique problemas de manutenção de software por meio da mineração de repositórios

## Decisões Importantes

- Definição do problema

- Tecnologias utilizadas

- Origem dos dados: Git ou GitHub?

- Artefatos analisados: código, commits, issues, pull requests, branches, CI/CD etc.

- Apresentação dos resultados: métricas, visualizações, etc.

## Tools

### Git
- pydriller: Python Framework to analyse Git repositories (https://github.com/ishepard/pydriller)
- GitPython: Python library used to interact with Git repositories (https://github.com/gitpython-developers/GitPython)

### GitHub
- PyGithub: Typed interactions with the GitHub API (https://github.com/PyGithub/PyGithub)
- GitHub API: https://docs.github.com/en/rest: 
- GitHub Search tool (GHS): https://seart-ghs.si.usi.ch

### Building Command Line Interfaces (CLIs)

- typer: https://github.com/fastapi/typer
- click: https://github.com/pallets/click
- python-fire: https://github.com/google/python-fire
- argparse: https://docs.python.org/3/library/argparse.html

### Parsers

- tree-sitter: multilanguage parsing library (https://github.com/tree-sitter/tree-sitter)
- python ast: Python parsing library (https://docs.python.org/3/library/ast.html)

### Misc

- pmd: An extensible multilanguage static code analyzer (https://github.com/pmd/pmd)
- lizard: Code complexity analyser (https://github.com/terryyin/lizard)
- bandit: Find common security issues in Python code (https://github.com/PyCQA/bandit)
- awesome-msr: https://github.com/dspinellis/awesome-msr
