# Especificações do Projeto

A fim de definir de maneira minuciosa a especificação do problema e os pontos mais relevantes a serem tratados neste projeto, foram realizadas entrevistas com potenciais usuários na região de Belo Horizonte. As entrevistas objetivaram identificar o perfil dos usuários, atividade física que pratica, como considera a sua dieta e os resultados almejados com a readequação alimentar.

## Personas

![image](/docs/img/persona1.png)
![image](/docs/img/persona2.png)
![image](/docs/img/persona3.png)
![image](/docs/img/persona4.png)
![image](/docs/img/persona5.png)


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Amanda Gomes  | Obter receitas com alimentos que possuo na despensa           | Aproveitá-los              |
|Roberto Antunes\Lorena Martins       | Calcular quantidade de calorias e macronutrientes ideais                 | Alcançar resultados almejados |
|Roberto Antunes       | Inserir receita própria                 | Calcular quantidade de calorias que não extrapole a meta diária. |
|João Mauricio\Ana Lobo      | Encontrar receitas prontas                 | Para alcançar resultados almejados |
|Lorena Martins       | Inserir plano nutricional                 | Controlar calorias ingeridas no dia. |
|Lorena Martins\Ana Lobo      | Consultar informações nutricionais dos alimentos                 | Controlar calorias ingeridas no dia. |




## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| A aplicação deve permitir que o usuário calcule necessidade nutricional diária. | ALTA | 
|RF-002| A aplicação deve permitir que o usuário consulte informações nutricionais dos alimentos   | ALTA |
|RF-003| A aplicação deve permitir que o usuário consulte receitas já prontas com infomações nutricionais   | ALTA |
|RF-004| A aplicação deve permitir que o usuário adicione e edite receitas próprias  | ALTA |
|RF-005| A aplicação deve permitir que o usuário insira e controle seu plano nutricional  | ALTA |
|RF-006| A aplicação deve permitir que o usuário registre controle de estoque dos itens na sua despensa   | ALTA |
|RF-007| A aplicação deve permitir que o usuário encontre receitas com os itens que ja possui na despensa   | ALTA |
|RF-008| A aplicação deve ter área do usuário, com login e senha  | ALTA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deve ser publicada em ambiente acessível publicamente na internet | ALTA | 
|RNF-002| A aplicação deve ser de fácil usabilidade |  MÉDIA | 
|RNF-003| A Aplicação deve ser responsiva, podendo ser utilizada em diversos dispositivos |  ALTA | 
|RNF-004| A Aplicação deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft edge)|  ALTA | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre letivo, não podendo extrapolar a data de 11/12/2022. |
|02| A aplicação deverá se restringir a programação com a linguagem C# para back-end. Devendo utilizar Framework ASP.NET Core MVC.       |
|03| O site deve utilizar como sistema de gerenciamento de banco de dados (SGBD) um sistema compatível com o ambiente de desevolimento e publicação.        |
|04| A aplicação deve obedecer a Lei Geral de Proteção de Dados Pessoais (LGPD) para compartilhamento e armazenamento de dados sensíveis.       |
|05| A equipe não pode subcontratar o desenvolvimento do trabalho.        |





## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
