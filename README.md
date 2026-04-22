# 💰 Fluxo Sincronizado - Gestão Financeira Inteligente

Este é um sistema de contabilidade pessoal focado em **Front-end**, desenvolvido para oferecer controle total sobre entradas e gastos, com suporte especial para compras parceladas e sincronização automática de dados.

> **🔗 Acesse o projeto aqui:** (https://alananery-dev.github.io/Contabilidade/)

---

## 🚀 Funcionalidades Principais

* **Gestão de Entradas e Saídas:** Registro detalhado de ganhos e despesas com interface intuitiva.
* **Parcelamento Inteligente:** Ao adicionar um gasto, você pode definir o número de parcelas. O sistema gera automaticamente os registros para os meses seguintes, mantendo o vínculo entre eles.
* **Dashboard em Tempo Real:** Visualização clara do total de entradas/saídas do mês e o saldo geral acumulado.
* **Edição Dinâmica:** Quase todos os campos da tabela são editáveis diretamente com um clique.
* **Filtro por Período:** Selecione o mês/ano para analisar suas finanças de forma isolada.
* **Backup e Restauração:** Função para exportar todos os seus dados em um arquivo `.json` e importá-los quando quiser, garantindo que você nunca perca seu histórico.
* **Saldo Progressivo:** Uma coluna que calcula o saldo após cada transação, permitindo ver exatamente quando sua conta ficou negativa ou positiva.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica do projeto.
* **CSS3:** Design responsivo e interativo com variáveis (Root) para fácil manutenção de cores.
* **JavaScript (Vanilla):** Lógica pura para manipulação de dados, cálculos financeiros e controle de datas.
* **LocalStorage:** Persistência de dados no navegador, eliminando a necessidade de um banco de dados externo para uso pessoal.

## 🧠 Desafios Técnicos Superados

Neste projeto, foquei em resolver problemas reais de lógica de programação:
1.  **Sincronização de Grupos:** Criar uma lógica que identifica parcelas pertencentes ao mesmo "gasto pai", permitindo excluir ou editar o grupo inteiro ou apenas uma parcela isolada.
2.  **Tratamento de Datas:** Gerenciamento de fuso horário e progressão de meses em objetos de data do JavaScript.
3.  **Algoritmo de Saldo Progressivo:** Cálculo dinâmico do saldo baseado na ordenação cronológica das transações, independentemente da ordem em que foram inseridas.

---

## 👨‍💻 Como rodar este projeto localmente

1. Faça o download do arquivo `index.html`.
2. Abra-o em qualquer navegador moderno.
3. Não requer instalação de dependências ou servidores.

---
Desenvolvido por Alananery-Dev - 2026
