# Curso desenvolvimento Frontend: Zero ao Júnior

Faz algum tempo que desejo criar um curso de desenvolvimento frontend, se vou conseguir realmente não sei mas a jornada começa nesse repositório.
Eu ficaria feliz se conseguisse, através de um curso simples, permitir que pessoas interessadas em desenvolvimento frontend saíssem do interesse para sua primeira vaga de trabalho na área. Para mim ainda seria bom aprender mais sobre como ensinar e aprender.

Para isso esse curso tenta responder:

* Que tipo de conhecimento e experiências são essenciais para desenvolvedores e desenvolvedoras frontend em começo de carreira?
* Que tipo de conhecimento e experiências são essenciais para desenvolvedores e desenvolvedoras no geral?
* **Bônus:** Que informações teriam me ajudado quando iniciei minha carreira?

## O mapa do frontend

O site roadmap.sh fornece um bom mapa dos [assuntos relacionados a frontend](https://roadmap.sh/frontend).
Esse é um mapa bem completo e ainda assim não compreende todo o universo de frontend, mesmo assim é um bom ponto de partida para selecionar tópicos para criação de um mapa mais focado no início de carreira.

Esse curso não pretende abordar todos esses tópicos, mas somente aqueles tópicos que compreendem o currículo básico da profissão.

## Estrutura, estilo e comportamento

A pessoa profissional frontend não é aquela que sabe React, jQuery ou Angular. 
A pessoa profissional frontend é aquela que desenvolve projetos de interface usando tecnologias de frontend que podem ser divididas entre estrutura, estilo e comportamento.

Quando estamos falando de projetos que rodam no navegador web do usuário, podemos dizer que tipicamente estrutura é HTML, estilo é CSS e comportamento é JavaScript.

## Estrutura: HTML
<img src="https://openclipart.org/image/400px/175132" width="200">

```HTML
<html>
  <head>
    <title>Minha primeira página</title>
  </head>
  <body>
    <p class='paragrafo'>Oi, faço parte de uma página HTML</p>
  </body>
</html>
```

---

* Escrever HTML é estruturar o código de uma página de acordo com uma especificação
* O que o HTML especifica é um conjunto de tags
* A tag é uma marcação individual com algum significado que pode ser visto ou não pelo usuário
* HTML é uma especificação: um acordo comum seguido por navegadores e robôs de busca, por exemplo
* A especificação HTML evolui ao longo do tempo: `<marquee>` caiu em desuso, mas já podemos usar a tag `<video>`
* O HTML é uma linguagem de marcação e não uma linguagem de programação
* Um bom HTML precisa seguir boas práticas

<!-- fim da lista -->
A seguir falaremos de: estilo e comportamento

## Estilo: CSS
<img src="https://openclipart.org/image/400px/174634" width="200">

```CSS
.paragrafo {
    font-size: 1em;	
}
```

---

* Escrever CSS é aplicar estilo a uma estrutura criada com HTML de acordo com uma especificação
* O CSS é uma composição de seletores e regras
* Cada seletor define a qual trecho de HTML uma série de regras estará associada
* CSS é uma especificação: um acordo comum seguido por navegadores e robôs de busca, por exemplo
* As regras de estilo que o CSS especifica caracaterísticas como: cores, fontes, diagramação e muito mais
* A especificação do CSS também evolui com o tempo
* Um bom CSS precisa seguir boas práticas

## Comportamento: JavaScript
<img src="https://openclipart.org/image/400px/174987" width="200">

```JavaScript
window.alert('Isso é JavaScript');
```
---

* Escrever JavaScript para frontend é adicionar comportamento a uma estrutura HTML
* O JavaScript é uma linguagem de programação que pode ser interpretada por navegadores
* O JavaScript é uma composição de blocos de lógica
* Todos os principais navegadores mobile e desktop são capazes de interpretar JavaScript
* O JavaScript também é uma especificação, essa especificação é usada por interpretadores
* Diferentes navegadores JavaScript podem usar diferentes versões de diferentes interpretadores
* O JavaScript que roda no navegador é incrementado com regras para interagir com o navegador
* A especificação JavaScript também evolui com o tempo
* Um bom JavaScript precisa seguir boas práticas

## Boas práticas

<img src="https://openclipart.org/image/400px/174110" width="200">

> "Sempre que você for fazer um bolo que leve ovos na receita, peneire as gemas antes. Isso evitará que o bolo fique com cheiro de ovo."

---

* HTML, CSS e JS seguem especificações
* Essas especificações são abertas e proporcionam um alto nível de liberdade para quem as utiliza
* Com o tempo e a colaboração a comunidade de profissionais frontend cria conjuntos de boas práticas
* Seguir uma especificação permite que o código seja entendido por máquinas
* Seguir uma boa prática facilita que o código seja entendido por humanos
* Com a experiência, um bom código consegue combinar diferentes boas práticas de forma coesa
* As boas práticas incluem regras de formatação, nomeação de variáveis, adesão a padrões de projeto e mais
* Um projeto reúne um conjunto de boas práticas que precisa ser acordado por todos que o mantém
* Aderir a boas práticas é saber usar bem as especificações
