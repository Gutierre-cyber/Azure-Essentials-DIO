# Dominando o armazenamento no Azure

## Passo a Passo para Configurar Armazenamento no Azure

### 1. Acesse o Portal do Azure 🌐

1. Entre no [Portal do Azure](https://portal.azure.com).
2. No painel, procure por “Conta de Armazenamento” e clique em **"Criar"**.

### 2. Configure uma conta de armazenamento

1. **Nome da Conta** Escolhar um nome único para sua contato de armazenamento e lembrando que podemos usar somente letras minúsculas.
2. **Escolha a região** Escolha uma região mais proxima para um melhor desempenho.
3. **Tipo de Conta** Escolhar o modelo Standard.
4. **Redundância** Escolha qual modelo de redundância vamos trabalhar. Como estamos treinando escolheremos o LRS. Porém, ele não é indicado para ambientes produtivos.

**Clique em proxímo Conforme visto na imagem abaixo**
 
![armazenamento1](https://github.com/user-attachments/assets/33782980-2268-4230-95bc-8a91b9fe7f03)

5. **Proteção de dados** É importante habilitar exclusão temporária para blobs. Porém, como estamos em uma ambiente de testes. Iremos desabilitar. Conforme mostrado na imagem abaixo.

![armazenamento2](https://github.com/user-attachments/assets/320e69f8-8689-46c2-a968-25ff5877c624)

6. **Clique em criar**
   
![armazenamento3](https://github.com/user-attachments/assets/ef3479ec-4ef0-4468-8ffb-9cf542a8a90c)

7. **Clique em ir para o recurso**
   
![armazenamento4](https://github.com/user-attachments/assets/7fa91aaf-f1a0-4209-88ac-92119b5016e2)

### 3. Criar um compartilhamento de arquivos

 1. No menu "Serviços", clique em "Compartilhamento de Arquivos". E Depois clique em novo compartilhamento de arquivos. Conforme imagem abaixo:

![armazenamento5](https://github.com/user-attachments/assets/52dc1d89-f336-43a4-9f80-24a6940c4ee9)

 2. Nomeie o compartilhamento e defina o tipo de acesso e clique avançar para backup, como estamos em um ambiente de teste desabilite o backup.
    
![armazenamento6](https://github.com/user-attachments/assets/ce3082cc-8092-4cf1-a3fd-6c9626052e65)

 3. Clique em criar, conforme imagem abaixo:

![armazenamento7](https://github.com/user-attachments/assets/0d5e8b02-6af0-4f36-b027-604982d33cff)

### 4 Migrar dados para Azure

1. **Criar um projeto**
   - Clique em descobrir, avaliar e migrar. Conforme imagem abaixo:
     
     ![armazenamento8](https://github.com/user-attachments/assets/3284dbd1-bb0d-4613-9012-6405a8000c13)

   - **Agora vamos criar o projeto**
     
     ![armazenamento9](https://github.com/user-attachments/assets/c15cd6d0-39f7-477b-bf04-b4aead739764)

   - **Nomeie o projeto, escolha a geografia e clique em criar. Conforme imagem abaixo:

     ![armazenamento10](https://github.com/user-attachments/assets/c1a45dbc-8f13-4902-a946-ecfc8fbdafcd)

     ![armazenamento11](https://github.com/user-attachments/assets/5b489a84-1989-4a02-accd-1fe4d4e1f056)

   - **Configurando o Data Box** Escolha o grupo de recursos, país de origeml, país destino e clique em aplicar. Conforme imagem abaixo:

     ![armazenamento12](https://github.com/user-attachments/assets/d44812e6-a338-4297-859b-ac8ff7cbff1a)

2. **Instalando o Azcopy**

   - Baixe e instale o Azcopy do site: [Baixar Azcopy](https://learn.microsoft.com/pt-br/azure/storage/common/storage-use-azcopy-v10?tabs=dnf)

 ![image](https://github.com/user-attachments/assets/9ec4af37-d48d-49cc-86bd-4bcf6a1619cc)
  
   - Despois de criar o Contêineres. Clique no Contêiner criado. Conforme imagem abaixo:

 ![armazenamento13](https://github.com/user-attachments/assets/f3e0c455-dcda-4d41-bb16-2ce16c9c9c39)

   - Depois clique em Tokens de acesso compartilhado.
     
 ![image](https://github.com/user-attachments/assets/c761ec27-f4bc-4737-a719-9349ea8fe59a)

   - Agora configure as permissões e gere o token SAS e URL
     
 ![image](https://github.com/user-attachments/assets/3b7714e1-0392-4bbf-8f99-baf2f2164335)

   - Agora copie a URL
 ![image](https://github.com/user-attachments/assets/522517b1-88e4-42b4-adf3-2852cbc247ca)

   - Observe que o Contêiner está vazio
    
 ![image](https://github.com/user-attachments/assets/d736c56a-9f92-4625-b4a3-f3267b540bd4)

 ![image](https://github.com/user-attachments/assets/dca1ae07-d6a1-4ef7-949b-8273ef7627ff)
 
 Execute esse comando acima no CMD.

 ![image](https://github.com/user-attachments/assets/210f44a1-13b0-4a0a-9381-5ed3ea608295)

 ![image](https://github.com/user-attachments/assets/21677e08-b220-42be-972b-f2e00194906c)

Após excutar o comando. Agora observe que as imagens da pasta copia estão dentro do contêiner. 

![image](https://github.com/user-attachments/assets/7d273a81-97fc-4ec5-8d5e-45431f2d4a86)
