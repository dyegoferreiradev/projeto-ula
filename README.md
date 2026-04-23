# 💻 Projeto ULA (Unidade Lógica e Aritmética)

## 📖 Sobre o Projeto
Este repositório contém o desenvolvimento de uma **ULA (Unidade Lógica e Aritmética)** criado como parte da disciplina de Sistemas Digitais. O objetivo principal do projeto é aplicar os conceitos de eletrônica digital na prática, construindo os circuitos inteiramente a nível de portas lógicas (Logic Gates).

## ⚙️ Especificações Técnicas
* **Arquitetura:** Operações baseadas em palavras de **5 bits**.
* **Nível de Abstração:** Baixo nível (Portas Lógicas / RTL).
* **Ambiente de Desenvolvimento:** Software [Intel Quartus Prime](https://www.intel.com/content/www/us/en/software/programmable/quartus-prime/overview.html).

## 🛠️ Funcionalidades e Operações
A ULA foi projetada para receber sinais de entrada (operandos) e executar uma série de operações fundamentadas na seleção de controle. As operações implementadas incluem:

* ➕ **Soma:** Adição binária de 5 bits.
* ➖ **Subtração:** Diferença entre valores (utilizando lógica de complemento de 2).
* ⚖️ **Comparadores:** Circuitos para identificar se os valores são maiores, menores ou iguais.
* *(Dica: Se você implementou operações lógicas como AND, OR, ou XOR, você pode listá-las aqui também!)*

## 🚀 Como Executar o Projeto no Quartus

1. **Clone o repositório** para a sua máquina local:
   ```bash
   git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
2. Abra o software **Intel Quartus**.
3. Vá no menu File > Open Project... e selecione o arquivo do projeto (geralmente com a extensão .qpf) dentro da pasta clonada.
4. Para compilar o hardware, clique em Processing > Start Compilation (ou no ícone de "Play" na barra superior).
5. **Simulação:** Para testar e visualizar o comportamento das portas lógicas e operações, utilize os arquivos de simulação de forma de onda (como o .vwf no ModelSim/Quartus Simulator) fornecendo diferentes sinais de entrada de 5 bits.
