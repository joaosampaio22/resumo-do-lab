# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO


Modelos de Nuvem
Nuvem Pública: serviços oferecidos por empresas como Google, AWS, etc. Você compartilha a estrutura com outros, mas tem seu próprio espaço.
Nuvem Privada: só a sua empresa usa. Mais controle e segurança, mas custa mais.
Nuvem Híbrida: usa a pública e a privada conforme a necessidade.

CapEx vs OpEx
CapEx (Capital Expenditure): gasto com compra de equipamentos e infraestrutura. Alto custo inicial.
OpEx (Operational Expenditure): gasto com uso contínuo, como pagar mensalmente por serviços em nuvem. Sem custo alto no começo.
Resumo: nuvem troca grandes investimentos (CapEx) por pagamentos mensais (OpEx), trazendo mais flexibilidade.


Benefícios da Computação em Nuvem
Escalabilidade: cresce junto com o seu negócio. Se precisar de mais recursos, é só aumentar.
Elasticidade: ajusta os recursos automaticamente conforme o uso – aumenta em picos e reduz quando não precisa.
Confiabilidade: alta disponibilidade e recuperação rápida em caso de falhas. Os serviços continuam funcionando.
Previsibilidade: custos e desempenho mais fáceis de controlar e planejar.
Segurança: dados protegidos com criptografia, controle de acesso e monitoramento constante.
Governança: políticas e regras claras para controlar como os recursos são usados.
Gerenciabilidade: fácil de monitorar, configurar e manter, com painéis e ferramentas centralizadas.

Resumo sobre IaaS, PaaS e SaaS
IaaS (Infrastructure as a Service)
Infraestrutura pronta (servidores, rede, armazenamento).
Você controla o sistema operacional e o que roda nele.
Exemplo: máquinas virtuais (Azure VM, AWS EC2).

PaaS (Platform as a Service)
Plataforma pronta para você desenvolver e hospedar aplicações.
Sem se preocupar com servidores ou sistema operacional.
Exemplo: Azure App Service, Google App Engine.

SaaS (Software as a Service)
Software pronto, você só usa.
Não precisa instalar nada, é acessado pela web.
Exemplo: Gmail, Microsoft 365, Trello.



Como eu criei um banco de dados no Azure
Entrei no portal do Azure.
Cliquei em “Criar recurso” e selecionei a opção de “Banco de dados”.
Escolhi o tipo de banco que queria (no meu caso, por exemplo, um SQL Database).
Preenchi as informações básicas:
Nome do banco de dados
Grupo de recursos
Criei um novo servidor com nome, login e senha
Escolhi a região (local do data center)

Depois, configurei o plano de desempenho, de acordo com o que eu precisava.
Por fim, cliquei em “Revisar + Criar” e depois em “Criar”.
Depois que o recurso foi criado, consegui acessar o banco pelo portal do Azure e também conectar com uma ferramenta como o Azure Data Studio para gerenciar os dados.
