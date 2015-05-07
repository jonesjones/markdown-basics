# `Marcações básicas`

Marcações permitem que você escreva usando a forma fácil-de-escrever, formando textos simples que em seguida as converte para HTML válidos para serem visualizados no GitHub.

##Escrita básica

**Parágrafos**

Parágrafos em marcação são apenas uma ou mais linhas de um texto seguidas consecutivamente de uma ou mais linhas em branco.
```
Em 2 de julho, um alien entrou na órbita da terra e implantou vários pires- em 3 de julho Os Cavaleiros da Noite, um esquadrão de corpos da Marinha F/A-18, participaram. de uma invasão em um destroyer próximo à cidade de Los Angeles.
```

###Cabeçalhos

Você pode criar um cabeçalho adicionando um ou mais ```#``` símbolos antes do cabeçalho do seu texto. O número do # que você usa determina o cabeçalho.

```
#O maior cabeçalho (uma <h1> etiqueta)
##O segundo maior cabeçalho (uma <h2> etiqueta)
...
######O sexto maior cabeçalho (uma <h6> etiqueta)
```

######Citações em bloco

Você pode indicar citações em bloco com um ```>```.
```
Nas palavras de Abraham Lincoln:
>Perdão meu amigo.
```

###Estilo do texto

Você pode colocar o texto em **negrito** ou *itálico*

```
*Esse texto está em itálico*
**esse texto está em negrito**
```


Ambos negrito e itálico podem usar um ```*``` ou um ```_``` pelo texto para o estilo. Esse permite que você combine negrito com itálico se precisar.

```
** Todo o mundo _deve_ participar da reunião hoje às 5 horas. **
```

##Listas

###Listas não ordenadas

Você pode fazer uma lista não ordenada procedendo a lista de itens com ou um ```*``` ou um ```-```  .
```
*item
*item
*item

-item
-item
-item
```

###Listas ordenadas

Você pode criar uma lista ordenada procedendo a listas com ```*``` ou ```-```
```
1.	Item. 1
2.	Item. 2
3.	Item. 3
```

###Listas alinhadas

Você pode criar listas alinhadas recuando da lista pelos espaços.
```
1.	Item 1
 1. Um corolário acima do item.
 2. Ainda nenhum ponto a considerar.

2. Item 2

* Um corolário não precisa ser solicitado
* Isso é recortado por quatro espaços, porque dois espaços é menor que o item acima.
* Você tem que considerar a nova lista
3. Item 3
```

##`Códigos de formatação`

Use crases sozinhas (`) para formatar um texto especial. Tudo que esta em crase fica como está, sem uma formatação especial

```Aqui uma ideia: Porque nós não pegamos o `ProjetoSuperior` e o transformamos num `**ProjetoRazoável`.```

###Múltiplas linhas

Você pode usar as crases triplicadas (```) para formatar o texto com o seu bloco distinto.

Confira esse programa limpo que eu fiz:

```
X = 0
X = 2 + 2  
O que é x
``` 

##`Links`

Você pode criar uma ligação em linha por envolvimento link texto entre colchetes (```[ ]```), e, em seguida, envolver a ligação entre parênteses (```( )```).
Por exemplo, para criar um hiperlink para www.github.com, com um texto de link que diz, Visita GitHub !, você escreveria isso em Markdown: [Visite GitHub!] (Www.github.com).

