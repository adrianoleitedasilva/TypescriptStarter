# TypeScript Starter

Repositório de estudos pessoais focado nos fundamentos do TypeScript, com anotações organizadas em português e exemplos práticos de código.

## Estrutura do Projeto

```
TypescriptStarter/
├── 0. Notas/
│   ├── 0. TypeScript para Iniciantes/   # Introdução ao TypeScript
│   └── 1. TypeScript Básico/            # Conceitos intermediários
└── 1. TypeScriptStarter/                # Projeto prático
    ├── script.ts
    ├── index.html
    └── tsconfig.json
```

## Conteúdo das Notas

| Módulo                     | Tópicos                                                                                                    |
| -------------------------- | ---------------------------------------------------------------------------------------------------------- |
| TypeScript para Iniciantes | O que é TypeScript, sistema de tipos, type annotation, ferramentas                                         |
| TypeScript Básico          | Annotation vs Inference, primitivos, Union Types, Types vs Interfaces, Arrays, `any`, `null` e `undefined` |

## Compilando

Com o TypeScript instalado globalmente:

```bash
tsc script.ts
```

Ou usando o `tsconfig.json` local:

```bash
tsc
```

## Configuração TypeScript

O projeto usa uma configuração estrita (`strict: true`) com as seguintes opções habilitadas:

- `noUncheckedIndexedAccess` — acesso seguro a índices de arrays
- `exactOptionalPropertyTypes` — propriedades opcionais precisas
- `sourceMap` — mapas de origem para debug
- `declaration` — geração de arquivos `.d.ts`
- `jsx: react-jsx` — suporte a React JSX

## Tecnologias

- [TypeScript](https://www.typescriptlang.org/)
- HTML5
