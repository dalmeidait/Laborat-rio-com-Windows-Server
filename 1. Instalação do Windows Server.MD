# 🖥️ Instalação e Configuração Inicial – Windows Server 2019

## 📋 Ambiente Utilizado
- **Sistema Operacional:** Windows Server 2019  
- **Virtualização:** Oracle VirtualBox  
- **Rede:** Interna (Internal Network)  
- **Configuração de Hardware Virtualizado:** *(veja as imagens na pasta `/imagens`)*  

---

## 🛠️ Passo a Passo – Instalação do Windows Server 2019

### 1️⃣ Criar e Configurar a Máquina Virtual
1. Abra o **VirtualBox** e clique em **Novo**.  
2. Nomeie a VM (ex.: `WinSrv2019-DevTech`) e selecione:  
   - **Tipo:** Microsoft Windows  
   - **Versão:** Windows 2019 (64-bit)  
3. Defina a quantidade de **RAM** (mínimo recomendado: 2 GB, ideal: 4 GB ou mais).  
4. Crie um **disco rígido virtual** (VDI) de pelo menos **50 GB**.  
5. Nas **Configurações da VM**, vá até **Rede** → selecione **Rede Interna**.  
6. Adicione o **ISO do Windows Server 2019** como mídia de boot em **Armazenamento**.

---

### 2️⃣ Instalação do Sistema Operacional
1. Inicie a VM e selecione o idioma, formato de hora e teclado → clique em **Next**.  
2. Clique em **Install Now**.  
3. Escolha a edição desejada (ex.: **Windows Server 2019 Standard (Desktop Experience)**).  
4. Aceite os termos de licença e clique em **Next**.  
5. Selecione **Custom: Install Windows only (advanced)** para uma instalação limpa.  
6. Escolha o disco virtual criado e clique em **Next**.  
7. Aguarde a cópia dos arquivos e reinicializações automáticas.  
8. Após o boot, defina a **senha do Administrador** e faça login.  

---

## 🖊️ Renomeação da Máquina Virtual (Hostname)

### Passo a Passo
1. Faça login como **Administrador**.  
2. Clique com o botão direito em **Iniciar** → **Sistema**.  
3. Em **Informações do sistema**, clique em **Renomear este PC**.  
4. Digite o novo nome (ex.: `SRV-DC01`).  
5. Clique em **OK** e reinicie a VM para aplicar a mudança.  

**Alternativa via PowerShell:**  
```powershell
Rename-Computer -NewName "SRV-DC01" -Restart
