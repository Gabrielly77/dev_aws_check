# dev_aws_check

⚡ CHECK RÁPIDO — AWS DEVELOPER CERTIFICATION! ⚡
🧠 SERVIÇOS PRINCIPAIS PRA DEV:
Lambda → Função serverless (executa código sem servidor)

API Gateway → Cria e gerencia APIs

DynamoDB → Banco NoSQL ultra rápido

SQS → Fila (desacopla serviços)

SNS → Notificações (push, email, SMS)

EventBridge → Orquestra eventos (tipo um "telefone sem fio da nuvem")

Step Functions → Fluxos de trabalho serverless (organiza Lambdas, por exemplo)

🚀 CÓDIGO E DEVOPS:
CodeCommit → Git gerenciado

CodeBuild → Build (compila, testa)

CodeDeploy → Deploy automatizado

CodePipeline → Integra tudo (CI/CD completão)

☁️ ARQUITETURA E PADRÕES DE DESENVOLVIMENTO:
Retry, Dead Letter Queue (DLQ) → Quando falha, joga pra fila morta

Fallback, Circuit Breaker, Timeout → Resiliência nas aplicações

Idempotência → Mesma requisição feita N vezes → mesmo resultado (super cai na prova!)

Pagination → Respostas grandes (Dynamo, S3, API...) vêm paginadas

🔐 SEGURANÇA PRO DEV:
IAM Roles pra serviços (Lambda, EC2, etc.)

Secrets Manager vs Parameter Store:

Secrets Manager → Senhas, API keys sensíveis (rotação automática)

Parameter Store → Configs não tão sensíveis ou parâmetros simples

KMS (Key Management Service) → Criptografia de dados

💾 DADOS E CACHE:
DynamoDB → NoSQL, ultra rápido, escalável

DAX → Cache pro DynamoDB (acelera leitura)

S3 → Armazenamento de objetos

ElasticCache (Redis ou Memcached) → Cache em memória (resposta mais rápida)

🔥 OBSERVABILIDADE E MONITORAMENTO:
CloudWatch → Logs, métricas, alarmes

X-Ray → Rastreia requisições, vê gargalos e desempenho

CloudTrail → Auditoria das ações na conta AWS

🛠️ INFRA COMO CÓDIGO:
CloudFormation → Template de infraestrutura

CDK (Cloud Development Kit) → Infra como código usando linguagem de programação (Python, JS, etc.)

StackSets → Deploy de CloudFormation em várias contas/regiões

⚙️ DESENVOLVIMENTO SERVERLESS:
Lambda + API Gateway + DynamoDB + S3 → Combo clássico na prova!

Lambda → Timeout máximo: 15 minutos ⏳

Retry automático → Funciona diferente se for invocação síncrona (não tenta de novo) ou assíncrona (tenta até 2x)

💥 PERGUNTAS QUE SEMPRE CAEM:
CORS no API Gateway

Dead Letter Queue (DLQ) pra SQS/Lambda

Idempotência nas APIs

Pagination em respostas grandes

Retry e fallback pra resiliência

Segurança com IAM roles e Secrets Manager

🎯 DICAS DE OURO NA PROVA:
✅ Lê bem as palavras: "EXCETO", "MELHOR", "MAIS BARATO", "MAIS SIMPLES"
✅ Atenção na diferença de services parecidos (SNS ≠ SQS, Secrets ≠ Parameter Store)
✅ Quando falar em eventos entre serviços → EventBridge ou SNS/SQS
✅ Deploy → sempre pensar em CodePipeline + CodeDeploy
✅ Performance de leitura no DynamoDB? DAX ou ElasticCache
