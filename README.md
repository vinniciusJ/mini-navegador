# Simulador de navegador com ElectronJS

## Objetivo

Usar a tecnologia ElectronJS para simular um mini navegador para usar no processo de desenvolvimento web

## Tecnologias

As tecnologias usadas foram:

* [NodeJS][node_url]
* [ElectronJS][electron_url]

## Como funciona

No arquivo `config.js` você pode adicionar qual URL do arquivo que deseja visualizar.

__Exemplo__:

```js
    module.exports = {
        url: "https://nodejs.org/en/download/"
    }
```

### Pré-requisitos

Para poder executar o simulador de navegador necessita ter o `NodeJS` instalado em sua máquina

### Como executar

Para executar basta usar o seguinde comando no terminal:

```bash
$ npm start
```
## Imagem

![Mini navegador observando a página do NodeJS][img_url]


[node_url]: https://nodejs.org/en/download/ "Instalar NodeJS"
[electron_url]: https://www.electronjs.org/docs/tutorial/first-app "ElectronJS Docs"
[img_url]: img.png "NodeJS Download"
