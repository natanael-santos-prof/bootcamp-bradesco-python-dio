# 🏦 Automações em Python para o Setor Bancário

Este repositório reúne os projetos práticos que desenvolvi durante o **Bootcamp Bradesco na DIO**. O objetivo principal é aplicar a programação para resolver problemas reais e automatizar tarefas que acontecem no dia a dia de um banco.

---

## 🧠 Projeto 1: Assistente Virtual de Ferramentas Bancárias

### 📄 O que este projeto faz? (Em palavras simples)
Imagine que um novo funcionário entra para trabalhar na agência do banco. Ele precisa realizar várias tarefas no computador (como calcular juros ou consultar saldos), mas ainda não decorou qual ferramenta usar para cada caso.

Este programa funciona exatamente como um **assistente virtual inteligente por texto**:
1. O funcionário digita ou seleciona o que precisa fazer.
2. O sistema analisa o pedido em menos de um segundo.
3. O programa responde na tela explicando o que aquela ferramenta faz e como ela ajuda a resolver o problema.

### 💡 Exemplo Prático de Uso
Se o funcionário digitar exatamente isto:
> *`Relatorio de juros em planilha Excel`*

O sistema responde na hora:
> *`Calculo de juros sobre saldos usando colunas da planilha`*

---

## 📊 Do Exercício para a Realidade: Como isso funcionaria com uma Planilha de Verdade?

No desafio do Bootcamp, criamos a "inteligência" básica do sistema. Mas no dia a dia de uma agência bancária de verdade, esse mesmo código seria conectado a arquivos reais do banco para trabalhar sozinho. 

O processo automático funcionaria assim:

* 📥 **O Arquivo Base:** O banco deixaria uma planilha salva no computador (chamada `clientes.csv`) contendo uma lista com o nome de centenas de clientes e o saldo em conta de cada um deles.
* 🔌 **A Conexão:** No código, usaríamos um comando para o Python "conversar" com essa planilha e puxar todos os dados para dentro da memória do programa de forma invisível.
* ⚙️ **A Mágica da Automação:** Quando o funcionário digitasse que quer o relatório de juros, o Python não apenas responderia com um texto explicativo. Ele abriria a planilha em milissegundos, calcularia os juros de cada um dos centenas de clientes automaticamente e mostraria a tabela com os valores finais calculados na tela.

---

## 🛠️ Quais habilidades eu desenvolvi com esse projeto?
Para construir essa solução do zero, precisei dominar três pilares da lógica de programação:
* **Comunicação com o Usuário:** Fazer o computador criar caixas de diálogo para ouvir, ler e interpretar o que uma pessoa digita.
* **Tomada de Decisão:** Programar regras de escolha (se o usuário pedir "X", o sistema faz "X"; se pedir "Y", o sistema faz "Y") para que o software nunca fique confuso.
* **Organização e Manutenção:** Estruturar o código de um jeito limpo. Assim, se o banco criar uma ferramenta nova amanhã, basta adicionar uma linha no sistema e ele continuará funcionando perfeitamente sem precisar refazer o programa do zero.
* 
