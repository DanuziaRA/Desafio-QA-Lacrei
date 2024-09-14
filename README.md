# Desafio Quality Assurance Lacrei Saúde

Este repositório contém a documentação de teste do **Desafio de QA da Lacrei Saúde.** 

Para tanto, detalha-se:

* Especificação de Casos de Teste (https://github.com/DanuziaMoreira/Desafio-QA-Lacrei/blob/main/ESPECIFICA%C3%87%C3%83O%20DE%20CASOS%20DE%20TESTES.pdf) ; 
* Especificações de Procedimento de Teste (todos os fluxos indicados no desafio) (); 
* Relatório de Status de Casos de Teste (); 
* Relatório Gráfico de Execução de Casos de Testes (); 
* Relatório de Rastreabilidade de Casos de Testes (); 
* Evidências (gravação das telas) de execução dos casos de testes (); 
* Cenários de testes:
  a) desempenho (); \
  b) acessibilidade ();\
  c) responsividade mobile considerando dois tipos de dispositivos (); e \
* Falhas e Melhorias (). 

Além disso, diante do escopo do desafio apresenta-se os cenários de teste de desempenho; acessibilidade e responsividade mobile considerando dois tipos de dispositivos, as recomendações para correção de bugs e sugestões de melhorias contínuas da plataforma.


## Introdução

A presente documentação tem como objetivo apresentar o conjunto abrangente de casos de teste desenvolvidos para o **Desafio de QA da Lacrei Saúde**, a fim de avaliar a funcionalidade e a usabilidade do aplicativo/plataforma digital Lacrei Saúde. Cujo bojo foi criar casos de testes de uma variedade de fluxos críticos, abrangendo desde o processo de cadastro e pós-cadastro até a funcionalidade de busca e contato com profissionais, edição de perfil e as funcionalidades de recuperação de senha em dispositivos móveis.

Além dos testes funcionais, elabora-se cenários para avaliar o desempenho do aplicativo, assegurando que ele opere de maneira eficiente sob diferentes condições de carga. Ademais, realiza-se uma análise de acessibilidade para garantir que o aplicativo seja utilizável por todos os usuários, independentemente de suas necessidades específicas. A responsividade do aplicativo foi testada em dois tipos de dispositivos móveis, assegurando que a experiência do usuário seja consistente e otimizada.

Acredita-se que esta análise fornecerá uma visão clara sobre a robustez e a qualidade da aplicação. 

## Metodologia e Ferramentas

Neste documento, segue-se o padrão IEEE 829 elaborado pela IEEE (Institute of Electrical and Electronic Engineers), fundação organizacional sem fins lucrativos responsável por definir padrões para praticas presentes na engenharia de software, no que tange ao processo de testes e controle da qualidade, definição de documentos consistentes, adequados, em registros capazes de prover condições de análise dos resultados obtidos ao longo dos testes funcionais.

As ferramentas utilizadas no processo de teste são listadas a seguir:
                • Site Lacrei Saúde utilizado para elaboração do planejamento dos casos de teste, disponível no endereço https://paciente-staging.lacreisaude.com.br/ 
                • O Jira Software™  foi a ferramenta para o planejamento, metodologia e gestão da execução do projeto. 
                • O aplicativo Zephyr Scale© foi escolhido como gerenciador dos casos de testes, uma vez que se integra ao software Jira, permitindo a coordenação e rastreio de atividades e resultados dos casos. 
                • Os fluxos dos casos de testes foram executados na plataforma Sauce Labs©  unificada para testes automatizados e monitoramento de erros para aplicativos móveis, integrado a estrutura de automação Appium Serve©.


## Caso de Teste
1. Criar casos de testes para os fluxos citados e gravar a tela realizando a ação: \
Fluxo da pessoa usuária (Versão Mobile): \
  **Cadastro da pessoa usuária**: Cadastro → Pós Cadastro → Buscar Profissional. \
  **Buscar uma pessoa profissional:** Buscar Profissional → Contatar Profissional. \
  **Editar Perfil um dado da Pessoa Usuária**: Inserir as informações solicitadas com troca de dados.\
  **Esquecer a senha da pessoa usuária e receber por e-mail.**\
  **Testar reset de senha.**


## Referência 
1. IEEE Standard for Software Test Documentation. Disponível em:<https://ieeexplore.ieee.org/document/741968/> Acesso em: 10 de setembro de 2024.
