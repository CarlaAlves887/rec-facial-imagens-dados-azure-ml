# Reconhecimento Facial e transformação de imagens em Dados no Azure ML

Para a resolução deste projeto segui o tutorial do laboratório 02 [Explore Automated Machine Learning in Azure Machine Learning](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html), seguindo os passos abaixo:

# 1. Criar um serviço Azure AI

Selecionar `+ Create a resource`option

![](https://github.com/CarlaAlves887/rec-facial-imagens-dados-azure-ml/blob/main/Imagem1.png)

Selecione a opção `AI + Machine Learning` do menu `Categories` e clique em `Create` no `Azure AI Services`.

![](https://github.com/CarlaAlves887/rec-facial-imagens-dados-azure-ml/blob/main/Imagem2.png)

Criar o novo `Azure AI Service` resoure com as seguintes configurações:
- **Subscription**: Selecionar a sua subscrição do azure.
- **Resource group**: Criar ou selecionar um resource group.
- **Name**: Defina um nome exclusivo para o seu worspace.
- **Region**: Selecionar East US.
- **Name**: servico-vision.
- **Pricing tier**: Standard S0.

Selecionar `Review + Create` e aguarde uns minutos até que o deployment termine com sucesso

![](https://github.com/CarlaAlves887/rec-facial-imagens-dados-azure-ml/blob/main/Imagem3.png)

# 2. Connectar o meu serviço Azure AI no Vision Studio

1. Abrir o [Vision Studio](https://portal.vision.cognitive.azure.com) e selecionar a opção `View all resources`
   ![](https://github.com/CarlaAlves887/rec-facial-imagens-dados-azure-ml/blob/main/Imagem4.png)

# 3. Detetar faces no Vision Studio

1. Na página principal `Get started with Vision`, selecionar a tab `Face` e depois selecionar a opção `Detect faces in an image`
   ![](https://github.com/CarlaAlves887/rec-facial-imagens-dados-azure-ml/blob/main/Imagem5.png)

2. Abaixo do subtítulo `Try it out` marcar a caixa da política de uso de recursos
   ![](https://github.com/CarlaAlves887/rec-facial-imagens-dados-azure-ml/blob/main/Imagem6.png)

3. Com base nas [imagens de input](https://github.com/CarlaAlves887/rec-facial-imagens-dados-azure-ml/tree/main/inputs) vamos testar o serviço para verificar se são detetadas máscaras nas faces ou não.
   
4. Na pasta de [output](https://github.com/CarlaAlves887/rec-facial-imagens-dados-azure-ml/tree/main/output) podem ser consultados os resultados da deteção das imagens.




   

