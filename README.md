# 🧠 Projeto DIO - Criação de Máquina Virtual no Azure

## 📌 Objetivo
Este projeto tem como objetivo demonstrar a criação e configuração de uma máquina virtual utilizando o Microsoft Azure, consolidando os conhecimentos adquiridos no curso da DIO.

---

## 🔧 Configurações da VM

| Item                    | Valor                                          |
|-------------------------|-----------------------------------------------|
| **Nome da VM**          | VM-Teste-DIO                                   |
| **Região**              | Norway East                                    |
| **Imagem**              | Ubuntu Server 24.04 LTS - x64 Gen2             |
| **Tamanho da VM**       | Standard_D2s_v3 – 2 vCPUs, 8 GiB RAM           |
| **Usuário admin**       | dioadmin                                       |
| **Autenticação**        | Senha                                          |
| **Porta liberada**      | SSH (porta 22)                                 |
| **Grupo de Recursos**   | RG-VM-Aula                                     |
| **Disco do SO**         | SSD Standard                                   |

---

## 🖥️ Etapas Realizadas

1. Criação do Grupo de Recursos no Azure.
2. Escolha da imagem: Ubuntu 24.04 LTS Gen2.
3. Seleção do tamanho da VM: Standard_D2s_v3.
4. Configuração da autenticação via usuário e senha.
5. Abertura da porta SSH (22) para acesso remoto.
6. Criação de disco SSD padrão.
7. Implantação da máquina virtual com sucesso.

---

## 📚 Aprendizados
1. Como navegar pelo portal Azure para criação de VMs.
2. Configuração correta de rede, disco e autenticação.
3. Como evitar custos desnecessários utilizando regiões gratuitas e tipos de máquinas leves.
4. Boas práticas de documentação técnica e uso do GitHub.

---

## 🖼️ Prints da Criação

As imagens capturadas durante a criação da VM estão organizadas na pasta `/images`.

### 📁 Estrutura do repositório

- `vm-azure-dio/`  
  - `images/`  
    - `print-basico.png`  
    - `print-discos.png`  
    - `print-rede.png`  
    - `print-gerenciamento.png`  
    - `print-tags.png`  
    - `print-revisao.png`  
  - `README.md`

---

## 🚀 Conclusão

Com esta atividade, foi possível colocar em prática os conhecimentos adquiridos no curso da DIO, desde a criação até a documentação de uma máquina virtual no Azure.  
A prática reforçou conceitos importantes como:

- Configuração de infraestrutura em nuvem
- Boas práticas de segurança e acesso remoto
- Organização e versionamento com GitHub


