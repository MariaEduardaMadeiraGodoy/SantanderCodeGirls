IaaS 
- software como serviço
- maior parte é desenvolvida e pertencente a uma empresa;
    Exemplo: num churrasco, você seria responsável pela comida e pela bebida, porém uma empresa seria responsável pelo espaço, churrasqueira e música.

PaaS
- Inverso direto do IaaS
- maior parte é sua, ou seja, você desenvolve o serviço através de um recurso de uma plataforma;
    Exemplo: em uma festa, você seria responsável pelo espaço, pela música e pela comida e uma empresa seria responsável pelas bebidas.

SaaS
- Versão bem conhecida pelo público geral
- Empresa entra com todo o serviço e você apenas usufrui dele;
    Exemplos: Gmail, Spotify, Netflix, entre outros serviços.

Regions
- Regiões geográficas contendo ***Availability Zones*** que são data centers independentes fisicamente, porém conectados logicamente garantindo alta disponibilidade.
- Quando vamos escolher uma Region, devemos levar em consideração: 
    - o compliance, para não infringir as leis do local escolhido;
    - a disponibilidade de serviços, para não escolher um serviço que não está disponível na região desejada;
    - o custo;
    - a latência, pois se escolher uma região muito distante o serviço fica lento.

EC2, ou seja, Elastic Compute Cloud, são máquinas virtuais na AWS compostas por: 
- CPU; 
- Memória;
- Disco;
- Rede;
- Sistema operacional.

EBS, ou seja, Elastic Block Store:
- Armazenamento em blocos; 
- Pode ser anexado em qualquer instância EC2;
- Possui uma capacidade de expansão rápida.

S3, ou seja, Simple Storage Service
- Forma de armazenamento de objetos em nuvem;
- Conseguimos organizar e recuperar grandes volumes de dados de maneira segura;
- Possui algumas classes onde conseguimos economizar nos custos.


Como poupar custos e evitar gastos desnecessários?

Ótimas formas de poupar cursos através da otimização de recursos são: 
- Desligando instâncias não utilizadas;
- Removendo recursos ociosos ou não utilizados;
- Escalar recursos verticalmente, acrescentando ou reduzindo a capacidade de um recurso em uma mesma instância ou;
- Escalar recursos horizontalmente, aumentando ou diminuindo o número de recursos.

