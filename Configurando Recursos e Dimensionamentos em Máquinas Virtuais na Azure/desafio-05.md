# Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

## 1. Entre no [portal Azure](https://portal.azure.com/#home) 
 - No painel, procure por “Máquinas Virtuais” e clique em **"Criar"**

## 2. Configure a Máquina Virtual 

   1. **Nome da Maquina Virtual**.
      
      ![VM1](https://github.com/user-attachments/assets/44cc26b5-d13b-4a9a-9041-994d76ee3065)
   
   2. **Escolha a região**

      ![VM2](https://github.com/user-attachments/assets/bab54a2b-b7ac-4190-b368-5e41405d49d6)

   3. **Opções de disponibilidade. Como estamos realizando teste. Escolheremos "Nenhuma redundância infraestrutura necessária" por enquanto**

      ![VM3](https://github.com/user-attachments/assets/abaf37f2-e389-4c18-bbea-4c6a34232f06)

   4. **Escolha a imagem Windows ou linux que deseja usar**
      
      ![VM4](https://github.com/user-attachments/assets/6df4ec9a-5e00-4b80-8e86-a9097fcac560)

   5. **Escolha o tamanho da Maquina Virtual de acordo com a nessecidade de CPU E Memoria Ram.**
         
      ![VM5](https://github.com/user-attachments/assets/0df54be0-9e94-4564-bec2-56ea49e87614)

## 3. Configure o dimencionamento da Maquina Virtual

  1. **Manual de Dimensionamento**: Escolha um tamanho de VM com base na carga de trabalho que você espera. O Azure oferece uma variedade de tamanhos de VM, desde opções básicas para tarefas leves até opções robustas para aplicações exigentes. 

  2. **Dimensionamento Automático**: Configure uma escala automática para ajustar automaticamente os recursos da VM com base na demanda. Isso é útil se você tiver variações específicas no uso ou precisa garantir que a VM possa lidar com picos de carga.
 
  ![VM6](https://github.com/user-attachments/assets/6ee9ab73-df7b-4c15-a79a-a20ba931482e)
  
  3. **Configure a escala**: Clique no lapis para alterar as configurações padrões.
     
  ![VM7](https://github.com/user-attachments/assets/e6a05154-b1fd-4ce6-9bbd-e17e2907c38e)
  
  ![VM8](https://github.com/user-attachments/assets/92c37921-a424-41a5-b9ec-1a155717479f)

  5. **Utilize o Azure Advisor**: O Azure Advisor fornece recomendações de dimensionamento com base no desempenho atual de sua VM. Ele pode sugerir configurações para economizar custos ou melhorar o desempenho.

## 4. Depois só Seguir os passos restante e revisar e criar
