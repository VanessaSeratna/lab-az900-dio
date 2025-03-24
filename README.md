# lab-az900-dio
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.

# Formação Microsoft AZ-900 Certification

Bem-vindo ao repositório sobre o bootcamp de Formação Microsoft AZ-900 Certification! Este repositório foi criado para fornecer uma visão geral sobre o que aprendi até o momento.

## 📌 Resumo do conteúdo

### 💡 O que é Computação em Nuvem?

A **computação em nuvem** é a entrega de serviços de computação, como armazenamento, processamento, redes, bancos de dados e software, pela internet ("nuvem"). Em vez de possuir e manter infraestrutura física, os usuários podem acessar recursos sob demanda, pagando apenas pelo que utilizam.

### 🌐 Modelos de Nuvem
#### 1. **Nuvem Pública**
#### 2. **Nuvem Privada**
#### 3. **Nuvem Híbrida**

### 💡 Modelo Baseado no Consumo

O **modelo baseado no consumo** é um dos pilares da computação em nuvem. Nele, os usuários pagam apenas pelos recursos que consomem, sem custos iniciais ou compromissos de longo prazo. Isso elimina a necessidade de investimentos em infraestrutura física e permite maior flexibilidade financeira.

### 🌐 Benefícios da Computação em Nuvem
#### 1. Alta disponibilidade e da escalabilidade na nuvem.
#### 2. Confiabilidade e da previsibilidade na nuvem.
#### 3. Segurança e da governança na nuvem.
#### 4. Capacidade de gerenciamento na nuvem.

### 💡 Tipos de Serviço de Nuvem
#### 1. IaaS (Infraestrutura como serviço).
#### 2. PaaS (Plataforma como serviço).
#### 3. SaaS (Software como Serviço).

### ⚒️ Construindo Arquiteturas no Azure
#### Nesta parte do curso, fizemos um laboratório onde construimos um grupo de recursos e uma rede virtual.

### 🖥️ Criação de VM pelo Portal do Azure
#### Passos para Criação da VM

#### 1. Acesse o Portal do Azure:
   - Entre no [Portal do Azure](https://portal.azure.com) com suas credenciais.

#### 2. Criar um Grupo de Recursos:
   - No menu à esquerda, selecione **"Grupos de Recursos"**.
   - Clique em **"Criar"** e preencha os campos necessários (Nome, Assinatura, Região).

#### 3. Criar a Máquina Virtual:
   - No menu à esquerda, selecione **"Máquinas Virtuais"**.
   - Clique em **"Criar"** e escolha **"Máquina Virtual"**.
   - Preencha os detalhes necessários:
     - **Assinatura**: Escolha sua assinatura.
     - **Grupo de Recursos**: Selecione o grupo criado anteriormente.
     - **Nome da VM**: Defina um nome para a VM.
     - **Região**: Escolha a região desejada.
     - **Imagem**: Selecione uma imagem (ex: Ubuntu Server, Windows Server).
     - **Tamanho**: Escolha o tamanho da VM.
     - **Nome de usuário e Senha**: Defina as credenciais de acesso.
   - Revise as configurações e clique em **"Revisar + criar"**.
   - Após a validação, clique em **"Criar"**.

#### 4. Conectar à VM:
   - Após a criação, acesse a VM pelo portal.
   - Use as credenciais definidas para conectar-se via SSH (Linux) ou RDP (Windows).

### ⚙️ Armazenamento no Azure
Nesta parte do repositório contém exemplos e documentação sobre como utilizar o Armazenamento do Azure, um serviço de armazenamento em nuvem da Microsoft que oferece soluções escaláveis e seguras para armazenamento de dados.

#### Visão Geral

O Armazenamento do Azure é um serviço de armazenamento em nuvem que oferece diferentes tipos de armazenamento para atender a diversas necessidades:

   - **Blob Storage**: Armazenamento de objetos para textos ou dados binários, como arquivos de mídia, backups, etc.
   - **File Storage**: Armazenamento de arquivos acessíveis via SMB (Server Message Block), ideal para compartilhamento de arquivos.
   - **Queue Storage**: Armazenamento de mensagens para comunicação assíncrona entre componentes de aplicativos.
   - **Table Storage**: Armazenamento NoSQL para dados semi-estruturados.

### 🪪 Identidade, Acesso e Segurança no Azure
Nessa sessão do repositório contém recursos, exemplos de código e documentação relacionados à gestão de identidade, acesso e segurança no Microsoft Azure. Aqui, você encontrará informações sobre serviços como Azure Active Directory (Azure AD), RBAC (Role-Based Access Control), Azure Security Center e muito mais, visando garantir a proteção e conformidade dos recursos na nuvem.
   - ID do Microsoft Entra: É o serviço de gerenciamento de identidades e acesso baseado em nuvem do Microsoft Azure.
     - **Microsoft Entra Domain Services**: É um serviço gerenciado da Microsoft que fornece serviços de domínio compatíveis com o Microsoft Entra diretamente na nuvem do Azure.
   - Autenticação e Autorização:
     - **Autenticação**: É o processo de verificar a identidade de um usuário, sistema ou entidade que tenta acessar um recurso, sistema ou aplicação. Em outras palavras, é o mecanismo que confirma que alguém ou algo é realmente quem ou o que diz ser.
     - **Autorização**: É o processo que define o que um usuário ou sistema autenticado pode ou não fazer dentro de um ambiente ou aplicação.
     - **Auenticação Multifator (MFA)**: Fornece segurança adicional, para as identdades, exigindo dois ou mais elementos para autenticação completa.
   - B2B do Microsoft Entra External ID: É uma solução da Microsoft que permite que organizações compartilhem aplicativos, serviços e recursos com usuários externos, como parceiros, fornecedores ou clientes, de forma segura e controlada. 
   - Azure AD B2C: É um serviço de gerenciamento de identidades da Microsoft projetado para aplicativos voltados ao consumidor. Ele permite que você personalize e controle como os usuários se inscrevem, fazem login e gerenciam seus perfis ao usar seus aplicativos, sejam eles web, móveis ou de desktop.
   - Acesso Condicional: Ele ajuda a proteger os recursos da sua organização contra ameaças, como logins suspeitos, dispositivos não gerenciados ou acessos de locais inesperados.
   - Controle de Acesso Baseado em Função (RBAC): É um sistema de gerenciamento de permissões que permite controlar o acesso a recursos no Azure de forma granular e organizada.
   - Microsoft Defender para Nuvem: É uma solução de segurança unificada para proteger cargas de trabalho em nuvem, sejam elas executadas no Azure, em outras nuvens (como AWS ou Google Cloud) ou em ambientes híbridos.
### 💰 Gerenciamento de Custos
Este repoditório contém informações para ajudar no controle de custos, identificação de desperdícios e alocação precisa de recursos na Azure.
   - Fatores que afetam os custos são: 
     - Tipos de recursos, Consumo, Área Geográfica, Tráfico de Rede e Assinatura.
   - Calculadora de preço: Ferramenta para estimar custos de serviços Microsoft Azure antes da implementação.
   - Calculadora de custo total (TCO): Ferramenta avançada para estimar custos totais de migração para nuvem, incluindo infraestrutura, licenças, operação e otimizações.
   - Gerenciamento de custos do Azure: Solução completa para monitorar, analisar e otimizar custos na Microsoft Azure.
   - Marcas (Tag): Sistema de organização de recursos na nuvem Azure usando tags para gestão de custos, governança e operações.
#
#
⚠️ **Com o avanço do bootcamp, mais informações seram adicionadas nesse repositório.**
