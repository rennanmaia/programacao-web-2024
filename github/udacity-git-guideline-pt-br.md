# Guia de eslito de mensagens para commits da Udacity (tradução livre para PT-BR)

[Página principal](../README.md)

## Introdução

Este guia de estilos age como um guia oficial para seguir nos projetos. Deve ser usado durante o desenvolvimento do projeto. Existem muitas opiniões sobre o estilo "ideal" no mundo do desenvolvimento de software. Entretanto, para reduzir a confusão sobre como os estudantes devem seguir, solicito que todos sigam guia de estilo de commits para seus projetos de github enquanto estiverem cursando a disciplina.

## Mensagens de Commit

### Estrutura da mensagem

Uma mensagem de commit consiste de três partes distintas separadas por uma linha em branco: o título, um corpo opcional e um rodapé opcional. O layout se parece com isso:

```
tipo: assunto

corpo

rodapé
```

O título consiste do tipo de mensagem e o assunto.

## O tipo

O tipo é contido no título e pode ser um ou mais desses tipos:

* **feat:** uma nova funcinalidade
* **fix:** a correção de um bug
* **docs:** alteração na documentação
* **style:** formatação, ponto e vírgula faltando, etc; sem alteração de código
* **refactor:** refatoramento de código em produção
* **test:** adiciona tesets, teses de refatoração; sem alteração de código em produção
* **chore:** atualização de tarefas feitas, configuração no gerenciador de pacotes, etc; sem alteração no código em produção

## O assunto

Assuntos não devem ser maiores que 50 caracteres, devem iniciar com letra maiúscula e não deve exceder um período.

Use um tom imperativo para descrever o que o commit faz, não o que ele fez. Por exemplo, use altera; não alterou, nem foi alterado.

## O corpo

Nem todos os commits são complexos o suficiente para ter um corpo, portanto ele é opcional e somente usado quando um commit requer um pouco explicação e contexto. use o corpo para explicar o que e porquê existe aquele commit, não como.

Quando escrever o corpo, é mandatória uma linha em branco entre o título e o corpo e o tamanho de cada linha não deve exceder 72 caracteres.

## O rodapé

O rodapé é opcional e é usado para referenciar IDs de issues rastradas.

## Exemplo de mensagem de commit

```
feat: Resumo alterações em 50 caracteres ou menos

Um texto mais detalhado pode ser descrito aqui, se necessário. 
Deve ser escrito em linhas de até 72 caracters. Em alguns contextos, 
a primeira linha é tratada como o assunto do commit e o resto como 
o corpo. A linha em branco separando o resumo do corpo é crucial 
(a menos que você omita o corpo do commit); várias ferramentas 
como `log`, `shortlog` e `rebase` podem confundir se você colocar 
as duas juntas.

Explique o problema que este commit resolve. Foque no porquê você
está fazendo esta mudança em vez de como (o código explica isso).
Existem efeitos colaterais ou outra consequência não intuitiva
desta alteração? Aqui é o espaço para explicar isso.

Novos parátrafos vem depois de linhas em branco.

 - Marcadores são ok, também.

 - Tipicamente um hífen ou asterístico é usado para um marcador, 
  precedido de um espaço simples, com uma linha em branco entre eles
  mas as concenções podem variar aqui

Se você usa uma issue ou algo do tipo, colo as referências dela no
rodapé como a seguir:

Resolves: #123
See also: #456, #789
```