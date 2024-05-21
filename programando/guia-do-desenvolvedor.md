---
description: >-
  Este guia é direcionado aqueles que pretendem criar scripts usando nosso core.
  Seguindo estes princípios, as chances de seus scripts quebrarem no futuro é
  pequena.
---

# Guia do desenvolvedor

## Não acesse as tabelas do core diretamente

Isso poderá fazer com que seu script deixe de funcionar, se alteramos o banco de dados no futuro. Se os dados que você precisa não puderem ser lidos/escritos usando uma função, abra uma \`issue\` no [GitHub ](https://github.com/mri-Qbox-Brasil)para que possamos ajustar para todos.

## Não modifique o código do core

Isso pode dificultar atualizaçoes no future, e também criar confusão quando precisar debugar problemas que podem ou não ter sido causados pelas alterações.

## Não use funções/eventos obsoletos

Eles serão removidos no futuro e portanto, deixarão de funcionar.
