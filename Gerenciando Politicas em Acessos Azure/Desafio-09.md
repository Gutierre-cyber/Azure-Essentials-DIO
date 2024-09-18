# Gerenciando Politicas em Acessos Azure

## 1. Portal de Confiança do Azure

O Portal de Confiança do Azure é uma ferramenta que permite monitorar e gerenciar a conformidade e a segurança dos recursos disponíveis na plataforma Azure. Ele disponibiliza dados sobre melhores práticas, aderência a regulamentos e proteção das informações. Para acessar e aproveitar as funcionalidades do Portal de Confiança, siga os passos a seguir:

1. **Acesse o Portal de Confiança**:

![image](https://github.com/user-attachments/assets/a39ca2b1-f6d7-4950-979e-34df85af0f5c)

Este portal é uma ferramenta que otimiza a administração de políticas de conformidade, assegurando que seus recursos estejam em conformidade com as melhores práticas de segurança e os requisitos regulatórios. No Portal de Confiança, você encontrará um resumo das certificações e da conformidade com as normas do Azure, o que possibilita uma avaliação rápida da situação de conformidade e a identificação de áreas que necessitam de melhorias.

## 2. Bloco de Recursos

O Bloqueio de Recursos no Azure possibilita a proteção contra a exclusão ou modificação acidental de recursos essenciais. Para implementar um bloqueio de recurso, siga as etapas abaixo:

1. **Acesse o Portal do Azure**:

Realize o login no [Portal do Azure](https://portal.azure.com/#home)

2. **Navegue até o Recurso**

 - No painel de navegação à esquerda, clique em "Recursos" e selecione o recurso que deseja proteger.
   
![image](https://github.com/user-attachments/assets/4b94afeb-6cbb-4e5d-ace4-2e8350d03130)

3. **Configure o bloqueio**

   - No painel do recurso, selecione "Bloqueios ou Locks"
   - Clique em "Adicionar bloqueio" e escolha um tipo de bloqueio:
     - **ReadOnly**: Impede alterações, mas permite leitura.
     - **CanNotDelete**: Impede exclusão do recurso.
    
![image](https://github.com/user-attachments/assets/8e441c33-572d-4d58-a420-5c209ae88cc2)

4. **Defina o Nome e Descrição**:

   - Insira um nome e uma descrição para o bloqueio.
   - Clique em **"Salvar"** para aplicar o bloqueio ao recurso.

   ![b3](https://github.com/user-attachments/assets/7df17666-dcd2-4903-a492-0f9f391de4ed)

   ![b4](https://github.com/user-attachments/assets/c3f2d14c-d801-4060-98f0-36a4be58f035)

## 3. Microsoft Purview

 1. **Criar uma conta Microsoft Purview**:

   ![image](https://github.com/user-attachments/assets/23f51d4b-5a1c-4699-be33-ecd9805b914f)

 2. **Configure a conta**:

    - Escolha o grupo de recurso.
    - Nomeie a conta
    - Examinar e criar

  ![image](https://github.com/user-attachments/assets/4460b081-c6d8-4798-b554-1762e5abdc02)

 3. **Clique no Portal de Governança do Microsoft Purview**:

      ![image](https://github.com/user-attachments/assets/052400a6-2202-401c-962c-acf9ec60e506)

