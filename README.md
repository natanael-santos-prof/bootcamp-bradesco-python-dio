# 🏦 Central de Desafios - Python para o Setor Bancário

Este repositório reúne os projetos práticos que desenvolvi durante o **Bootcamp Bradesco na DIO**. O objetivo principal é aplicar a programação Python para resolver problemas reais que acontecem no dia a dia de um banco.

---

## 🧠 Desafio 1: Guia Inteligente de Ferramentas Bancárias

### 📄 O que este projeto faz? (Resumo Simples)
Imagine que um novo funcionário entra no banco e precisa criar um relatório, mas não sabe qual ferramenta usar. Este programa funciona como um **assistente virtual**: o usuário digita a tarefa que precisa fazer e o sistema responde na hora qual é a ferramenta correta (como Excel ou SQL) e o motivo.

### 💡 Exemplo Prático (Como funciona)
*   **O que o usuário digita:** `Relatorio de juros em planilha Excel`
*   **O que o sistema responde:** `Calculo de juros sobre saldos usando colunas da planilha`

---

## 📊 Do Exercício para o Mundo Real: Como funcionaria com uma Planilha de Verdade?

Se quiséssemos levar este projeto para o dia a dia de uma agência bancária real, a inteligência do código que criei seria embutida para abrir arquivos de verdade. O processo funcionaria assim em apenas 3 passos:

1. **Armazenamento:** Salvaríamos uma planilha real do Excel (ex: `clientes.csv`) com os saldos dos correntistas na mesma pasta do código.
2. **Integração:** Usaríamos uma biblioteca do Python chamada `pandas` para ler o arquivo diretamente com o comando:
   ```python
   df = pd.read_csv("clientes.csv")
   ```
3. **Automação:** Assim que o usuário digitasse a tarefa no terminal, o Python abriria a planilha em milissegundos, calcularia os juros automaticamente linha por linha e exibiria a tabela atualizada na tela.

---

## 🛠️ O que eu precisei aprender para construir isso?
Para criar essa automação, utilizei conceitos fundamentais de lógica:
1.  **Entrada de Dados:** Fazer o programa ouvir e entender o que o usuário digita.
2.  **Tomada de Decisão:** Criar regras para o programa analisar o texto e escolher a resposta certa.
3.  **Organização de Código:** Estruturar as funções para que o sistema seja rápido e fácil de atualizar caso o banco adicione novas ferramentas no futuro.

---

## 🚀 Como testar no seu computador
1. Abra a pasta `desafios-de-codigo/`.
2. Execute o arquivo `entendendo_operacoes_bancarias.py`.

### 📸 Demonstração Prática no Terminal
![Simulação do Sistema](desafios-de-codigo/NOME_DA_SUA_IMAGEM.jpg)
