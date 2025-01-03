# Instalações necessárias - 02/01/2025

## Node.JS

Será necessário a desinstalação de qualquer versão instalada na máquina local para fazer a instalação novamente com a versão atual.

```bash
node --version 
```

Após a reinstalação do node, iremos verificar a versão do angular.

## Angular

```bash
ng --version
```

Se houver alguma versão do angular instalada e não for a mais recente, será necessário reinstalar a versão do angular.

```bash
npm uninstall @angular/cli -g
```

Agora iremos entrar no site do npm no pacote [Angular](https://npmjs.com/package/@angular/cli) para instalar a ultima versão com a tag `latest`.

```bash
npm install @angular/cli@latest -g
```

>[!IMPORTANT]
>É extremamente importante colocar o `-g` para fazer a instalação do angular de forma global.


## Criação de projeto Angular

Ao criar um projeto Angular, iremos utilizar o comando `ng new` para criar o projeto.
Iremos utilizar a flag `--no-standalone` para criar o arquivo `app.module.ts`.

```bash
ng new nome-do-projeto --no-standalone --style=scss --routing=true --ssr=false
    #stulesheet = scss
    #SSR = false
    #routing = true
```

## VSCode atalhos

1. Para abrir/fechar o terminal do vscode, iremos utilizar o atalho `Ctrl + '` ou `Ctrl + "`.

2. Para abrir/fechar o explorador lateral, iremos utilizar o atalho `Ctrl + B`.

3. Para duplicar uma linha, iremos utilizar o atalho `Alt + Shift + Seta UP/DOWN`.

4. para buscar pelo arquivo palavras iguais, iremos selecionar o texto que desejamos alterar todos de uma vez e segure o atalho `Ctrl + D` e ele vai buscar todas as palavras iguais.

5. Para mostrar o menu do quick fix, iremos utilizar o atalho `Ctrl + .`.

6. Para mostrar os parametros que devemos dclarar na função iremos utilizar o atalho `Ctrl + Shift + Espaço`.


>[!IMPORTANT]
> Desabilitar o salvamento automático para que possamos trabalhar com o DevTools do navegador sem perder as informações do console.

## Extensoes recomendadas

- [Angular Language](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
- [Angular 17 Snippets](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)
- [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Shades of Purple](https://marketplace.visualstudio.com/items?itemName=ahmadawais.shades-of-purple)
- [Ayu Theme](https://marketplace.visualstudio.com/items?itemName=teabyii.ayu)