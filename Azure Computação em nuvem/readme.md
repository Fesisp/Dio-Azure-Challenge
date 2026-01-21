# Resumo: Benefícios do Laboratório em Nuvem

Este projeto faz parte do desafio de projeto da DIO e tem como objetivo demonstrar os conhecimentos adquiridos no curso de Máquinas Virtuais da Azure.

##  Descrição
O projeto consiste em criar, configurar e documentar uma máquina virtual no Azure, explorando os principais recursos e funcionalidades da plataforma. 
Esta aula tratou especificamente sobre a criação de uma Máquina Virtual no Azure.

##  Passo a Passo

### 1. Acesse o Portal do Azure
- Faça login em [Portal Azure](https://portal.azure.com).

### 2. Crie um Grupo de Recursos
- Crie um novo grupo de recursos para organizar os recursos da sua VM.

### 3. Crie a Máquina Virtual
- Selecione "Criar um recurso" e busque por **"Máquina Virtual"**.
- Preencha os detalhes da VM:
  - Nome
  - Região
  - Imagem do sistema operacional
  - Tamanho
  - Outros detalhes necessários
- Configure a rede:
  - Crie uma nova VNet ou utilize uma existente.
- Configure as regras de entrada no NSG (Network Security Group):
  - Libere as portas necessárias (ex: porta 80 para HTTP e porta 22 para SSH).

### 4. Acesse a Máquina Virtual
- Após a criação da VM, acesse-a via:
  - **SSH** (para Linux)
  - **RDP** (para Windows)

### 5. Configuração Opcional
- Se for do interesse, instale um Servidor web (como **NGINX** ou **Apache**) para testar a conectividade.
