# Projeto de Componentes

**Versão:** 0.0.2

Este projeto é uma biblioteca de componentes reutilizáveis para aplicações React. Utiliza **Storybook** para desenvolvimento e teste isolado dos componentes, **Webpack** para empacotamento dos módulos e **Vite** para um servidor de desenvolvimento rápido.

## Sumário

- [Visão Geral](#visão-geral)
- [Configuração do Projeto](#configuração-do-projeto)
- [Scripts Disponíveis](#scripts-disponíveis)
- [Uso do Storybook](#uso-do-storybook)
- [Uso do Webpack](#uso-do-webpack)
- [Uso do Vite](#uso-do-vite)
- [Dependências](#dependências)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Visão Geral

Este projeto visa criar e gerenciar uma coleção de componentes React reutilizáveis. O **Storybook** permite visualizar e testar os componentes de forma isolada, enquanto o **Webpack** e o **Vite** oferecem suporte para desenvolvimento e empacotamento.

## Configuração do Projeto

Para configurar o projeto, siga as instruções abaixo:

### Como Instalar

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd seu-repositorio
   ```

3. Instale as dependências do projeto:

   ```bash
   npm install
   ```

4. Se necessário, instale as dependências de tipo específicas para Node.js:

   ```bash
   npm install @types/node@latest
   ```

5. Caso enfrente problemas de dependências, você pode usar o seguinte comando:
   ```bash
   npm install --legacy-peer-deps
   ```

### Como Rodar o Projeto com Webpack

1. Para iniciar o servidor de desenvolvimento com Webpack, use:

   ```bash
   npm run start:webpack
   ```

2. Para gerar um build de produção, use:
   ```bash
   npm run build:webpack
   ```

### Como Rodar o Storybook

1. Para iniciar o Storybook, use:

   ```bash
   npm run storybook
   ```

2. O Storybook será iniciado em `http://localhost:6006` por padrão.

### Como Rodar o Vite

1. Para iniciar o servidor de desenvolvimento com Vite, use:

   ```bash
   npm run dev:vite
   ```

2. Para gerar um build de produção com Vite, use:
   ```bash
   npm run build:vite
   ```

## Scripts Disponíveis

- `npm run start:webpack`: Inicia o servidor de desenvolvimento com Webpack.
- `npm run build:webpack`: Gera o build de produção com Webpack.
- `npm run storybook`: Inicia o Storybook para visualização e teste dos componentes.
- `npm run dev:vite`: Inicia o servidor de desenvolvimento com Vite.
- `npm run build:vite`: Gera o build de produção com Vite (opcional).

## Dependências

- **React**: Biblioteca principal para construção de componentes.
- **Storybook**: Ferramenta para desenvolvimento e teste isolado de componentes.
- **Webpack**: Empacotador de módulos para o projeto.
- **Vite**: Ferramenta de desenvolvimento rápido e empacotamento.

## Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do repositório.
2. Crie uma branch para sua feature ou correção de bug:
   ```bash
   git checkout -b minha-feature
   ```
3. Faça commit das suas alterações:
   ```bash
   git commit -am 'Adiciona uma nova feature'
   ```
4. Envie para o repositório remoto:
   ```bash
   git push origin minha-feature
   ```
5. Abra um pull request.
