+++
draft = true
date = "2018-01-01T23:54:04-02:00"
title = "2017 em livros"
description = "resenha dos livros que li nesse ano"
+++

2017 foi um ano de muitas mudanças, troquei de emprego, mudei o status de relacionamento (fiquei
noivo \o/), casa, fundei uma empresa e mais algumas coisas.  Porém algo que não mudou foi meu habito de
ler toda noite antes de dormir, algo que construi a 3 anos atrás e consigo
manter quase 100%. Com isso consegui ler 12 livros, sendo 3 tecnicos.

## Livros Tecnicos

1) [Big Data: Principles and best practices of scalable realtime data systems](https://www.amazon.com/Big-Data-Principles-practices-scalable/dp/1617290343)

![livro big data](/images/big-data.jpg)

No final do ano de 2016 eu entrei para o time de data analytics da globo.com e
esse livro me ajudou a entender melhor a infraestrutura da area e como era o
fluxo de dados.

![lambda architecure](/images/lambda-architecture.png)

Nesse livro o autor apresenta a arquitetura lambda para bigdata, que consiste em 3 layers: batch, speed e serving.
No layer batch temos processamento de grandes quantidade de dados, que podem durar até horas.
No layer speed temos processamento em real-time, geralmente numa janela pequena de tempo (dados do ultimo minuto, por exemplo).
E no layer serving temos o acesso externo ao dado processado no layers anteriores, onde os usuarios finais podem fazer queries.

2) [Redis Essentials](https://www.amazon.com.br/Redis-Essentials-Maxwell-Dayvson-Silva-ebook/dp/B00ZXFCFLO/ref=sr_1_1?ie=UTF8&qid=1516965096&sr=8-1&keywords=redis+essentials)

Logo depois de eu entrar no time de data analytics, recebemos a missão de
salvar um software legado que fazia o realtime analytics de algumas paginas da
globo.com. Esse software foi feito em 2011 e por isso utilizava ferramentas
muito rudimentares, fazendo parse de log de um server apache, salvando no redis e mysql.

![livro redis essentials](/images/redis-essentials.jpg)

Depois de 2 semanas tentado identificar o erro no codigo sem sucesso, resolvemos
mudar a arquitetura para algo mais moderno, usando kafka, spark streaming e redis.

E esse livro foi essencial para completar a tarefa. Ele mostra as principais
funções do redis de forma pratica, com exemplos relevantes e explicações
incriveis!

3) [Programming in Scala](https://www.amazon.com.br/Programming-Scala-Comprehensive-Step-Step-ebook/dp/B01EX49FOU/ref=sr_1_2?s=digital-text&ie=UTF8&qid=1516965499&sr=1-2&keywords=scala+programming)

![livro redis essentials](/images/programming-in-scala.jpg)

Na area de big data, uma das principais linguagens é o Scala, por ser rapido, fáci de escrever e principalmente porque ~~não é java~~**.
Esse livro apresenta muito bem a linguagem e mostra tudo que é possivel fazer com ela.

## Outras leituras

1) Fantasia

2) Ficção Cientifica

3) Neil Gaiman

