# analise-sentimentos
Criando um Projeto no Azure AI Foundry
Antes de tudo, precisamos criar um projeto dentro do Azure AI Foundry, que é a plataforma da Microsoft para desenvolver soluções de IA.

Acesse o Azure AI Foundry.
Entre na sua conta.
Clique em Create a project.
Escolha um nome para o projeto ou mantenha o gerado automaticamente.
Selecione Criar novo hub, defina um nome exclusivo e clique em Avançar.
Configure o local do recurso (East US, France Central, Korea Central, West Europe ou West US).
Clique em Create.
Aguarde a criação dos seguintes recursos:
Serviços de IA do Azure
Hub de IA do Azure
Projeto de IA do Azure
Conta de armazenamento
Cofre de chaves
Grupo de recursos
Após a criação, acesse a aba Playgrounds.
Testando os Recursos do Azure AI Language
Dentro do Playground de Linguagem do Azure AI Foundry, podemos testar as funcionalidades do Azure AI Language.

1. Extraindo Entidades Nomeadas
As entidades nomeadas representam informações específicas dentro de um texto, como nomes de pessoas, locais e datas.

Acesse Extract Information.
Selecione Extract Named Entities.
Cole o seguinte texto de exemplo:
Tired hotel with poor service
The Royal Hotel, London, United Kingdom
5/6/2018
This is an old hotel (has been around since 1950's) and the room furnishings are average - becoming a bit old now and require changing. The internet didn't work and had to come to one of their office rooms to check in for my flight home. The website says it's close to the British Museum, but it's too far to walk.


2. Extraindo Frases-Chave
Essa funcionalidade permite identificar as informações mais relevantes dentro de um texto.

Acesse Extract Information.
Selecione Extract Key Phrases.
Cole o seguinte exemplo:
Good Hotel and staff
The Royal Hotel, London, UK
3/2/2018
Clean rooms, good service, great location near Buckingham Palace and Westminster Abbey, and so on. We thoroughly enjoyed our stay. The courtyard is very peaceful and we went to a restaurant which is part of the same group and is Indian (West coast so plenty of fish) with a Michelin Star. We had the taster menu which was fabulous. The rooms were very well appointed with a kitchen, lounge, bedroom and enormous bathroom. Thoroughly recommended.
Clique em Run e revise as frases-chave extraídas.
O sistema identifica palavras e frases que capturam a essência do texto.


3. Resumindo Textos
A função de sumarização permite reduzir um texto grande em um resumo conciso.

Acesse Summarize Information.
Selecione Summarize Text.

  Cole este exemplo:
Very noisy and rooms are tiny
The Lombard Hotel, San Francisco, USA
9/5/2018
Hotel is located on Lombard street which is a very busy SIX lane street directly off the Golden Gate Bridge. Traffic from early morning until late at night especially on weekends. Noise would not be so bad if rooms were better insulated but they are not. Had to put cotton balls in my ears to be able to sleep--was too tired to enjoy the city the next day. Rooms are TINY. I picked the room because it had two queen size beds--but the room barely had space to fit them. With family of four in the room it was tight. With all that said, rooms are clean and they've made an effort to update them. The hotel is in Marina district with lots of good places to eat, within walking distance to Presidio. May be good hotel for young stay-up-late adults on a budget.
