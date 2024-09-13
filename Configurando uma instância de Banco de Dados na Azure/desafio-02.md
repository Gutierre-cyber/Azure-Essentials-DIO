## Configurando uma instância de Banco de Dados na Azure

## Para sua instância, siga estas etapas:

### 1. Entre no [portal Azure](https://portal.azure.com/#home) 

### 2. No menu esquerdo do portal do Azure, selecione SQL do Azure. Se SQL do Azure não estiver na lista, selecione Todos os serviços e, em seguida, digite SQL do Azure na caixa de pesquisa. Conforme visto na imagem abaixo:

![Criando Instacias de banco de dados no azure](https://github.com/user-attachments/assets/be3d2212-0c65-4440-a5b9-7f8b40b1105a)

### 3. clique em criar recurso SQL do Azure

![Criando Instacias de banco de dados no azure2](https://github.com/user-attachments/assets/33a0009c-f5c7-4516-a0c1-ce73e4e7e6d5)

### 4. Escolha Base de dados única na lista suspensa e depois selecione Criar para abrir a página Criar banco de dados SQL do Azure. Conforme imagem abaixo: 

![criando Instacias de banco de dados no azure3](https://github.com/user-attachments/assets/c64f6800-db54-4bac-8026-f46214e852c5)

### 5. Crie um Novo Banco de Dados
 #### 1. Após clique em "Criar": Isso iniciará o assistente de criação do banco de dados.
 #### 2. Preencha os Detalhes:
- Nome do Banco de Dados: Escolha um nome legal e único.
- Assinatura: Selecione a assinatura que você está usando.
- Grupo de Recursos: Crie um novo grupo ou use um existente.
- Servidor: Crie um novo servidor ou selecione um já existente. Se você está criando um novo, preencha o nome do servidor, localização e -- credenciais de administrador.
- 
### Conforme imagem abaixo:

![criando Instacias de banco de dados no azure4](https://github.com/user-attachments/assets/0ba867a2-1320-413d-981e-8a4b7e4f5743)

### 6. Configurações de Banco de Dados 

Escolha o tipo de banco de dados que deseja usar. O Azure oferece opções como SQL Database, Cosmos DB e mais. Aqui, vamos criar um **SQL Database**. 🗃

- **Plano de Tarifação** (Importante): Selecione o plano que se adapta às suas necessidades. Se você está apenas testando, o plano gratuito pode ser suficiente. 
- **Backup e Recuperação** (Importante): Configure as opções de backup conforme necessário para garantir que seus dados estejam seguros. 

### 7. Revise e Crie 

Revise todas as configurações para garantir que está tudo certo. Se estiver, clique em **"Criar"** e aguarde alguns minutos enquanto o Azure configura seu banco de dados. 

### Conforme imagem abaixo: 

![criando Instacias de banco de dados no azure5](https://github.com/user-attachments/assets/d2ae7dbd-26eb-41df-84d3-c7e092440d94)

### 8. Conecte-se ao Seu Banco de Dados 

Após a criação, você pode se conectar ao banco de dados usando ferramentas como SQL Server Management Studio (SSMS) ou Azure Data Studio. Use as credenciais que você configurou anteriormente para se conectar. 

