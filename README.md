# Dicas para marcações em Markdown

Aproveitando o conteúdo do curso Git e GitHub (Curso em Vídeo)
Vou Testar as marcações em Markdown.

Caso lhe seja útil, fique a vontade.

## Formatação da Fonte 

* em negrito 2** **teste** ou __teste__
* em itálico 1*     *teste* ou _teste_
* riscado 2~       ~~teste~~
* Podemos misturar  com 2** de negrito e 1* de itálico ***teste***

## Linhas

* linha com 3 _
___
* linha  com 3*  
***


## Tamanho das Fontes
* Tamanho 1#   
 # Título




* Tamanho 2##   
## Titulo




* Tamanho 3###    
### Título



## Listas numeradas 

* (digitando 1.  e dando Enter, as demais manterão a sequencia)
1. Teste
2.  Teste
3.  Teste
4.  Teste

* (digitando 1. e continuar digitando 1. nas demais)

1.
1.
1.

* (criando sub itens com 3 espaços no próximo item)

1.
2.
   1.
   1.

## Lista demarcada 
(com *, e para sub itens 3 espaços no próximo item)
* teste
* teste
   *teste
*teste

## Lista de Tarefas
( espaço - espaço [ espaço] descrição da tarefa)
e quando realizar a tarefa (espaço - espaço [X] descrição da tarefa)
 - [ ] Criar a página principal
 - [ ] Criar a página da loja
 - [X] finalizar a reunião com o cliente
 - [ ] receber pagamento

## Colocando imagens
Arrastar a imagem para a linha descrita abaixo:

(Anexe arquivos arrastando e soltando, selecionando ou colando-os)
(Attach files by dragging & dropping, selecting or pasting them)

![octodex-x-man](https://user-images.githubusercontent.com/80476746/123532308-7a6f4e80-d6e2-11eb-8db9-27f7cb74275e.jpg)

## Criando link
(Clique no ícone de 2 elos de corrente)
preencher [ ] com a descrição ou título do link
preencher { } com o link escolhido
[Meu perfil no GitHub](https://github.com/Eins10Week)

## Tabela
Digitar os nomes das colunas e separa-las com | pipies      Num | Nome | Nota
Na linha debaixo 3- | 3- | 3-       ---|---|---
Nas demais linhas preencher com os valores e nomes, separando-os com | pipes também   1 | João | 7,5
(Observação: para formar a tabela precisa ser uma linha embaixo da outra ser interferência)

*Exemplo:*
Num | Nome | Nota
---|---|---
1 | João | 7,5
2 | José | 10
3 | Cráudia | 2,5

## Escrever um comando
 digita o texto entre uma crase (`) 
 
exemplo: 

não estou conseguindo desenvolver com o comando document.getElementById() da linguagem JavaScript.


não estou conseguindo desenvolver com o comando `document.getElementById()` da linguagem JavaScript.

## Escrever parte de um programa
 digita o texto entre 3 crase (```) 
exemplo:
```
num = int(input('Digite um valor: ')
if num % 2 = = 0:
    print(f'O valor {num} é PAR')
else:
    print(f'O valor {num} é ÍMPAR')
```

## Parte de um programa
Colando o print de uma parte de um programa da mesma maneira que colamos uma imagem anteriormente.
![dúvida](https://user-images.githubusercontent.com/80476746/123533174-88749d80-d6e9-11eb-9475-b72d7f047c22.PNG)


## Colocar emojis
digitar : já vai aparecer algumas opções,
ai pode apenas completar com o nome do emoji

exemplo:  :smile:   smile
                 :hand:  hand

acessando o link para consultar base de emojis
[Repositório do Git Hub da ikatyang com listagem dos nomes dos emojis](https://github.com/ikatyang/emoji-cheat-sheet)

## Colocar emojis no título
Copiar o emoji na lista de emojis no site Emojipedia

[Site do Emojipedia](https://emojipedia.org/)
e colar nos títulos

😆 **Título** 😆

## Fazer citações e marcações de pessoas
digitar @ mais o nome da pessoa

exemplo: conforme a citação do @Eins10Week 

assim o nome dele ficará disponível em link

## Para responder a um comentário específico
Clique em ... (reticências) no canto direito do comentário e em "quote reply".
Automaticamente iniciará uma frase com o sinal > (maior) que refere-se a reply, ou a resposta citada.
Aí, é só comentar.

Ou apenas iniciar a resposta com o sinal de maior > mais o texto referido, e responder.
