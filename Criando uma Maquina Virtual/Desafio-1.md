## Criação de VM em Azure

### 1. Acesse o Portal do Azure 

Primeiro, faça login no [portal do Azure](https://portal.azure.com). É onde você vai gerenciar todos os seus recursos.

### 2. Criação da VM 

No painel do Azure, procure por “Virtual Machines” ou Máquinas Virtuais na barra de pesquisa. Clique em **"Criar"** para começar a configuração.

### 3. Preencha os Detalhes Básicos 

- **Nome da VM**: Escolha um nome que ajude você a identificar a VM facilmente.
- **Região**: Selecione a região onde a VM será criada. É uma boa ideia escolher uma que esteja perto dos seus usuários ou da sua localização.
- **Imagem**: Escolha o sistema operacional que você deseja instalar na VM, como Windows ou Linux.
- **Tamanho**: Selecione o tamanho da VM com base nas suas necessidades de CPU, memória e armazenamento.

### 4. Configure as Opções de Rede 

- **Rede Virtual**: Crie uma nova rede ou selecione uma existente.
- **Sub-rede**: Escolha a sub-rede onde a VM será conectada.
- **Grupo de Segurança de Rede (NSG)**: Defina as regras de firewall para a sua VM.

### 5. Defina as Credenciais de Login 

- **Nome de Usuário e Senha**: Configure um nome de usuário e senha para acessar a VM. Certifique-se de escolher uma senha segura.

### 6. Revise e Crie 

Revise todas as configurações para garantir que tudo esteja correto. Clique em **"Criar"** e aguarde alguns minutos enquanto o Azure provisiona sua máquina virtual.

### 7. Conecte-se à Sua VM 

Depois que a VM estiver criada, você pode se conectar a ela. Para VMs Windows, use o Remote Desktop (RDP). Para VMs Linux, você pode usar SSH.
