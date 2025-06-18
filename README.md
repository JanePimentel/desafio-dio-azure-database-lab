# desafio-dio-azure-database-lab
Configuração de uma instância de Banco de Dados MySQL na plataforma Microsoft Azure

# 🚀 Desafio Azure MySQL - DIO

## 📝 Descrição do Desafio
**Implementação de um Banco de Dados MySQL Flexível no Azure** com documentação técnica no GitHub, contemplando:

- Configuração passo a passo
- Melhores práticas

## 🔧 Configuração Técnica

### Pré-requisitos
| Item | Especificação |
|------|--------------|
| **Conta Azure** | Camada gratuita (750h) |
| **Tipo de Servidor** | MySQL Flexible Server |
| **Região** | East US (recomendado) |
| **Versão** | MySQL 5.7+ |

### Passo a Passo (Resumido)
Navegue até a seção "Serviços do Azure" no portal (Figura 1)
Selecione "Bancos de dados SQL" ou pesquise por "MySQL" (Figura 2)
Ao acessar a seção de servidores MySQL, clique em "Criar Servidor Banco de Dados do Azure para MySQL" (Figura 3)
Selecione o tipo "Servidor flexível do Banco de Dados do Azure para MySQL" (Figura 4)
### Config Básico
Selecione a assinatura (ex: Azure for Students)
Crie ou selecione um grupo de recursos (Figura 5)
### Detalhes do Servidor
Nome do servidor (deve ser único)
Região (ex: East US)
Versão do MySQL (ex: 5.7)
Tipo de carga de trabalho (Figura 5)
### Configuração de Computação e Armazenamento
Selecione o tipo de computação (ex: "Intermitente, B1ms" com 1 vCore, 2 GiB RAM)
Configure o armazenamento (20 GiB, 360 IOPS) (Figura 6)
### Configuração de Segurança
Criptografia de dados (habilitada por padrão)
Opção para usar chaves gerenciadas pelo cliente (Figuras 7-8)
### Definir credenciais de admin:
   - Nome de usuário
   - Senha forte (12+ caracteres)  (Figura 6)
### Revisar todas as configurações + Criar  (Figura 10)
