# Modelo de Design

## Histórico de Versão
|Data|Versão|Descrição|Autor|Revisor|
| :----------: | :------: | :-----------: | :---------: |:---------: |
|22/11/2022|1.0|Criação do Documento| [Pedro Lucas](https://github.com/PedroLSF)| [João Lucas](https://github.com/HacKairos)

## Introdução

Em primeiro momento é fundamental entender que o processo de design tange as seguintes atividades básicas: a análise da situação atual (identificação do problema), a síntese de uma intervenção e a avaliação dessa intervenção projetada ou já aplicada à situação atual.

Precisamos entender que é fundamental o processo de design, porque cada processo específica essas atividades citadas a cima de forma única, deve ser citado o que é cada atividade, como executar e quando executar.

## Objetivo

Depois de algumas análises, a equipe irá trabalhar com o processo de Engenharia de Usabilidade de Mayhew, também conhecido como o Ciclo de Vida de Mayweh.

Este documento visa revisar algumas opções levantadas pela equipe e explicar de forma clara o motivo de Mayhew ser a primeira opção.

## Modelo de Design

### Ciclo de Vida de Mayhew

O Ciclo de Mayhew foi proposto por Deborah Mayhew (1999), e este processo está dividido em 3 grandes etapas:

* Análise de Requisitos
* Projeto, testes e implementação
* Instalação

<img src="../../assets/images/Mayhew.png" width="700" >Figura 1 - Ciclo de Vida da Mayhew</img>

<br></br>
Iremos abranger cada tópico e discutir um pouco sobre cada uma das etapas.

#### Análise de Requisitos

Está é a primeira fase, nesta fase é necessário definir as metas de usabilidade como mostrado na figura e deve ser definido através do  perfil dos usuários, análise de tarefas, possibilidades e limitações da plataforma em que o sistema será executado e os princípios gerais de design do projeto.

* **Análise do perfil do Usuário:** Para cada tipo de usuário previsto, os projetistas devem conhecer seus atributos pessoais (faixa etária, sexo, limitações, motivação) e suas habilidades e competências (na tarefa, na organização e com sistemas informatizados). 
* **Análise das tarefas:** Para cada tarefa a ser apoiada pelo sistema, os projetistas devem conhecer os objetivos e resultados, a estrutura, a duração, as dependências, os custos, a carga mental, as interrupções, os incidentes etc.
* **Características da Plataforma:** Devem ser examinadas as possibilidades e restrições em termos de equipamentos, sistemas operacionais, ambientes de janelas, recursos de rede etc.
* **Análise de princípios gerais para o projeto:** Pesquisa e catalogação do conhecimento ergonômico disponível para a concepção da interface no tipo de contexto de uso (usuário, tarefa, equipamento e ambiente) no qual o sistema está inserido.
* **Guia de Estilo:** Registra todas as decisões tomadas nesta e nas demais fases do desenvolvimento e devem ser registradas em um documento oficial.

####  Projeto, testes e implementação

Agora vamos falar sobre a segunda fase, aqui temos o objetivo de criar uma solução que se baseia nas metas de usabilidade que já foram definidas no processo anterior, será divida em três niveis que serão citados logo abaixo.

* **Primeiro nível:** 

    - Reengenharia do trabalho: Levando em consideração as especificações realizadas na etapa anterior, os projetistas devem aqui conceber um novo nível de automação da tarefa (nova repartição de tarefas entre o homem e a máquina) e uma nova organização do trabalho.
    - Modelo Conceitual: Modelagem de alternativas de projeto, nas quais os projetistas especificam as telas e componentes essenciais da interface, bem como a navegação entre elas.
    - Testes de Interface: 
        - Simulação dupla
  
            • Por um lado, os representantes de usuários simulam a realização das tarefas fundamentais do sistema (imaginando que as maquetes sejam o próprio sistema).

            • Por outro lado, os projetistas simulam o comportamento do sistema, tipicamente apresentando novas telas em papel em resposta a uma ação do usuário.
 
* **Segundo nível:**

    - Padrões de Telas e Diálogos: Estabelecerá regras para a escolha de controles, para a definição de seu formato e localização, para a terminologia empregada, para o uso de cores, tipos de fontes etc. 
    - Padrões de Telas - Protótipos de Baixa Fidelidade: Estabelecerá regras para a escolha de controles, para a definição de seu formato e localização, para a terminologia empregada, para o uso de cores, tipos de fontes etc.
    - Padrões de Telas - Testes: Simulações mais realistas do uso do sistema. Torna-se possível nesta etapa realizar testes de usabilidade mais detalhados, produzindo medidas objetivas sobre a eficácia, a facilidade de aprendizado e a taxa de erros do usuário na tarefa, por exemplo.

* **Terceiro Nível:**

    - Projeto Detalhado: O projetista integra ao projeto os aspectos não essenciais até então desconsiderados, tanto no que se refere ao modelo conceitual da interface quanto aos padrões de telas.
        - Janelas, caixas de diálogo e de mensagens até agora não previstos.
        - Caminhos entre estes componentes.
        - Conteúdo não essencial de cada janela, caixa de diálogo, formulário e caixa de mensagem.
        - Opções não essenciais de menus e de caixas de ferramentas.
    
    - Projeto Detalhado - Testes: Simulações ainda mais próximas da realidade, na medida em que o usuário estará empregando o sistema final para realizar suas tarefas.
        - Aferir a integração de diferentes interfaces, até agora consideradas individualmente, além de aspectos não essenciais dessas interfaces.
        - Medir tempos de tarefas e verificar se os valores admissíveis especificados na etapa de análise de requisitos estão sendo alcançados.

#### Instalação

Terceira etapa a ser realizada, aqui iremos tocar nos feedbacks do usuário  após a utilização do produto por um tempo determinado.

* Feedbacks do usuário: 
    - Detectar e eliminar problemas de última hora e preparar um novo release do produto.
    - Detectar e eliminar problemas maiores e preparar uma nova versão do produto.
    - Detectar oportunidades para melhoria de novas versões do produto e elaborar requisitos para novos produtos similares.

## Motivo de escolha

Dos modelos existentes, o ciclo Mayhew foi considerado o mais adequado para o nosso projeto, pois seus artefatos são mais complexos e completos, e o grupo acredita que será ideal para uso na disciplina de interação humano-computador. Ainda assim, se necessário, alguns artefatos de outros modelos serão utilizados para complementar alguns processos de projeto e, se for o caso, isso será devidamente documentado.