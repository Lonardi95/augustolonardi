# Projeto: Verificador de Aprovação Escolar (Portugol)

Este é um projeto simples desenvolvido em **Portugol**, que calcula a média de duas notas e informa se o aluno foi **Aprovado**, **está em Recuperação** ou **foi Reprovado** com base na média.

---

## Objetivo

O objetivo do projeto é aplicar os primeiros conceitos de **variáveis**, **leitura de dados**, **cálculo de média** e **estrutura condicional** em um algoritmo prático e funcional.

---

## Tecnologias utilizadas

 **Portugol**
- Lógica de programação básica
- Entrada e saída de dados
- Condicionais (if, else)

---

## O que eu aprendi

Durante o desenvolvimento deste projeto, aprendi a:

- Declarar e utilizar variáveis do tipo `real`
- Utilizar comandos de entrada (`Leia`) e saída (`Escreva` / `Escreval`)
- Implementar estruturas condicionais aninhadas (`Se`, `Senao`, `Fimse`)
- Criar algoritmos que seguem regras de decisão baseadas em valores numéricos
- Aplicar regras de negócio de forma clara e organizada em um programa

---

## Exemplo de uso

```
Qual a nota da primeira prova? 6.0  
Qual a nota da segunda prova? 4.5  
Sua nota média foi de: 5.25  
Você está de RECUPERAÇÃO.
```
## Código:
- algoritmo "aprovacao"
- var
-    n1, n2, media: real
- inicio
-      Escreva ("Qual a nota da primeira prova? ")
-      Leia (n1)
-      Escreva ("Qual a nota da segunda prova? ")
-      Leia (n2)
-      media <- (n1+n2)/2
-      Escreval ("Sua nota média foi de: ", media)
-      Se (media >= 7:1:2) entao
-         Escreval ("Você foi APROVADO.")
-      SENAO
-           SE (media >= 5) e (<=6.99) entao
-              Escreval ("Você está de RECUPERAÇÃO.")
-           Senao
-                Escreval ("Você foi REPROVADO.")
-           Fimse
-      Fimse
-
- fimalgoritmo
