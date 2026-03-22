# Reescrita-de-Algoritmos-em-Rust
Disciplina: Estruturas de Dados e Análise de Algoritmos Aula: 04 – Implementação de Algoritmos em Rust Professor: Alexandre de Oliveira

Reescrita de Algoritmos em Rust
NOME: Suzana
RA: 124115854


** Reescrita de Algoritmos em Rust: 
// Ex1: 
Complexidade: O(1)
Esse algoritmo só pega o primeiro número da lista. Se a lista estiver vazia, ele retorna nada. Não tem repetição (loop). Ele só olha o primeiro elemento, então não importa o tamanho da lista, sempre faz a mesma coisa.

//Ex2:
Complexidade: O(n)
Ele percorre toda a lista somando os números até chegar no final. Tem um único loop que passa por todos os elementos. Quanto maior a lista, mais tempo vai levar.

//Ex3:
Complexidade: O(log n)
Ele procura um número no meio da lista. Se não achar, ele elimina metade da lista e continua procurando. 
A cada passo ele divide a lista pela metade. Isso faz com que o número de passos seja bem pequeno, mesmo com listas grandes.

//\Ex4: 
Complexidade: O(n²)
Tem dois loops, um dentro do outro. Isso faz o número de operações crescer muito rápido quando a lista aumenta.

//Ex5: 
Complexidade: O(n²)
começa com o número 1 e vai multiplicando por 2 até chegar perto do número informado.
