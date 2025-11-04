# Estrutura-de-dados-

📚 Estruturas de Dados em Java (Lista, Pilha e Fila)

Este projeto implementa três estruturas de dados fundamentais em Java:

✅ Lista (vetor estático)
✅ Pilha (estrutura LIFO)
✅ Fila (estrutura FIFO)

Além disso, contém um menu interativo no console (classe Principal) que permite testar cada uma dessas estruturas de forma amigável.

🚀 Tecnologias Utilizadas

Linguagem: Java

IDE sugerida: IntelliJ IDEA, Eclipse ou VS Code

Entrada de dados: Scanner (entrada via console)

src/
├── estruturas/
│   ├── Lista.java
│   ├── Pilha.java
│   ├── Fila.java
│   ├── Principal.java   ← Menu principal do programa

📌 Classe Principal (Menu Interativo)

A classe Principal permite ao usuário escolher qual estrutura de dados deseja testar.

✅ Opções do Menu:

=== MENU PRINCIPAL ===
1. Testar Lista
2. Testar Pilha
3. Testar Fila
4. Sair

Cada opção leva a um submenu com ações específicas, como inserir, remover, mostrar e verificar se está vazia.

🧪 Funcionalidades por Estrutura

📌 LISTA
Inserir elemento
Mostrar todos os elementos

📌 PILHA
Empilhar (push)
Desempilhar (pop)

Verificar se está vazia

📌 FILA
Enfileirar (add)
Desenfileirar (remove)
Mostrar fila

🖥️ Como Executar

Certifique-se de que todos os arquivos .java estão no mesmo pacote (estruturas).
Compile o projeto:

javac estruturas/*.java
java estruturas.Principal

✅ Exemplo de Funcionamento
=== MENU PRINCIPAL ===
1. Testar Lista
2. Testar Pilha
3. Testar Fila
4. Sair
Escolha uma opção: 1

--- LISTA ---
1. Inserir elemento
2. Mostrar lista
3. Voltar ao menu principal
Escolha: 1
Digite um valor para inserir: 50
