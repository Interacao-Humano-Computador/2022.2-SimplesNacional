# Modelo de Design

## <a>Histórico de Versão</a>
|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:-----------:| :------: | :-----------: | :---------: |:---------: |
|22/11/2022|22/11/2022|1.0|Criação do Documento|[Pedro Lucas](https://github.com/PedroLSF)|[João Lucas](https://github.com/HacKairos)|

## <a>Introdução</a>

Em primeiro momento, é fundamental entender que o processo de design tange as seguintes atividades básicas: análise da situação atual (identificação do problema), síntese de uma intervenção e avaliação dessa intervenção projetada ou já aplicada à situação atual.

É necessário entender que o processo de design é fundamental, visto que cada processo especifica as atividades citadas acima de forma única. Deve-se citar o que é cada atividade, como a executar e quando a executar.

## <a>Objetivo</a>

Depois de algumas análises, a equipe decidiu que irá trabalhar com o processo de Engenharia de Usabilidade de Mayhew, também conhecido como o Ciclo de Vida de Mayweh.

Esse documento visa revisar algumas opções levantadas pela equipe e explicar, de forma clara, o motivo de Mayhew ser a primeira opção.

## <a>Modelo de Design</a>

### <a>Ciclo de Vida de Mayhew</a>

O Ciclo de Mayhew foi proposto por Deborah Mayhew (1999), e está dividido em 3 grandes etapas:

* Análise de Requisitos;
* Projeto, testes e implementação;
* Instalação.

Ilustração do modelo na figura 1:
<br>

<center>

<img src="../../assets/images/Mayhew.png" width="700" ><br></img>

*Figura 1 - Ciclo de Vida da Mayhew (BARBOSA e SILVA, 2010)*

</center>

Cada tópico será explicado e será exposto um pouco sobre cada uma das etapas.
<br><br>

#### <a>Análise de Requisitos</a>

Esta é a primeira fase. Nela ocorre a definição das metas de usabilidade, como ilustrado na figura. Essa definição ocorre através do perfil dos usuários, da análise de tarefas, possibilidades e limitações da plataforma em que o sistema será executado e dos princípios gerais de design do projeto.

* **Análise do perfil do usuário:** para cada tipo de usuário previsto, os projetistas devem conhecer seus atributos pessoais (faixa etária, sexo, limitações, motivação) e suas habilidades e competências na tarefa, na organização e com sistemas informatizados;
* **Análise das tarefas:** para cada tarefa a ser apoiada pelo sistema, os projetistas devem conhecer os objetivos e resultados, a estrutura, a duração, as dependências, os custos, a carga mental, as interrupções, os incidentes e etc;
* **Características da plataforma:** devem ser examinadas as possibilidades e restrições em termos de equipamentos, sistemas operacionais, ambientes de janelas, recursos de rede e etc;
* **Análise de princípios gerais para o projeto:** pesquisa e catalogação do conhecimento ergonômico disponível para a concepção da interface no tipo de contexto de uso (usuário, tarefa, equipamento e ambiente) no qual o sistema está inserido;
* **Guia de estilo:** registra todas as decisões tomadas nesta e nas demais fases do desenvolvimento e devem ser registradas em um documento oficial.

#### <a> Projeto, testes e implementação</a>

Na segunda fase, temos o objetivo de criar uma solução baseada nas metas de usabilidade que foram definidas no processo anterior. Derá divida em três niveis, citados logo abaixo.

* **Primeiro nível:** 

    - Reengenharia do trabalho: levando em consideração as especificações realizadas na etapa anterior, os projetistas devem aqui conceber um novo nível de automação da tarefa (nova repartição de tarefas entre o homem e a máquina) e uma nova organização do trabalho.
    - Modelo Conceitual: modelagem de alternativas de projeto, nas quais os projetistas especificam as telas e componentes essenciais da interface, bem como a navegação entre elas.
    - Testes de Interface: 
        - Simulação dupla
  
            • Por um lado, os representantes de usuários simulam a realização das tarefas fundamentais do sistema, imaginando que as maquetes sejam o próprio sistema.

            • Por outro lado, os projetistas simulam o comportamento do sistema, tipicamente apresentando novas telas em papel, em resposta a uma ação do usuário.
 
* **Segundo nível:**

    - Padrões de Telas e Diálogos: estabelecerá regras para a escolha de controles, para a definição de seu formato e localização, para a terminologia empregada, para o uso de cores, tipos de fontes e etc. 
    - Padrões de Telas - Protótipos de Baixa Fidelidade: estabelecerá regras para a escolha de controles, para a definição de seu formato e localização, para a terminologia empregada, para o uso de cores, tipos de fontes e etc.
    - Padrões de Telas - Testes: simulações mais realistas do uso do sistema. Torna-se possível nesta etapa realizar testes de usabilidade mais detalhados, produzindo medidas objetivas sobre a eficácia, a facilidade de aprendizado e a taxa de erros do usuário na tarefa, por exemplo.

* **Terceiro Nível:**

    - Projeto Detalhado: o projetista integra ao projeto os aspectos não essenciais, até então desconsiderados, tanto no que se refere ao modelo conceitual da interface quanto aos padrões de telas.
        - Janelas, caixas de diálogo e de mensagens ainda não previstos;
        - Caminhos entre componentes;
        - Conteúdo não essencial de cada janela, caixa de diálogo, formulário e caixa de mensagem;
        - Opções não essenciais de menus e de caixas de ferramentas.
    
    - Projeto Detalhado - Testes: simulações ainda mais próximas da realidade, na medida em que o usuário estará empregando o sistema final para realizar suas tarefas.
        - Aferir a integração de diferentes interfaces, até agora consideradas individualmente, além de aspectos não essenciais das mesmas;
        - Medir tempos de tarefas e verificar se os valores admissíveis especificados na etapa de análise de requisitos estão sendo alcançados.

#### <a>Instalação</a>

A instalação é a terceira etapa a ser realizada, aqui deve-se tocar nos feedbacks do usuário após a utilização do produto por um tempo determinado.

* Feedbacks do usuário: 
    - Detectar e eliminar problemas de última hora e preparar um novo release do produto;
    - Detectar e eliminar problemas maiores e preparar uma nova versão do produto;
    - Detectar oportunidades para a melhoria de novas versões do produto e elaborar requisitos para novos produtos similares.

## <a>Motivo de escolha</a>

Dos modelos existentes, o ciclo Mayhew foi considerado o mais adequado para o projeto, pois seus artefatos são mais complexos e completos. A equipe acredita que ele será ideal para uso na disciplina de interação humano-computador. Ainda assim, caso necessário, alguns artefatos de outros modelos poderão ser utilizados para complementar alguns processos de projeto, sendo tudo devidamente documentado.

## <a>Bibliografia</a>
BARBOSA, SIMONE DINIZ JUNQUEIRO; SILVA, BRUNO SANTANA DA , **Interação Humano-Computador**, 1ª Edição, Editora Campus, 2010 
