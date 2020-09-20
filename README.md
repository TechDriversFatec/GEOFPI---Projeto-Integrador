# GEOFPI---Projeto-Integrador
Projeto Integrador proposto pela FATEC - São José dos Campos com o seguinte tema: Desenvolver sistema “mini-ETL”, do inglês Extract Transform Load, com interface gráfica de usuário (GUI), visando armazenamento e recuperação de dados georreferenciados em banco de dados geográficos.

## Dev Team
* Márcio Geraldo de Sousa (Product Owner)
* Fernanda Corrente Marques (Scrum Master)
* Jodan Lima Galas (Dev Team)
* Fabrício Cursino dos Santos (Dev Team)
* Edson Brendon de Oliveira (Dev Team)
* Hyury Lins de Vasconcelos (Dev team)
* Lucas de Lima Chaves (Dev team)
## Índice
* [O que é o GEOFPI](#o-que-é-o-geofpi)
* [Ferramenta Desenvolvida](#ferramenta-desenvolvida)
* [Benefícios](#benefícios)
* [Product Backlog](#product-backlog)
* [Tecnologias](#tecnologias)
* [Plano de Ação](#plano-de-ação)

## O que é o GEOFPI?
A carga de dados georreferenciados é uma atividade contínua durante os projetos que utilizam diversos software GIS para organizar e fazer o processamento de imagens de satélite. O resultado desse processamento, a depender do projeto, é o que se utiliza para desenvolvimento de produtos. A solução escolhida foi a de ferramentas de ETL espacial GEOFIP, cuja estrutura conceitual é apresentada na figura abaixo.

imagem

## Ferramenta Desenvolvida
Essa ferramenta será configurada para entender os arquivos de formato shapefile e realizar conversões, usando regras definidas na etapa de planejamento, buscando compatibilidade com normas oficiais, e carregá-los e manipulá-los no banco de dados geográficos PostgreSQL com extensão Postgis, de acordo com a modelagem física definida pelo cliente. Também realiza o processo inverso de gerar um arquivo shapefile a partir de uma tabela do banco de dados PostgreSQL.
## Benefícios 
* Melhoria de aplicações para inteligência empresarial focada na capacidade de gerenciar dados espaciais.
* Suporta o processamento de grande volume de dados do tipo Shapefile.
* Transforma dados em insights com análises incorporáveis.
* Aprimora a análise dos negócios e tem influência nas decisões corporativas, permitindo analisar, visualizar e planejar.

## Product Backlog (*User story*)


| Quem | O que? | Para |
| ----------------------- | ---------------------------------|---------------------------------------------------------|
|    Analista de Dados Espaciais   | Gostaria da Prototipação da Ferramenta desenvolvida. | Para ter uma visão global do desenvolvimento do produto, verificar o entendimento das funcionalidades da ferramenta e fazer possíveis apontamentos de melhorias na usabilidade.|
|    Analista de Dados Espaciais   |Gostaria da interface gráfica fazendo a extração dos dados Shapefile e a conexão com o banco de dados|Para iniciar o processo de utilização da função “de para” da ferramenta.|
|    Analista de Dados Espaciais   |Gostaria que a ferramenta execute e transforme os dados e faça a parametrização com o Banco de Dados| Para atender as necessidades do negócio.|
|    Analista de Dados Espaciais   |Gostaria de um ambiente de desenvolvimento de tarefas e transformações geográficas e que o sistema realize o processo inverso de conversão de dados| Para atender as necessidades do negócio. E trazer soluções rápida de desenvolvimento de produtos para sistemas.|
|    Analista de Dados Espaciais   |Gostaria de uma ferramenta que me forneça condições de aplicar regras de transformação nos dados  | Para desenvolver novos produtos de acordo com a solicitação dos setores.| 
|    Analista de Dados Espaciais   |Gostaria de uma ferramenta intuitiva, de fácil usabilidade,  com manuais de instruções| Para melhorar a experiência do usuário com a ferramenta|

Imagem do product Backlog

## Plano de Ação

Imagem Linha do tempo

## Tecnologias
Imagem 
## Product Backlog
Imagem
# Sprint 1

Entrega do protótipo da interface gráfica contendo a tela inicial, instruções de uso do sistema, sobre a ferramenta, a opção de carregar o arquivo em formato shapefile e transformação dos dados para parametrização com o banco de dados PostgreSQL com extensão Postgis.
## Requisitos Atendidos
* [RF001] A prototipação da ferramenta, para ter uma visão global do desenvolvimento do produto, verificar o entendimento das funcionalidades e fazer possíveis apontamentos de melhorias na usabilidade.
* [RNF001] O protótipo deve permitir que o usuário insira login, senha e endereço de conexão para se conectar com o Banco de Dados.
* [RNF 003] O protótipo deve permitir a verificação da página inicial e ter um botão com a função “Sobre” que explicará o que o sistema faz.

## Valor da Sprint 
* Facilita a visualização do produto para o cliente desde a fase inicial. 
* Possibilita receber o feedback em tempo ágil. 
* Facilita o levantamento de requisitos e funcionalidades. 
* Possibilita estimar de forma mais precisa a complexidade e tempo de desenvolvimento.
