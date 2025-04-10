# Microfront class USP

## Bundlers:

- Ferramenta que automatiza a instalação, atualização e remoção de bibliotecas e dependências.
- Facilita a gestão de versões e compatibilidade entre pacotes.

## Multirepo:

● Cada projeto em repositório separado
● Independência total dos projetos
● Facilidade de gerenciamento individual
● Dificuldade para sincronizar dependências e versões


## Monorepo
● Múltiplos projetos dentro de um único repositório
● Centralização e compartilhamento facilitados
● Fácil gerenciamento de versões


### Monorepo: desafios
● Necessidade de ferramentas específicas para lidar com dependências compartilhadas
● Evitar duplicação e conflitos entre múltiplos projetos 
● Simplificar instalação e manutenção de pacotes dentro do mesmo repositório

## Workspaces
● Funcionalidade para gerenciar múltiplos pacotes em um único repositório (monorepo)
● Disponível em npm (v7+), Yarn e pnpm
● Evita duplicidade de dependências e facilita o desenvolvimento modular


## Single SPA
● Open source
● Orquestrador
● vários SPAs menores dentro de um SPA principal
● Framework-agnóstico
● Gerenciamento de ciclo de vida: single-spa fornece hooks para bootstrap, mount e unmount
● Roteamento centralizado
● Isolamento com possibilidade de comunicação


## Native Federation
● Module Federation do Webpack 5
● Elimina dependência de ferramentas de build
● Module loader em runtime
● Host e Remotos
● Carregamento dinâmico
● Compartilhamento de dependências
● Isolamento e independência
● Federação via ESM nativo


## Piral
● Open source
● Oferece uma solução completa
● Pequenos módulos plugin (chamados pilets)
● App Shell
● Feed Service
● Pilet
● APIs do Piral
