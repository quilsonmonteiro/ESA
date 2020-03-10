# Pincípios de Segurança #



A “Arquitetura de Segurança da Informação” descreve os serviços de segurança, que proveem, controles de segurança para atender os pilares de Confidencialidade, Integridade e Disponibilidade.

Os pilares de segurança, também conhecidos como CID (Confidencialidade, Integridade e Disponibilidade), serão compostos por múltiplas soluções, formando *“Defesa em Camadas”*, por meio de controles de segurança no âmbito de *“Network Security”*; *“Host Security”*; *“Application Security”*; *“Data Security”* e *“Least Privilege”*  

Confidencialidade: propriedade que limita o acesso a informação tão somente às entidades legítimas, ou seja, àquelas autorizadas pelo proprietário da informação;

Integridade: propriedade que garante que a informação manipulada mantenha todas as características originais estabelecidas pelo proprietário da informação, incluindo controle de mudanças e garantia do seu ciclo de vida (Corrente, intermediária e permanente).

Disponibilidade: propriedade que garante que a informação esteja sempre disponível para o uso legítimo, ou seja, por aqueles usuários autorizados pelo proprietário da informação;


## Defesa em Camadas - Security Layers of Defense ##


O conceito de “Defesa em Camadas” parte da premissa que os controles de segurança individuais, são incompletos e insuficientes e múltiplos mecanismos de controle implementados um após o outro, através de camadas ou perímetros, tornarão a solução de segurança mais completa e robusta.


Este princípio abrange a integração de diversos controles de Segurança, como também o Design de uma Arquitetura em camadas, sempre agregando outros controles como por exemplo:


* Segregação de redes/VLAN, 
* Firewall, 
* IPS, 
* NLB / Netscale,
* Ant-DDOS,
* API Protection,
* WAF,
* DLP,
* Web Filter,
* Criptografia, etc.



## Least Privilege - Privilégios mínimos ##


Privilégios mínimos limitam o potencial de danos por acidente, erro ou uso não autorizado do sistema.

Limitar o nível de acesso ao mínimo necessário para realizar as atividades sobre sua responsabilidade;

O acesso deve ser concedido apenas para a quantidade mínima de tempo necessário;

Implementar o princípio de privilégios mínimo visa fornecer as permissões limitadas apenas o trabalho deles (business needed);

Privilégios mínimos devem ser considerados em um início de novas iniciativas e na organização (soluções existentes);

Mudanças nas funções dos empregados devem implicar na revisão dos acessos privilégios da conta de usuário do funcionário;



## Data Security Lifecycle – Ciclo de vida da Informação ##


No ciclo é importante que a classificação e “rotulação” da informação seja feita, para que controles realizados através de DLP; Mascaramento; Criptografia; Tokenização; Ofuscação e DRM sejam efetivos. 

Criação de Dados – estabelecer classificação e rotulação para realização de Discovery através dos métodos de Label-Based Discovery; Metadata-Based Discovery; Content-Based Discovery.

Armazenamento – Estabelecer os controles de acesso, Mascaramento, Criptografia, etc, junto com Autenticação e Autorização.

Uso dos Dados – Proteger os dados de maneira fim-a-fim (Controle de acesso, criptografia em trânsito, etc), assim como o monitoramento das atividades.

Compartilhamento de Dados - Estabelecer o direcionados por privilégios mínimos e o “need to know”.

Arquivamento – Os dados que são arquivos também deverão conter os controles descritos no processo de Armazenamento.

Destruição – Fazer o descarte dos dados, de forma segura, uma vez que sua finalidade ao processo de negócio tenha se encerrado.



## Security Shift Left ##


O “Shift Left” prover processos e modelos de segurança, para automação de controles em todos os estágios de uma aplicação, como por exemplo, Stack de Rede; Host; Contêineres; Servidores; provisionamento em Cloud; Codificação e Acesso.


