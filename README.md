![desafio-da-lampada-_online-video-cutter com_](https://github.com/danibenfica/Desafio-da-lampada/assets/103818625/c91b6520-0552-4980-b898-77837dce00d1)

# Desafio da Lâmpada

[Link do projeto online aqui!](https://desafio-da-lampada.vercel.app/)

## Descrição do Projeto

O projeto "Desafio da Lâmpada" consiste em uma página web interativa que simula o controle de uma lâmpada. O objetivo é permitir ao usuário ligar, desligar e quebrar a lâmpada por meio de botões e interações visuais.

## Tecnologias Utilizadas

O projeto utiliza as seguintes tecnologias:

- HTML: Utilizado para criar a estrutura e o conteúdo da página web.
- CSS: Utilizado para aplicar estilos e personalizar a aparência da página.
- JavaScript: Utilizado para adicionar interatividade à página e controlar o comportamento da lâmpada.

## Principais Funções

O projeto possui as seguintes funções JavaScript:

### `estaQuebrada()`

```javascript
function estaQuebrada() {
    return lamp.src.indexOf('quebrada') > -1
}
```

A função `estaQuebrada()` verifica se a lâmpada está quebrada. Ela verifica se a string 'quebrada' está presente no URL da imagem da lâmpada. Caso esteja, retorna `true`; caso contrário, retorna `false`.

### `ligar()`

```javascript
function ligar() {
    if(!estaQuebrada()) {
        lamp.src = 'ligada.svg'
    }
}
```

A função `ligar()` é responsável por ligar a lâmpada. Ela verifica se a lâmpada não está quebrada e, em seguida, altera o URL da imagem da lâmpada para exibir a imagem da lâmpada ligada.

### `desligar()`

```javascript
function desligar() {
    if (!estaQuebrada()){
        lamp.src = 'desligada.svg'
    }
}
```

A função `desligar()` é responsável por desligar a lâmpada. Ela verifica se a lâmpada não está quebrada e, em seguida, altera o URL da imagem da lâmpada para exibir a imagem da lâmpada desligada.

### `quebrar()`

```javascript
function quebrar() {
    lamp.src = 'quebrada.svg'
}
```

A função `quebrar()` é responsável por quebrar a lâmpada. Ela altera o URL da imagem da lâmpada para exibir a imagem da lâmpada quebrada.

## Conclusão

O projeto "Desafio da Lâmpada" demonstra o uso de HTML, CSS e JavaScript para criar uma página web interativa. Ele permite ao usuário ligar, desligar e quebrar a lâmpada por meio de botões e interações visuais. É um projeto perfeito para quem está começando na linguagem para entender melhor a manipulação do DOM e uso de funções!

Qualquer dúvida ou sugestão, pode me contatar! :smile: