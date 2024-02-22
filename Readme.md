# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: Imediato
Empresa: Abstergo Industries     
Responsável: Fernando Augusto Pereira

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Fernando Augusto Pereira. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 4 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- AWS VPC / subnets
- Criacao de um rede privada para uso exclusivo da farmacia, com o uso integrado das subnets.
- Ha princio sera criado somente um VPC para a implemantacao de tres subnet, uma para o AWS EC2 Auto Scaling e uma segunda para o Amazon Aurora MySQL e uma terceira para Amazon S3 Intelligent - Tiering. Desta forma as tres ferramentas estao protegidas de qualquer intempere.

Etapa 2: 
- AWS EC2 Auto Scaling
- Criacao de Maquinas para a migracao do sistema. 
- Com o AWS EC2 Auto Scaling dentro da VPC poderemos criar uma maquina virtual onde sera colocada a aplicacao, deste modo o AWS EC2 Auto Scaling automaticamente aumetara e diminuira a quantidade de maquinas para o uso, sendo o minimo de 1 maquina e no maximo 10 maquinas.

Etapa 3: 
- Amazon Aurora MySQL
- Banco de dados sem servidor escalavel.
- Junto com o AWS EC2 Auto Scaling implementaremos um servidor Amazon Aurora MySQL para que este possa crescer ou diminuir com a demanda, assim como as maquinas virtuais com a aplicacao o banco de dados tambem podera crescer sem a nescessidade de manutencao. Deste modo assim diminuiremos os custos destas manutencao.

Etapa 4: 
- Amazon S3 Intelligent - Tiering
- Armazenamente de Arquivos
- Ferramenta para o armazenamento de arquivos de backup e em futuras features do aplicativo. Esta ferramenta consiste no armazenamento de pequenos arquivos não ultrapassando os 1000 objetos é gratuita, este armazenamento inicial deve ser suficiente mas caso haja a nescessidade é possivel criar bots para que monitorem esses valor e mantenha o bucket na carga minima.



## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado *AWS VPC, AWS EC2 Auto Scaling, Amazon Aurora MySQL e Amazon S3 Intelligent - Tiering*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.


Assinatura do Responsável pelo Projeto: 

                                            Fernando Augusto Pereira