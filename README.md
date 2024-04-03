# Reconhecimento Facial e transformação de imagens em dados ![Azure](https://img.shields.io/badge/Azure-blue?style=for-the-badge&logo=microsoft%20azure&logoColor=blue&labelColor=FFFFFF&link=https%3A%2F%2Fimages.app.goo.gl%2FK7PN1jYJd57x4q7A8)

## Detectar rostos no Vision Studio

Para realizar o desafio de reconhecimento facial vamos utilizar os recursos de detecção facial do serviço Azure AI Face. Vamos utilizar o Azure Vision Studio, plataforma baseada em interface do usuário que permite explorar os recursos do Azure AI Vision sem precisar escrever nenhum código.

## Criar um recurso de serviços de IA do Azure

O primeiro passo é criar um recurso de serviços de IA de Azure em sua assinatura, caso você ainda não tenha um recurso multisserviço criado.

1. Abra o portal do Azure em https://portal.azure.com, entrando com a conta da Microsoft associada à sua assinatura do Azure.

2. Clique no botão +Criar um recurso e procure serviços de IA do Azure. Selecione criar um plano de serviços de IA do Azure. Você será levado a uma página para criar um recurso de serviços de IA do Azure. Configure-o com as seguintes configurações:
 * Assinatura: sua assinatura do Azure.
 * Grupo de recursos: selecione ou crie um grupo de recursos com um nome exclusivo. 
 * Região: Leste dos EUA.
 * Nome: insira um nome exclusivo.
 * Nível de preços: Standard S0.
 * Ao marcar esta caixa, reconheço que li e entendi todos os termos abaixo: Selecionado.
 * Selecione Revisar + criar e, em seguida, Criar e aguarde a conclusão da implantação.

![image](https://github.com/acdolive/DP02-Reconhecimento-Facial-e-transformacao-de-imagens-/assets/162451624/c9d650d0-8cfb-4e31-aa46-aadf6be9fcab)

![image](https://github.com/acdolive/DP02-Reconhecimento-Facial-e-transformacao-de-imagens-/assets/162451624/e7ef3a91-3bab-48c5-b912-1521de5c86ab)

![image](https://github.com/acdolive/DP02-Reconhecimento-Facial-e-transformacao-de-imagens-/assets/162451624/cf1dddf7-3366-43cc-b53f-69bed159f442)

![image](https://github.com/acdolive/DP02-Reconhecimento-Facial-e-transformacao-de-imagens-/assets/162451624/9802f420-8e82-4313-a0b8-124150f8b585)

## Conectar seu recurso de serviço de IA do Azure ao Vision Studio

Em seguida, conecte o recurso de serviços de IA do Azure provisionado acima ao Vision Studio. 
1. Acesse o Vision Studio em https://portal.vision.cognitive.azure.com.
2. Entre com sua conta e verifique se você está usando o mesmo diretório em que criou seu recurso de serviços de IA do Azure.
3. Na home page do Vision Studio, selecione Exibir todos os recursos no cabeçalho Introdução ao Vision.

 ![image](https://github.com/acdolive/DP02-Reconhecimento-Facial-e-transformacao-de-imagens-/assets/162451624/7ae8f3c7-db3a-4fc2-b112-cc9a67b253ed)

4. Feche a página de configurações selecionando o "x" no canto superior direito da tela.

## Detectar rostos no Vision Studio

Para realizar o primeiro exercío do desafio vá até a página inicial Introdução ao Vision, selecione a guia "Rosto" 

![image](https://github.com/acdolive/DP02-Reconhecimento-Facial-e-transformacao-de-imagens-/assets/162451624/8651b5f8-fa92-4163-bcd5-1640c03a65ee)

Selecione o bloco "Detectar faces em uma imagem".

![image](https://github.com/acdolive/DP02-Reconhecimento-Facial-e-transformacao-de-imagens-/assets/162451624/32a75bc6-d3f7-4cb4-8e8b-86d879189aa3)

No subtítulo "Experimente", reconheça a política de uso de recursos lendo e marcando a caixa.

![image](https://github.com/acdolive/DP02-Reconhecimento-Facial-e-transformacao-de-imagens-/assets/162451624/f46ff2fa-557a-4fdf-9f24-cc26358c6ed1)

Selecione cada uma das imagens de amostra e observe os dados de detecção de rosto retornados.

![image](https://github.com/acdolive/DP02-Reconhecimento-Facial-e-transformacao-de-imagens-/assets/162451624/30fa82d6-7e32-4a02-805e-22c17afcf4b7)

Para finalizar o desafio selecione suas póprias imagens e faça o exercício.

![image](https://github.com/acdolive/DP02-Reconhecimento-Facial-e-transformacao-de-imagens-/assets/162451624/32c0fed9-f8cf-42d4-bf68-1c60a45c38c7)

## Extraindo texto de imagens 

Para realizar o segundo exercío do desafio, vá até a página inicial Introdução ao Vision, selecione a guia "extrair texto de imagens" 

![image](https://github.com/acdolive/DP02-Reconhecimento-Facial-e-transformacao-de-imagens-/assets/162451624/23179c91-c605-48f8-b4c9-cd07aacd75df)

Selecione uma das imagens de amostra e observe os dados retornados.

![image](https://github.com/acdolive/DP02-Reconhecimento-Facial-e-transformacao-de-imagens-/assets/162451624/af161510-b129-4aa9-ab34-a946ccf8865f)

Para finalizar o desafio selecione suas póprias imagens e faça o exercício.

![image](https://github.com/acdolive/DP02-Reconhecimento-Facial-e-transformacao-de-imagens-/assets/162451624/19d566d7-18a2-4b4d-8cd5-8b8d71421e86)

## Análise de Imagens 

Para realizar o útimo exercío do desafio, vá até a página inicial Introdução ao Vision, selecione a guia "adicionar legendas às imagens" 

Selecione uma das imagens de amostra e observe os dados retornados.

![image](https://github.com/acdolive/DP02-Reconhecimento-Facial-e-transformacao-de-imagens-/assets/162451624/ea9c1985-2110-49dd-9b46-e285be4423ed)

Para finalizar o desafio selecione suas póprias imagens e faça o exercício.

![image](https://github.com/acdolive/DP02-Reconhecimento-Facial-e-transformacao-de-imagens-/assets/162451624/35ca71c5-41c4-40ef-b8ef-84b674d88616)

# 🧹Limpeza

Para evitar cobranças desnecessárias, exclua o recurso de serviços que foi criado para o teste.

No portal do Azure, na página Grupos de recursos, abra o grupo de recursos especificado ao criar seu espaço de trabalho do Aprendizado de Máquina do Azure.
Clique em Excluir grupo de recursos, digite o nome do grupo de recursos para confirmar que deseja excluí-lo e selecione Excluir.

![image](https://github.com/acdolive/DP01-Trabalhando-com-Machine-Learning-no-Azure-ML/assets/162451624/c8591632-8d0a-4722-b08b-44616763b7d8)
