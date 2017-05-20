#SEBO - Plano de Gerenciamento de Tempo (PGT)

## 1. Objetivo do Documento

O Plano de Gerenciamento do Tempo tem por objetivo estabelecer as políticas, os procedimentos e a documentação para o planejamento, desenvolvimento, gerenciamento, execução e controle do cronograma do projeto SEBO.

## 2. Método de Gerenciamento do Tempo

Gerenciar o tempo do projeto requer um Plano de gerenciamento do cronograma aprovado englobando os principais processos de Gerenciamento do tempo do projeto definidos abaixo. O Plano de gerenciamento do cronograma é desenvolvido e aprovado durante a fase de planejamento do projeto para orientar a equipe do projeto sobre como os processos relacionados ao tempo serão executados, controlados, monitorados e encerrados.

### 2.1 Processos de Gerenciamento do Tempo

#### Definir as atividades

	Identificar as atividades específicas que devem ser executadas para produzir as entregas do projeto.

#### Sequenciar as atividades

	Identificar e documentar as relações de dependência entre as atividades.

#### Estimar os recursos das atividades

	Estimar o tipo e quantidade dos recursos necessários para executar cada atividade.

#### Estimar as durações das atividades

	Estimar a quantidade de períodos de trabalho que serão necessários para completar cada atividade.

#### Desenvolver o Cronograma

	Analisar a sequência das atividades, sua duração, seus recursos e suas restrições para criar o cronograma do projeto.

#### Controlar o Cronograma

	Controlar as mudanças no cronograma. 

### 2.2 Documentos padrozinados do Tempo

| Documento | Descrição   | Template  |
|:---------------:|:-------------:|:-----------:|
| Cronograma do Projeto | Template de cronograma em conformidade com a metodologia de gerenciamento de projetos | |

### 2.3 Ferramentas

* Microsoft Office Excel ou LibreOffice Calc
* Microsoft Office Word ou LibreOffice Writer

### 2.4 Papéis e Responsabilidades da Equipe do Projeto

|ID do Papel | Papel | Responsabilidades  |  Responsável | 
|:-----------:|:-------------:|:-----------:|:-----------:|
| R1 | Gerente de Projeto | Gerenciar todo o andamento do Projeto e seu sucesso | Cauã Pessoa |
| R2 | Gerente de Configuração | Gerenciar artefatos do projeto | Cauã Pessoa |
| R3 | Gerente de Requisitos | Elicitar, monitorar e gerenciar os requisitos e partes interessadas | Rhenan Konrad |
| R4 | Gerente de Qualidade | Assegurar a qualidade e adequação ao processo, qualidade do projeto e produto | Victor Stillo |
| R5 | Designer | Modelagem da arquitetura do software | Affonso Geisel |

## 3. Definir e Sequenciar as atividades

* 1. Abertura do Projeto - TAP
* 2. Definição do Plano de Configuração do Projeto - PGC
* 3. Organizar partes interessadas - PPI
* 4. Planejar a Integraçao - PGI
* 5. Definição do Escopo - PGE
* 6. Organização do Cronograma - PGT
* 7. Organização do Orçamento - PGO
* 8. Gerenciar Qualidade - PGQ
* 9. - 

## 4. Estimação dos Recursos e Duração das Atividades

| Atividade | Recursos | Duração (dias) |
|:-------------:|:-------:|:-------:|
| TAP | R1, R2, R4 | 7 |
| PGC | R1, R2 | 3 |
| PPI | R2 | 7 |
| PGI | R5 | 7 |
| PGE | R3, R4 | 7 |
| PGT | R1 | 7 |
| PGO | R1, R4, R3 | 7 |
| PGQ | R4 | 7 |

## 5. Cronograma

| ID da Atividade | Dependência   | Atividade   | Início     | Tempo Previsto (dias)   | Término Real   |
|:---------------:|:-------------:|:-----------:|:----------:|:----------:|:-----------------------:|
| AT01 | | Termo de Abertura do Projeto  | 01/04/2017 | 30 | 28/04/2017 | 
| AT02| | Estabelecer Plano de Configuração do projeto | 05/04/2017 | 7 | 28/04/2017 | 
| AT03 | AT01| Planejamento das Partes Interessadas | 05/05/2017 | 7 | 12/05/2017 | 
| AT04 | AT01 | Planejamento da Integração | 04/05/2017 | 7 | 19/05/2017 |
| AT05 | AT01, AT03| Planejamento do Escopo | 12/05/2017 | 7 | 19/05/2017 | 
| AT06 | AT05| Planejamento do Gerenciamento do Tempo | 12/05/2017 | 7 | 19/05/2017 |
| AT07 | AT05| Gerenciamento dos Custos do Projeto | 19/05/2017 | 7 | - | 
| AT08 | AT05, AT01, AT03 | Gerenciamento da Qualidade do Projeto | 19/05/2017 | 7 | - |


