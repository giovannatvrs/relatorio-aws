# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 27/08/2025<br>
Empresa: Abstergo Industries<br>
Responsável: Giovanna Tavares

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Giovanna Tavares**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto 
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:
- Nome da ferramenta: Amazon EC2 + AWS Auto Scalling 
- Foco da ferramenta: O Amazon Elastic Compute Cloud (EC2) é um serviço que disponibiliza um servidor de capacidade computacional, escalável e sob demanda. De forma simplificada, fornece uma máquina virtual para rodar uma determinada aplicação, sem a necessidade de comprar um hardware novo e configurá-lo manualmente, com possibilidade de escolher a quantidade de memória, armazenamento e processamento. No aspecto financeiro, é possível reduzir custos ao substituir servidores físicos por um modelo de pagamento flexível, pois sua  é possível aumentar e reduzir a capacidade. O AWS Auto Scalling atua junto com EC2, ajustando os recursos computacionais de forma automática para atender a demanda em tempo real. 
- Descrição de caso de uso: A Abstergo Industries utilizava servidores locais e fixos, o que gerava altos custos de manutenção de infraestrutura, como servidores, data centers, tráfego e energia, além de desperdício de capacidade em horários de baixa demanda. Ao migrar para a Amazon EC2, há mais flexibilidade e escabilidade. Com a integração do AWS Auto Scalling, a plataforma virtual da farmácia da empresa Abstergo Industries pode escalar seus recursos automaticamente durante uma promoção de grande porte e reduzir novamente após o evento, evitando gastos com capacidade ociosa.

Etapa 2:
- Nome da ferramenta: Amazon S3
- Foco da ferramenta: Amazon Simple Storage Service (S3) é um serviço de armazenamento de objetos (arquivos e metadados) em buckets, containers para armazenar objetos, garantindo que cada um deles sejam escaláveis. Isso permite que os usuários guardem e recuperem uma grande quantidade de dados de forma rápida, segura e fácil. No projeto, foi utilizado como armazenamento de arquivos estáticos, como imagens de produtos e backup. Além disso, a escabilidade auxilia no uso continúo dos dados para análise e entedimento do comportamento do consumidor, contribuindo para a tomada de decisões estratégias que tragam resultados eficientes para a empresa.
- Descrição de caso de uso: A empresa não possui a implementação de computação em nuvem, guardando dados da plataforma em um servidor local. Com a utilização do Amazon S3, elimina-se a necessidade de servidores físicos e ocorre a diminuição de custos de infraestrutura e manutenção.   
- Bônus: Os dados armazenados no S3 também podem ser utilizados posteriormente para análises de comportamento de consumo, contribuindo para estratégias de marketing mais eficientes e personalizadas.

Etapa 3:
- Nome da ferramenta: AWS Lambda
- Foco da ferramenta: AWS Lambda é um serviço de computação serverless, permitindo a execução de códigos sem a necessidade de gerenciar servidores. Essa solução é bastante utilizada em automações, processamento de eventos e criação de APIs escaláveis. Além disso, o modelo de cobrança é vantajoso para reduzir custos fixos, pois o pagamento é apenas pelo tempo de execução do código e elimina gastos com infraestrutura ociosa. 
- Descrição de caso de uso: A Abstergos Industries mantinha servidores ativos apenas para atividades rotineiras, como scripts de automação que eram feitos ocasionalmente. Com a substituição pelo AWS Lambda, essas tarefas passaram a rodar apenas quando era realmente necessário.


## Conclusão
A implementação de ferramentas na empresa **Abstergo Industries** tem como esperado redução de custos de infraestrutura, utilização de recursos de forma flexível e escalável, armazenamento seguro de dados, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade das utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa. 

## Anexos
https://aws.amazon.com/pt/s3/cost-optimization/
https://aws.amazon.com/pt/ec2/cost-and-capacity/ 
