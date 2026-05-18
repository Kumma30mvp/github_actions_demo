# GitHub Actions Demo - Python CI/CD

Este repositorio contiene un laboratorio básico de DevOps usando GitHub Actions para una aplicación Python simple.

## Objetivos

- Crear un workflow de CI/CD con GitHub Actions.
- Ejecutar tests unitarios con pytest.
- Configurar cache para dependencias de pip.
- Generar artefactos de build, coverage, package y documentación.
- Usar outputs entre jobs.
- Simular una etapa posterior de deploy.

## Estructura del proyecto

```text
github_actions_demo/
├── .github/
│   └── workflows/
│       └── devops.yml
├── hello.py
├── tests/
│   └── test_hello.py
├── requirements.txt
├── .gitignore
└── README.md