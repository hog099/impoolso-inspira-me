# Impoolso Inspira-me

Bem-vindo ao repositório **Impoolso Inspira-me**! Este projeto é dedicado a compartilhar **frases inspiradoras** e seus respectivos autores em um formato JSON. Acreditamos que palavras de sabedoria podem motivar e elevar o espírito, e queremos tornar essas citações acessíveis a todos.

## Estrutura do Projeto

O principal arquivo deste repositório é o `quotes.json`, que contém uma coleção de frases inspiradoras. Cada entrada no JSON segue a estrutura abaixo:

```js
{
"author": "Duke Ellington",
"phrase": "Os problemas são oportunidades para se mostrar o que sabe."
}
```


## Como Usar

Para utilizar as frases em seus projetos, você pode fazer o download do arquivo `quotes.json` e carregá-lo em sua aplicação. Aqui está um exemplo simples de como fazer isso usando JavaScript:

```js
fetch('https://raw.githubusercontent.com/hog099/impoolso-inspira-me/main/quotes.json')
.then(response => response.json())
.then(data => {
data.forEach(quote => {
console.log(${quote.phrase} - ${quote.author});
});
})
.catch(error => {
console.error('Erro ao buscar as citações:', error);
});

```
---

Esperamos que você encontre inspiração nas palavras compartilhadas aqui!
