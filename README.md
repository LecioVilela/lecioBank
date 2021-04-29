# TypeScript + Programação Orientada a Objetos

Neste repositório, estão inseridos arquivos onde, a tela do Front-End, está executando códigos em **Runtime**.

As classes estão em linguagem Typescript e como sabemos ao compilar é traduzido para o JavaScript, linguagem do browser (navegadores).

Sendo assim, temos uma tela para inserir nas negociações, que depois da inseridas não podem ser modificadas. Tudo isso estruturado com:

- Classes
- Atributos
- Orientação a Objetos
- Herança

## Utilizamos a lib jQuery

~~~javascript
npm install @types/jquery@2.0.42 --save-dev
~~~

Dessa forma o intellisense volta a funcionar e o Visual Studio Code nos fornece também, as opções do jQuery, por exemplo, podendo ser feita esta alteração:
~~~javascript
$('form').submit(controller.adiciona.bind(controller)) -> jQuery

document.querySelector('.form')
.addEventListener('submit', controller.adiciona.bind(controller)) -> JavaScript
~~~

![image](https://user-images.githubusercontent.com/76961685/116592515-7ac3b700-a8f6-11eb-8987-04cc7503eec1.png)
