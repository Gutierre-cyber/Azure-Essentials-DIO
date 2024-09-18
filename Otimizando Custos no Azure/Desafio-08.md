# Otimizando Custos no Azure

## 1.  Usando a Calculadora de TCO

A Calculadora de TCO (Custo Total de Propriedade) do Azure é uma ferramenta valiosa para avaliar o custo total associado à migração para a nuvem. Para utilizá-la, basta seguir os passos a seguir:

1. **Acesse a calculadora de TCO**:
   
   - Visitando o site oficial da Calculadora de TCO do Azure: [Calculadora de TCO do Azure](https://azure.microsoft.com/en-us/pricing/tco/calculator/).

  ![image](https://github.com/user-attachments/assets/14ad45f5-6f8c-46e2-b980-e3bb5bef2b15)

  A diferença dessa calculadora para a calculadora de TCO do Portal do Azure. É que, digamos que estamos pensando em migrar nossos recurso que estão em um datacenter on premises para a nuvem. 
  Porém, não podemos sair migrando, sem termos uma ideial de quanto, iremos gastar com essa migração. Dessa forma, temos um noção de quantos gastariamos, migrando nosso resurso.

2. **Configurar o Cenário Atual**

   - Adicione detalhes sobre sua infraestrutura atual, incluindo servidores, sistemas de armazenamento e redes.
   - A meta é apresentar uma visão geral dos custos atuais para que possamos comparar com os custos na nuvem.
   
![image](https://github.com/user-attachments/assets/000431e9-1bf4-4068-902f-2b3370ff5bee)

![image](https://github.com/user-attachments/assets/325322cb-2222-47c5-a099-2e4766ecfb54)

![image](https://github.com/user-attachments/assets/e58faa12-234a-48d7-a713-b19aed1812ca)

![image](https://github.com/user-attachments/assets/611ee6c7-76c1-4c7d-b817-7e2f8f2996dc)

3. **Configure o Cenário no Azure**:

     - Adicione as mesmas capacidades no Azure para estimar o custo equivalente.
     - Escolha os serviços e recursos que atendem aos seus requisitos atuais.

4. **Compare os Custos**:

     - A ferramenta fornecerá uma comparação entre o custo atual e o custo estimado na nuvem.
     - Analisar os resultados para tomar decisões informadas sobre a migração para o Azure.

![image](https://github.com/user-attachments/assets/767dbf1d-dbc2-4cdb-9ce3-d4feae367fdd)

![image](https://github.com/user-attachments/assets/83c50ff0-f04d-413a-8569-b549b071b1e8)

![image](https://github.com/user-attachments/assets/0a1ffd13-ca67-44b9-b7e7-48c1c0e40c95)

## 2. Realizando uma estimativa de preços de Maquinas virtuais

   1. Entre no site oficial [Calculadora de preço](https://azure.microsoft.com/pt-br/pricing/calculator/)

   2. Iremos realizar um simulação de estimativa de preços de Vms, clique em Maquinas virtuais e configure. Conforme imagem abaixo:

      ![image](https://github.com/user-attachments/assets/6a2145d9-d7b2-4d24-bf0e-6e2b3d72c4fa)

      ![image](https://github.com/user-attachments/assets/274ade0e-fe9c-4056-8321-774431558a9c)
      
   3. Licença incluída
      
   ![image](https://github.com/user-attachments/assets/dba89a2a-2d51-4123-9ab0-6e50bef401eb)

   5. Iremos escolher um benificio hibrido
      
   ![image](https://github.com/user-attachments/assets/257ec4e8-4892-4f93-a5e1-2b1d0dae5aa2)

   Obs.: que teve uma mudança no preço estimativo mesal. E se fizermos uma reserva de 1 ano, esse preço diminuirá ainda mais. Conforme visto na imagem abaixo:

   ![image](https://github.com/user-attachments/assets/6ed017a3-d1c4-482a-af9b-20de0f0c4bb2)

   E assim, por diante é possivel configurar vários cenários de negócio.

   ## 3. Monitoramento de Custos no Azure

   O Azure oferece várias ferramentas para monitorar e gerenciar seus custos. Aqui está um guia básico para monitorar seus gastos:

   1. **Acesse o Portal do Azure**:

   Realize o login no [Portal do Azure](https://portal.azure.com/#home)

   2. **Navegue para 'Gerenciamento de Custos + Faturamento'**:

    - No menu de navegaçã, selecione "Gerenciamento de Custos + Faturamento"
    
   ![image](https://github.com/user-attachments/assets/0cb18b2d-6c3c-4fc8-9e8f-12117675deb7)

   3. **Visualizar os Custos**:

   - Em "Gerenciamento de Custos" você pode ver um resumo de seus custos e despesas.
   - Utilize a "Análise de Custos" para explorar detalhes mais profundos sobre como os recursos estão gerando custos.
   
   4. **Configurar Alertas de Custo**:

   - Configure alertas para notificar quando seus gastos atingirem determinados limites.
   - Em "Alertas" você pode definir regras e limites para serem informados proativamente.

   ![image](https://github.com/user-attachments/assets/f5a41167-22eb-4baf-a826-d0ff8542272f)
