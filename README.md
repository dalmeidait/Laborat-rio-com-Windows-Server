# Laboratório prático com WindowsServer
Laboratório prático com Windows Server

# Windows Server Lab  
Repositório para estudos de Windows Server (AD DS, GPO, DNS e PowerShell).  

# Projeto

# 🏢 Estrutura da Empresa – DevTech Solutions

## 📌 Empresa
**Nome:** DevTech Solutions  

---

## 🏗 Departamentos

### 🔧 Engenharia  
- **Subdepartamentos:**  
  - Desenvolvimento Backend  
  - Desenvolvimento Frontend  
  - DevOps  
- **Responsáveis:**  
  - Engenheiro Chefe *(Engenharia)*  
  - Líder Backend *(Desenvolvimento Backend)*  
  - Líder Frontend *(Desenvolvimento Frontend)*  
  - Coordenador DevOps *(DevOps)*  

---

### ✅ Qualidade de Software (QA)  
- **Subdepartamentos:**  
  - Testes Automatizados  
  - Testes Manuais  
- **Responsáveis:**  
  - Gerente de QA *(Qualidade de Software)*  
  - Especialista em Automação *(Testes Automatizados)*  
  - Analista de Teste *(Testes Manuais)*  

---

### 🖥 Infraestrutura  
- **Subdepartamentos:**  
  - Suporte Técnico  
  - Redes  
- **Responsáveis:**  
  - Gerente de Infraestrutura *(Infraestrutura)*  
  - Coordenador de Suporte *(Suporte Técnico)*  
  - Administrador de Redes *(Redes)*  

---

## 🧪 Aplicações no Laboratório Virtual

Neste laboratório, você deverá implementar um ambiente com os seguintes serviços:

### 1️⃣ Active Directory Domain Services (AD DS)  
- Estrutura de **Unidades Organizacionais (OUs)** para cada departamento e subdepartamento.  
- **Contas de usuário** para todos os responsáveis e colaboradores.  

### 2️⃣ DHCP e DNS  
- Configuração de **servidor DHCP** para alocar endereços IP dinamicamente para todas as máquinas virtuais.  
- Configuração de **servidor DNS** para resolver nomes de host e permitir comunicação entre máquinas.  

### 3️⃣ Serviços de Arquivo e Impressão  
- **pastas compartilhadas** com permissões específicas para cada departamento.  
- Configuração de um **serviço de impressão centralizado** para gerenciar as impressoras da empresa.  

### 4️⃣ Servidor Web (IIS)  
- Implementação de um **servidor web** com o Internet Information Services (IIS).  
- Hospedagem de uma **intranet local** contendo:  
  - Informações de contato  
  - Organograma  
  - Manuais de procedimentos  

### 5️⃣ Firewall  
- Configuração de regras no **Windows Defender Firewall** para proteger a rede interna.  
- Restrição de acesso externo e controle de tráfego entre os departamentos.  

### 6️⃣ Serviço de Backup  
- Utilização do **Windows Server Backup** para criar um **plano de backup agendado** dos dados críticos, incluindo:  
  - Active Directory  
  - Arquivos compartilhados  

