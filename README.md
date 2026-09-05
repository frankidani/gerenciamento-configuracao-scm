# Gerenciamento de Configuração — Projeto SCM

Este repositório demonstra o fluxo básico de gerenciamento de configuração com Git: criação de artefatos, clonagem de um repositório remoto, alteração local, registro em commit e publicação das mudanças.

## Estrutura

- `src/novo.py`: artefato principal do exemplo.
- `src/nova_funcionalidade.py`: artefato criado durante a evolução do projeto.
- `docs/CHANGELOG.md`: histórico resumido das mudanças.

## Fluxo demonstrado

1. Inicialização do repositório.
2. Criação do primeiro artefato.
3. Clone a partir de um repositório remoto.
4. Alteração de um artefato existente.
5. Criação de um novo artefato.
6. Execução de `git status`, `git add`, `git commit` e `git push`.
7. Verificação do conteúdo atualizado no repositório remoto.

## Execução

```bash
python3 src/novo.py
python3 src/nova_funcionalidade.py
```

## Repositório remoto

A versão publicada está disponível no repositório privado: https://github.com/frankidani/gerenciamento-configuracao-scm

## Observação

O fluxo também mantém um repositório remoto bare local para reprodução independente da atividade. A versão principal foi publicada no GitHub com a branch `main`.
