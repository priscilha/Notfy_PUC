# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>


## Personas

Alice 
Idade: 54 anos
Gênero: Feminino 
Profissão: Tabeliã 
Instrução: Bacharel em Direito 
Estado civil: Casada 
Cidade: Jaboticatubas 
Mídias: Twitter, Facebook e Instagram  

Biografia:
Alice mineira nascida na região da serra do espinhaço, no município de Jaboticatubas, tem 54 anos, apaixonada por sua família e pela natureza, trabalhou por anos em um cartório em Belo Horizonte como escrevente, hoje trabalha em seu próprio cartório. É aficcionada por inovações tecnológicas. Também é simpática e muito influente na cidade. Seu hobby favorito são as caminhadas ao ar livre.

Desafios: 
Administrar melhor seu Cartório, procurar ferramentas e mecanismos que facilitem a rotina no trabalho de toda sua equipe. 
Otimização de processos. 


Bruno
Idade: 27 anos
Gênero: Masculino
Profissão: Notificador
Instrução: Graduando em Administração
Estado civil: Solteiro
Cidade: Belo Horizonte
Mídias: Twitter, Facebook e Instagram  

Biografia:
Bruno Almeida, tem 27 anos, cursa Administração no período noturno e trabalha no período integral. Ele é fã de novas tecnologias, utiliza muitos apps para facilitar seu dia a dia bastante atarefado. É um homem bastante comunicativo, tem facilidade de relacionar com as pessoas. Bruno gosta de ouvir músicas eletrônicas e podcast, e tem hábito de praticar corridas de rua aos finais de semana. Fica muito tempo conectado na internet, utilização maior pelo celular.

Desafios:
Por por não conseguir atender muitas demandas, perder muito tempo no deslocamento entre uma notificação e outra, além do alto custo financeiro para o deslocamento com pouca logística, Bruno acredita que poderia utilizar a tecnologia a seu favor para melhorar seu desempenho com as notificações. Otimizando seu trabalho, atenderia com mais eficácia suas demandas e aumentaria a segurança do processo referente às notificações extrajudiciárias.


Cíntia
Idade: 45 anos
Gênero: Feminino 
Profissão: Advogada e Notária de Cartório 
Instrução: Bacharel em Direito 
Estado civil: Casada 
Cidade: Contagem
Mídias: Facebook e Instagram  

Biografia:
É advogada e notária em um cartório na região de Contagem. Casada e mãe de duas crianças, gosta de passar o tempo livre com sua família.
Ela tem um perfil analítico e focada em conhecimento, obcecada com novidades e inovações. Quer sempre qualificar sua equipe, porém não dispõe de muito tempo e sua agenda está sempre apertada.

Desafios: 
Ela gostaria de aumentar seus resultados utilizando ferramentas tecnológicas que simplifiquem seus processos diários otimizando tempo e gerando melhores resultados - com estratégias inovadoras, ser líder referência para sua equipe.
Seus principais obstáculos são o excesso de tarefas e a dificuldade de gestão de tempo, além da falta de incentivo e aprovação da direção para colocar em prática todas as suas ideias.

Joana Dark Idade: 47 anos Profissão: Notificadora Escolaridade: Ensino médio completo Estado civil: Casada. Cidade: Belo Horizonte - MG

Biografia: Joana é uma mulher de 47 anos, mãe de 2 filhos adultos e avó de 1 neto. Trabalha como notificadora há 20 anos. Não tem a pretensão de avançar nos estudos e está satisfeita com sua escolarização e profissão. Também não gosta de ferramentas complicadas. Após o expediente, Joana faz doces para a confeitaria que ele tem em casa com uma de suas filhas. Nos momentos de lazer, gosta de assistir novelas e ler revistas e ter um tempo livre com o seu neto.

Desafios: Joana se perde muito por não ter uma rota pré-definida. Perde muito tempo tentando planejar um roteiro de entrega e ainda assim, acaba fazendo um trajeto ineficiente. Precisa otimizar as atividades como notificadora para se dedicar mais à confeitaria, considerando que demora para concluir suas atividades diárias. Tem muita dificuldade com tecnologias e coisas novas, também não se interessa em aprender porque se julga incapaz.


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`       |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------------|----------------------------------------|
|Administrador       | Gerenciar melhor os processos do cartório|Reduzir os custos do cartório           |
|Administrador       | Facilitar o trabalho dos funcionários    |Dar mais celeridade aos processos       |
|Notificador         | Cadastrar Notificandos                   |Criar banco de dados                    |
|Notificador         | Gerar rotas                              |Organizar as notificações por endereços |  
|Notificador         | Dar check-in em cada diligência          |Comprovar a realização do trabalho      |
|Notificador         | Gerar certidão através do sistema        |Agilizar a conclusão do trabalho        |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir cadastro de administradores e usuários | ALTA |
|RF-002| Permitir alteração cadastral de administradores e usuários | MÉDIA |
|RF-003| Permitir exclusão de cadastro de administradores e usuários | MÉDIA |
|RF-004| Permitir que o usuário cadastre notificandos | ALTA | 
|RF-005| Permitir que o usuário altere o cadastro  | MÉDIA |
|RF-006| Permitir que o usuário exclua o cadastro  | MÉDIA |
|RF-007| Gerar rota a partir dos dados de cada protocolo | ALTA |
|RF-008| Permitir que o usuário exclua a rota | MÉDIA |
|RF-009| Permitir que o usuário exclua um ou mais protocolos da rota | MÉDIA |
|RF-010| Permitir que o usuário inclua um ou mais protocolos na rota | MÉDIA |
|RF-011| Realizar check-in em cada diligência realizada por notificando | ALTA |
|RF-012| Permitir que o usuário finalize o protocolo no momento do check-in | ALTA |
|RF-013| Permitir que o usuário registre a conclusão da diligência no momento do check-in | ALTA |
|RF-014| Gerar certidão de conclusão toda vez que um protocolo for finalizado | ALTA |
|RF-015| Permitir que o usuário altere a certidão de conclusão | MÉDIA |
|RF-016| Permitir que o usuário exclua a certidão de conclusão | MÉDIA |
|RF-017| Permitir que o administrador visualize as rotas realizadas por usuário | ALTA |
|RF-018| Permitir que o administrador acesse as estatísticas dos deslocamentos realizados por usuário | MÉDIA |




### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 
|RNF-003| Deve realisar reuisições assincronamente | ALTA |
|RNF-004| Deve atender a maior parte possível das Heurísticas de Nielsen para usabilidade |  ALTA | 
|RNF-005| Deve ser acessível para pessoas com deficiência, segundo as métricas estabelecidas pelo W3C |  MéDIA | 
|RNF-006| Disponibilidade - Deve permitir imput de informações em modo off-line |  MÉDIA | 
|RNF-007| Segurança - Autenticação de usuário para consumo de webservices do sistema por sistemas externos |  ALTA | 
RNF-008| Arquitetura de desenvolvimento em camadas para desaclopamento |  ALTA | 


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |



