# Introdução ao Microsoft Azure
## O que é o Azure?

Azure é a cloud da Microsoft. Ele permite que a gente crie apps, bancos de dados por exemplo, sem precisar de um computador físico rodando tudo isso. Ao invés de instalar e cuidar de servidores reais, podemos facilitar isso com essa ferramenta. 

### Menu Inicial e Personalização

Assim que criamos um recurso no Microsoft Azure, somos levados para esse painel bem organizado com várias opções úteis.

<img width="1918" height="907" alt="image" src="https://github.com/user-attachments/assets/69bd0740-5f2a-4a41-9b63-e1fb5fb361df" />

#### Personalizando o portal:

É possível:

- Trocar a região (local dos servidores) e mudar o idioma para o que preferir

<img width="1027" height="404" alt="image" src="https://github.com/user-attachments/assets/4d20514b-364e-4934-94d5-5a8eed6bf86b" />


- Escolher entre temas claro ou escuro.
<img width="1155" height="578" alt="image" src="https://github.com/user-attachments/assets/f85cd3ef-d1f7-4967-8311-60611962a918" />


Antes de entrarmos mais a fundo nas categorias, acho importante explicar a diferença entre Paas e Saas 

## PaaS – Platform as a Service (Plataforma como Serviço)

Fornece um ambiente pronto pra você desenvolver e rodar suas aplicações sem se preocupar com a infraestrutura.

🔹 Você gerencia: o código, os dados, e a lógica do app
🔹 Azure gerencia: servidores, rede, segurança, sistema operacional e tudo que roda por trás.

Exemplos no Azure:

- Azure App Service

- Azure Functions

- Azure SQL Database

## SaaS – Software as a Service (Software como Serviço)

É um software, hospedado na nuvem, que você só acessa e usa — sem instalar ou programar nada.

🔹 Você gerencia: sua conta e preferências
🔹 Azure gerencia: infraestrutura, plataforma e o próprio aplicativo.

Exemplos:

- Microsoft 365 (Word, Excel, Outlook online)

- Dynamics 365 (CRM e ERP)

- Azure DevOps Services (gestão de projetos e repositórios)

# Categorias que explorei

<img width="223" height="689" alt="image" src="https://github.com/user-attachments/assets/2557b52a-f795-4e64-8eca-82b99f9eb866" />

## O Azure é gigante, então separei em três categorias principais pra começar a entender melhor:

### Compute (Computação)

Serviços para processar e rodar aplicações.

- Azure Virtual Machines (VMs): Uma máquina/servidor completo na nuvem.

- Azure App Service: Hospede sites e APIs facilmente, sem cuidar de servidor.

- Azure Functions: Execute códigos sob demanda (serverless) e pague só pelo que usar.

### Storage (Armazenamento)

Serviços para guardar arquivos, dados e backups.

- Azure Blob Storage: Armazene imagens, vídeos, documentos etc.

- Azure File Storage: Compartilhamento de arquivos como um drive em rede.

- Azure Table Storage: Armazenamento NoSQL simples para dados estruturados.

### Database (Banco de Dados)

-Soluções prontas para guardar e consultar informações.

-Azure SQL Database: SQL Server totalmente gerenciado na nuvem.

-Azure Cosmos DB: Banco de dados NoSQL distribuído globalmente.

-Azure Database for MySQL/PostgreSQL: Versões gerenciadas desses bancos famosos.

-------- Desafio 2 ----

# Principais beneficios da nuvem 

Temos 8 beneficios da Nuvem :

### 1. Alta Disponibilidade

Garantia de que os serviços estarão disponíveis o tempo todo, mesmo em caso de falhas ou interrupções.

Como é feito: Com redundância e distribuição global dos serviços (via SLAs do Azure).

### 2. Escalabilidade

Capacidade de aumentar ou reduzir recursos conforme a necessidade.Você só paga pelo que realmente usa (modelo baseado em consumo).

Tipos:

- Vertical: mais CPU/RAM na mesma máquina.

- Horizontal: adicionar/remover instâncias (como mais VMs).

### 3. Elasticidade

Capacidade de ajustar automaticamente os recursos durante picos ou quedas de demanda.

### 4. Confiabilidade

O que é: A nuvem é projetada para ser resiliente. Mesmo se uma região falhar, outras continuam funcionando.

### 5. Previsibilidade

Controle mais confiável de custos e desempenho.

### 6. Segurança 

A nuvem oferece ferramentas para proteção de dados e sistemas. Em modelos como PaaS/SaaS, parte da segurança é gerenciada pelo provedor; em IaaS, o cliente tem mais controle e responsabilidade.

### 7. Segurança 

Governança

Monitoramento e conformidade com as políticas da empresa. Como:

- Auditorias automáticas.

- Aplicação automática de patches.

- Prevenção contra má configuração.

### 8. Gerenciabilidade

Facilidade para gerenciar recursos em nuvem com Linha de comando (CLI), PowerShell,APIs. Além do escalonamento automático e monitoramento de uso e desempenho.

# Criando uma maquina virtual 

Abaixo temos a tela inicial para criação da maquina virtual 
<img width="1901" height="872" alt="image" src="https://github.com/user-attachments/assets/c2ea2e3e-3bcd-497d-a16e-46073394ac14" />

Ao escolhermos criar uma maquina virtual temos as configurações básicas como: Assinatura: assinatura ativa, grupo de recursos,nome da VM, região, imagem e tamanho

<img width="1159" height="717" alt="image" src="https://github.com/user-attachments/assets/93f200d1-a59d-4846-8f3d-5de486520dd4" />

