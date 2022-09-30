# Guia-Markdown

A linguagem __MarkDown__ foi desenvolvida em *2004* por dois caras o **John Gruber** e __Aaron Swartz__.
Ela foi feita basicamente para simplificar o conteúdo e a estruturação de um determinado texto,
o **Markdown** é um sistema de formatação que permite torna a escrita e a leitura mais simples.
Com uma codificação mínima, e também fácil, ela é aparentimente mais "limpa"
e também pode ser convertida para a tão famosa linguagem **HTML**.

Ela, basicamente marca suas modificações nos textos (subtítulos, negrito, itálico etc) apenas utilizando símbolos.
Essa linguagem **Markdown** também pode ser processada em diversos outros programas, com por exemplo o __*Microsoft Word*__ e outros. 

## Algumas marcações com MarkDown

* Para colocar uma frase em negrito basta envelopar o texto com ** ou __

* Para colocar uma frase em itálico basta envelopar o texto com * ou _ 

* Para deixar um texto riscado basta envelopar o texto com ~~

* Para deixar o texto como título basta colocar # nível 1

* Para deixar o texto como título basta colocar ## nível 2

* Para deixar o texto como título basta colocar ### nível 3

* para colocar uma linha horizontal em baixo do texto basta colocar *** ou ___

### Listas

Lista numerada basta colocar 1.

1. teste
1. teste
   1. teste
   1. teste
1. teste
1. teste

Lista demarcada basta colocar * ou -

* teste
* teste
  * teste
  * teste
* teste
* teste

Lista de tarefas basta colocar -[] tarefa concluída coloque -[x]

- [x] tarefa 01
- [ ] tarefa 02
- [x] tarefa 03
- [ ] tarefa 04

## Imagens

Para adicionar uma imagem basta movê-la para o campo digitável
e automaticamente irá criar um link

![img-code](https://user-images.githubusercontent.com/109040443/179379799-35d7ec64-7b2c-432e-8f07-977ed190e854.jpg)

### Links

Para adicionar um link basta colocar **[Acesse meu github] (url)**.

[Acesse meu github](https://github.com/aleanrocha)

### Tabelas

Para utilizar tabelas basta colocar 

**num | nome | nota**

**---|---|---**

**1 | Zezinho | 10**

**2 | aluno | 8**


resultado 

num | nome | nota
---|---|---
1 | Zezinho | 10
2 | aluno | 8

### Destacando comandos de outras linguagens

O código `document.getElementById()` é da linguagem **JavaScript**!

Para dar este destaque basta envelopar com uma __Crase__ **``**

Codigo em **Python**

```
num = int(input("Digite um valor: "))
   if (num % 2 == 0):
      print(f"O número {num} é PAR")
   else:
      print(f"O número {num} é Ímpar")
 ```     
 
 Para dar destaque em um trecho de código basta envelopar com três **Crases** __```__
 
 ### Emoji
 
 Para adicionar _emoji_ basta colocar dois pontos e o nome do emoji **: + nome do emeji** 💛
 
 Estou utilizando emoji 😊 🌎 ✋



