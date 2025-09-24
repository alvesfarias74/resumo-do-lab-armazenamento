# ☁️ Armazenamento no Microsoft Azure
Este repositório documenta os principais conceitos e práticas sobre os **serviços de armazenamento na plataforma Microsoft Azure**, cujo objetivo é consolidar o conhecimento adquirido e servir como referência para projetos e estudos relacionados à computação em nuvem.

## 🧠 Conteúdo Aprendido

- **Tipos de armazenamento no Azure**:
  - **Blob Storage**: Armazenamento de objetos não estruturados, ideal para imagens, vídeos, backups e arquivos grandes.
  - **File Storage**: Compartilhamento de arquivos via protocolo SMB, útil para migração de servidores de arquivos locais.
  - **Queue Storage**: Gerenciamento de mensagens entre componentes distribuídos, promovendo escalabilidade e desacoplamento.
  - **Table Storage**: Armazenamento NoSQL para dados estruturados, com alta disponibilidade e baixo custo.

- **Camadas de acesso**:
  - **Hot**: Para dados acessados com frequência.
  - **Cool**: Para dados acessados esporadicamente.
  - **Archive**: Para dados raramente acessados, com custo de armazenamento reduzido.

- **Redundância e replicação**:
  - **LRS (Locally Redundant Storage)**: Replicação dentro de um único datacenter.
  - **ZRS (Zone-Redundant Storage)**: Replicação entre zonas de disponibilidade na mesma região.
  - **GRS (Geo-Redundant Storage)**: Replicação entre regiões geográficas para maior resiliência.

- **Segurança e controle de acesso**:
  - Criptografia em repouso e em trânsito.
  - Autenticação via Azure Active Directory.
  - Controle de acesso com SAS (Shared Access Signatures) e políticas de RBAC.

- **Ferramentas de gerenciamento**:
  - Portal do Azure.
  - Azure CLI e PowerShell.
  - SDKs para .NET, Python, JavaScript e outras linguagens.

