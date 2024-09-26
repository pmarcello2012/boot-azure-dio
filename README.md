# boot-azure-dio
Este repositório contém conteúdos aprendidos do bootcamp Microsoft Azure Essentials da DIO

Neste bootcamp aprendi até o momento quais são os benefícios oferidos pela nuvem
Flexibilidade e escalabilidade, Segurança, Alta Disponibilidade, Governança e Gerenciamento, Redução e maior controle de custos.
No geral a compuação em nuvem proporciona que as empresas inovem com mais rapidez pois a nuvem oferece recuros flexíveis para atender a essa demanda.

Para criação de um Banco de Dados na Azure
Seleciono +Criar
Escolho um nome: testedba1
Escolho a localização
Seleciono como se dará a autenticação: Microsoft Entra (por exemplo)
Definir um administrador

Seleciono o modelo de redundância (SLA)

Observar que com base no que foi configurado qual o valor mensal que será cobrado pelo serviço.
Lembrando que o Azure disponibiliza uma calculdadora para gerenciar os custos cobrados pelos serviços.

Temos que estar atentos aos serviços oferecidos pelo Azure, funções e funionalidades.

O Azure oferece capacidade robusta de armazenamento e também ferramentas robustas para transferências de dados, com segurança e confiabilidade.
Arquitetura e Serviços do Azure

Serviços de Diretório

Métodos de Autenticação

Modelos de Segurança


Microsoft Entra - os funcionários entram para acessar os recuros, onde o logon é único (SSO.
Gerencia os aplicativos e negócios B2B.

Comparar a autenticação e a autorização

Identifica a pessoa ou serviço buscando acesso a um recurso;
Solicita credenciais de acesso legítimo;
Base para criar princípios de identidade e controle de acesso seguros;

Autorização

Determina o nível de acesso de uma pessoa ou serviço automático;
Define quais dados eles podem acessar e o que podem fazer com eles;

Modelos de Segurança


Microsoft Entra - os funcionários entram para acessar os recuros, onde o logon é único (SSO.
Gerencia os aplicativos e negócios B2B.


Comparar a autenticação e a autorização

Identifica a pessoa ou serviço buscando acesso a um recurso;
Solicita credenciais de acesso legítimo;
Base para criar princípios de identidade e controle de acesso seguros;

Autorização

Determina o nível de acesso de uma pessoa ou serviço automático;
Define quais dados eles podem acessar e o que podem fazer com eles;

Autenticação Multifator

Fornece segurança adicional para as identidades, exigindo dois ou mais elementos
para autenticação completa.

B2B do Microsoft Entra External ID

Parceiros, fornecedores, outros colaboradores fora da instituição;

B2B empresa para empresa

Acesso Condicional

Associação de usuário ou grupo;
Local do IP;
Dispositivo;
Aplicativo;
Detecção de Risco;

Controle de Acesso Baseado em função - RBAC do Azure

Gerenciamento de acesso de granulidade fina;
Divida as tarefas  dentro da equipe e conceda somente a quantidade
de acesso de que usuários precisam para trabalhar;
Habilite o acesso ao portal do Azure e o controle de acesso aos
recursos;

Modelo de Confiança Zero

Proteja os Ativos onde eles estiverem com a Confiança Zero

Verificar de forma explícita, sempre usar requisito de menor privilégio.

-Segurança física;
-Identidade e acesso;
-Perímetro;
-Rede;
-Computação;
-Aplicativo;
-Dados;

Proteção completa

Abordagem em camadas para proteger sistemas de computador
Fornece vários níveis de proteção
Ataques são isolados

Microsoft Defender for Cloud
Serviço de monitoramento que fornece proteção contra ameaças nos
datacenters do Azure

Custos Azure - https://azure.microsoft.com/en-us/pricing/tco/calculator/

Calculadora do TCO (Custo Total de Propriedade)

Defina as suas cargas de trabalho
Ajuste suposições
Exibe relatórios Salvos
Advisor tras sugestões de melhorias relacionadas aos custos.

Bloqueios de Recursos

Proteja os recursos do Azure de exclusão ou modificação acidental
Gerenciar bloqueios na assinatura, grupo de recursos ou níveis de
recursos individuais dentro do Portal do Azure.

Bloqueios sempre caem na prova

Tipos de Bloqueio
excluir / ler = sim / atualizar = sim / excluir = não

ReadOnly  ler = sim / atualizar = Não / Excluir  = Não


Portal de Confiança do Serviço

Link aberto ao público que inclui todas as informações.

Microsoft Purview

É uma família de soluções de governança, risco e conformidade de dados
que ajuda a obter uma única exibição unificada em seus dados. O Microsoft Purview
reúne insights sobre seus dados locais, multinuvem e de software como serviço.

Descoberta de dados automatizada
Classificação de dados confidenciais
Linhagem de dados de ponta a ponta



Ferramentas para interagir com o Azure

- Portal Azure

- Azure PowerShell

- Azure Cloud Shell

- Interface de lina de Comando (CLI)

O Azure Arc é um serviço da Microsoft que permite gerenciar e governar recursos de TI em diferentes ambientes, como nuvem, datacenters, edge e dispositivos.
Gerenciamento mais assertivo.

o ARM (Azure Resource Manager) é como se fosse um grande funil, recebe requisições e 
cria meus recursos.

Infraestrutura como código
- Garante a consistência na implantação em todo o ecossistema de nuvem.
Gerencie a configuração em escala.

Provisionar os ambientes de forma muito mais rápida.
Modelos do ARM

São arquivos JSON (Javascript Object Notation) que podem ser usados
para criar e implantar a infraestrutura do Azure sem a necessidade
de escrever comandos de programação.

Sintaxe declarativa
Resultados repetíveis
Orquestração
Arquivos modulares
Validação integrada
Código Exportável
Modelo enviado
Infraestrutura como código sem modelo

BICEP

Bicep modelo de linguagem criado pela Microsoft onde podemos criar nossos recursos,
somente aceito no Azure.
















