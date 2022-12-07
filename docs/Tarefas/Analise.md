# Análise de tarefas

## Histórico de Versão
|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:-----------:| :------: | :-----------: | :---------: |:---------: |
|03/12/2022|05/12/2022|1.0|Criação do documento|[Ana Luiza](https://github.com/AnHoff)|[Pedro Lucas](https://github.com/PedroLSF)|
|06/12/2022|07/12/2022|1.1|Adição do GOMS|[Pedro Lucas](https://github.com/PedroLSF)|[João Lucas](https://github.com/HacKairos)|

## Introdução
A análise de tarefas é uma atividade que pode ser realizada em diversas etapas do desenvolvimento, inclusive antes mesmo dele começar. Essa atividade consiste em analisar a situação atual do produto para determinar como cada tarefa é realizada, seja com o apoio de softwares externos ou não. Também é possível realizar a análise após a implementação de intervenções no sistema já existente.

Dois métodos foram escolhidos para realizar a análise de tarefas nesse projeto, são eles:

* Hierarchical Task Analysis, ou HTA;
* GOMS, sigla para Goals, Operators, Methods and Selection Rules.

## HTA
Hierarchical Task Analysis (HTA) ou, em português, Análise Hierárquica de Tarefas (AHT), usa como base as tarefas a serem realizadas a fim de atingir um objetivo do usuário. Abaixo é possível conferir as principais tarefas que um usuário procura utilizar através do Simples Nacional. A listagem foi disponibilizada com base nas propostas de notação textual e gráfica; para entender essas notações, veja os exemplos abaixo:
<br>

#### Exemplo 1 - notação textual:

* **0 - Objetivo**
    * **1 - Tarefa 1**
        * 1.1 - Sub-tarefa 1
        * 1.2 - Sub-tarefa 2
    * **2 - Tarefa 2**
        * 2.1 - Sub-tarefa 1
        * 2.2 - Sub-tarefa 2

#### Exemplo 2 - notação gráfica:
<center>

<img src="../../assets/analise/imgLegendaHierarquia.png">

</center>

### Representação em notação textual

### Representação em notação gráfica

## GOMS
GOMS é a abreviação de 4 termos utilizados nesse método, seriam eles Goals, Operators, Methods e Selection Rules. Vamos entender um pouco mais sobre o método GOMS:

É um métodos de análise de tarefas que permite a representação do conhecimento necessário para a realização de uma tarefa por parte de um usuário. Nessas representações podemos encontrar goals que são as metas e submetas que o usuário deseja fazer, operators que são as ações que o software permite que o usuário tome e que são diretamente relacionadas com o dispositivo em si, methods que são sequências claras de goals e operators que permitem o usuário concluir uma tarefa, selection rules que são as regras que o usuário pode seguir para decidir qual método usará para atingir uma goal.

### Objetivos
* Incluir o Débito Automático
1. Method 1: Pelo CNPJ
   
   1. **Goal 0:** Acessar o Débito Automático
        1. **OP 0.1:** Deslocar o mouse até o quadrado escrito "Simei";
        2. **OP 0.2:** Apertar o botão esquerdo em "Débito Automático";
        3. **OP 0.3:** Clicar na chave dentro de "Código de Acesso";
        4. **OP 0.4:** Preencher o campo de "CNPJ";
        5. **OP 0.5:** Preencher o campo de "CPF";
        6. **OP 0.6:** Preencher o campo de "Código de Acesso";
        7. **OP 0.7:** Preencher o campo de caracteres;
        8. **OP 0.8:** Deslocar o mouse até o quadrado escrito "Continuar";
        9. **OP 0.9:** Apertar o botão esquerdo do Mouse;
    1. **Goal 1:** Incluir o Débito Automático
        1. **OP 1.1:** Deslocar o mouse até "Débito Automático";
        2. **OP 1.2:** Apertar o botão esquerdo do Mouse;
        3. **OP 1.3:** Selecionar "Inclusão";
        4. **OP 1.4:** Digitar os dados;
        5. **OP 1.5:** Deslocar o mouse para "Continuar";
        6. **OP 1.6:** Apertar o botão esquerdo do Mouse;
* Consultar o Débito Automático
1. Method 1: Pelo CNPJ
   1. **Goal 0:** Acessar o Débito Automático
        1. **OP 0.1:** Deslocar o mouse até o quadrado escrito "Simei";
        2. **OP 0.2:** Apertar o botão esquerdo em "Débito Automático";
        3. **OP 0.3:** Clicar na chave dentro de "Código de Acesso";
        4. **OP 0.4:** Preencher o campo de "CNPJ";
        5. **OP 0.5:** Preencher o campo de "CPF";
        6. **OP 0.6:** Preencher o campo de "Código de Acesso";
        7. **OP 0.7:** Preencher o campo de caracteres;
        8. **OP 0.8:** Deslocar o mouse até o quadrado escrito "Continuar";
        9. **OP 0.9:** Apertar o botão esquerdo do Mouse;
    1. **Goal 1:** Consultar o Débito Automático
        1. **OP 1.1:** Deslocar o mouse até "Débito Automático";
        2. **OP 1.2:** Apertar o botão esquerdo do Mouse;
        3. **OP 1.3:** Selecionar "Consulta";
        5. **OP 1.4:** Deslocar o mouse para "Continuar";
        6. **OP 1.5:** Apertar o botão esquerdo do Mouse;
* Alterar o Débito Automático
1. Method 1: Pelo CNPJ
   
   1. **Goal 0:** Acessar o Débito Automático
        1. **OP 0.1:** Deslocar o mouse até o quadrado escrito "Simei";
        2. **OP 0.2:** Apertar o botão esquerdo em "Débito Automático";
        3. **OP 0.3:** Clicar na chave dentro de "Código de Acesso";
        4. **OP 0.4:** Preencher o campo de "CNPJ";
        5. **OP 0.5:** Preencher o campo de "CPF";
        6. **OP 0.6:** Preencher o campo de "Código de Acesso";
        7. **OP 0.7:** Preencher o campo de caracteres;
        8. **OP 0.8:** Deslocar o mouse até o quadrado escrito "Continuar";
        9. **OP 0.9:** Apertar o botão esquerdo do Mouse;
    1. **Goal 1:** Alterar o Débito Automático
        1. **OP 1.1:** Deslocar o mouse até "Débito Automático";
        2. **OP 1.2:** Apertar o botão esquerdo do Mouse;
        3. **OP 1.3:** Selecionar "Alteração";
        4. **OP 1.4:** Digitar os dados;
        5. **OP 1.5:** Deslocar o mouse para "Continuar";
        6. **OP 1.6:** Apertar o botão esquerdo do Mouse;

* Desativar o Débito Automático
1. Method 1: Pelo CNPJ
   1. **Goal 0:** Acessar o Débito Automático
        1. **OP 0.1:** Deslocar o mouse até o quadrado escrito "Simei";
        2. **OP 0.2:** Apertar o botão esquerdo em "Débito Automático";
        3. **OP 0.3:** Clicar na chave dentro de "Código de Acesso";
        4. **OP 0.4:** Preencher o campo de "CNPJ";
        5. **OP 0.5:** Preencher o campo de "CPF";
        6. **OP 0.6:** Preencher o campo de "Código de Acesso";
        7. **OP 0.7:** Preencher o campo de caracteres;
        8. **OP 0.8:** Deslocar o mouse até o quadrado escrito "Continuar";
        9. **OP 0.9:** Apertar o botão esquerdo do Mouse;
    1. **Goal 1:** Desativar o Débito Automático
        1. **OP 1.1:** Deslocar o mouse até "Débito Automático";
        2. **OP 1.2:** Apertar o botão esquerdo do Mouse;
        3. **OP 1.3:** Selecionar "Desativação";
        5. **OP 1.4:** Deslocar o mouse para "Continuar";
        6. **OP 1.5:** Apertar o botão esquerdo do Mouse;

* Alterar o Débito Automático
1. Method 1: Pelo CNPJ
   
   1. **Goal 0:** Acessar o Débito Automático
        1. **OP 0.1:** Deslocar o mouse até o quadrado escrito "Simei";
        2. **OP 0.2:** Apertar o botão esquerdo em "Débito Automático";
        3. **OP 0.3:** Clicar na chave dentro de "Código de Acesso";
        4. **OP 0.4:** Preencher o campo de "CNPJ";
        5. **OP 0.5:** Preencher o campo de "CPF";
        6. **OP 0.6:** Preencher o campo de "Código de Acesso";
        7. **OP 0.7:** Preencher o campo de caracteres;
        8. **OP 0.8:** Deslocar o mouse até o quadrado escrito "Continuar";
        9. **OP 0.9:** Apertar o botão esquerdo do Mouse;
    1. **Goal 1:** Alterar o Débito Automático
        1. **OP 1.1:** Deslocar o mouse até "Débito Automático";
        2. **OP 1.2:** Apertar o botão esquerdo do Mouse;
        3. **OP 1.3:** Selecionar "Alteração";
        4. **OP 1.4:** Digitar os dados;
        5. **OP 1.5:** Deslocar o mouse para "Continuar";
        6. **OP 1.6:** Apertar o botão esquerdo do Mouse;

* Visualizar os calculos e declarações
1. Method 1: Pelo CNPJ
   1. **Goal 0:** Acessar o cálculo e declaração
        1. **OP 0.1:** Deslocar o mouse até o quadrado escrito "Simei";
        2. **OP 0.2:** Apertar o botão esquerdo em "Cálculo e decração";
        3. **OP 0.3:** Clicar na chave dentro de "Código de Acesso";
        4. **OP 0.4:** Preencher o campo de "CNPJ";
        5. **OP 0.5:** Preencher o campo de "CPF";
        6. **OP 0.6:** Preencher o campo de "Código de Acesso";
        7. **OP 0.7:** Preencher o campo de caracteres;
        8. **OP 0.8:** Deslocar o mouse até o quadrado escrito "Continuar";
        9. **OP 0.9:** Apertar o botão esquerdo do Mouse;
    1. **Goal 1:** Visualizar cálculo e declaração
        1. **OP 1.1:** Deslocar o mouse até o desenho de uma impressora;
        2. **OP 1.2:** Apertar o botão esquerdo do Mouse;

* Pagar de forma on-line calculos e declarações
1. Method 1: Pelo CNPJ
   1. **Goal 0:** Acessar o Débito Automático
        1. **OP 0.1:** Deslocar o mouse até o quadrado escrito "Simei";
        2. **OP 0.2:** Apertar o botão esquerdo em "Cálculo e decração";
        3. **OP 0.3:** Clicar na chave dentro de "Código de Acesso";
        4. **OP 0.4:** Preencher o campo de "CNPJ";
        5. **OP 0.5:** Preencher o campo de "CPF";
        6. **OP 0.6:** Preencher o campo de "Código de Acesso";
        7. **OP 0.7:** Preencher o campo de caracteres;
        8. **OP 0.8:** Deslocar o mouse até o quadrado escrito "Continuar";
        9. **OP 0.9:** Apertar o botão esquerdo do Mouse;
    1. **Goal 1:** Visualizar cálculo e declaração
        1. **OP 1.1:** Deslocar o mouse até o desenho de computador;
        2. **OP 1.2:** Apertar o botão esquerdo do Mouse;

* Solicitar Restituição
1. Method 1: Pelo CNPJ
   
   1. **Goal 0:** Acessar o Débito Automático
        1. **OP 0.1:** Deslocar o mouse até o quadrado escrito "Simei";
        2. **OP 0.2:** Apertar o botão esquerdo em "Restituição";
        3. **OP 0.3:** Clicar na chave dentro de "Código de Acesso";
        4. **OP 0.4:** Preencher o campo de "CNPJ";
        5. **OP 0.5:** Preencher o campo de "CPF";
        6. **OP 0.6:** Preencher o campo de "Código de Acesso";
        7. **OP 0.7:** Preencher o campo de caracteres;
        8. **OP 0.8:** Deslocar o mouse até o quadrado escrito "Continuar";
        9. **OP 0.9:** Apertar o botão esquerdo do Mouse;
    1. **Goal 1:** Solicitar Restituição
        1. **OP 1.1:** Deslocar o mouse até "Solicitar Restituição";
        2. **OP 1.2:** Apertar o botão esquerdo do Mouse;
        3. **OP 1.3:** Deslocar o mouse até a caixa de texto de "PA";
        4. **OP 1.4:** Digitar o ano;
        5. **OP 1.5:** Deslocar o mouse para "Continuar";
        6. **OP 1.6:** Apertar o botão esquerdo do Mouse;

* Consultar pedidos de restituição
1. Method 1: Pelo CNPJ
   
   1. **Goal 0:** Acessar o Débito Automático
        1. **OP 0.1:** Deslocar o mouse até o quadrado escrito "Simei";
        2. **OP 0.2:** Apertar o botão esquerdo em "Restituição";
        3. **OP 0.3:** Clicar na chave dentro de "Código de Acesso";
        4. **OP 0.4:** Preencher o campo de "CNPJ";
        5. **OP 0.5:** Preencher o campo de "CPF";
        6. **OP 0.6:** Preencher o campo de "Código de Acesso";
        7. **OP 0.7:** Preencher o campo de caracteres;
        8. **OP 0.8:** Deslocar o mouse até o quadrado escrito "Continuar";
        9. **OP 0.9:** Apertar o botão esquerdo do Mouse;
    1. **Goal 1:** Consultar Restituição
        1. **OP 1.1:** Deslocar o mouse até "Consultar Pedidos de Restituição";
        2. **OP 1.2:** Apertar o botão esquerdo do Mouse;

* Alterar Dados Bancários para Crédito da Restituição
1. Method 1: Pelo CNPJ
   
   1. **Goal 0:** Acessar o Débito Automático
        1. **OP 0.1:** Deslocar o mouse até o quadrado escrito "Simei";
        2. **OP 0.2:** Apertar o botão esquerdo em "Restituição";
        3. **OP 0.3:** Clicar na chave dentro de "Código de Acesso";
        4. **OP 0.4:** Preencher o campo de "CNPJ";
        5. **OP 0.5:** Preencher o campo de "CPF";
        6. **OP 0.6:** Preencher o campo de "Código de Acesso";
        7. **OP 0.7:** Preencher o campo de caracteres;
        8. **OP 0.8:** Deslocar o mouse até o quadrado escrito "Continuar";
        9. **OP 0.9:** Apertar o botão esquerdo do Mouse;
    1. **Goal 1:** Consultar Restituição
        1. **OP 1.1:** Deslocar o mouse até "Alterar Dados Bancários para Crédito da Restituição";
        2. **OP 1.2:** Apertar o botão esquerdo do Mouse;


## Bibliografia
BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010<br>
