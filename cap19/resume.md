# O Que é Um Chatbot?

Um  chatbot  é  um  programa  de  computador  desenvolvido  para  simular  conversas humanas. Ele é projetado para interagir com os usuários em linguagem natural, geralmente através  de  interfaces  de  mensagens  como  websites,  aplicativosde  mensagens  móveis  ou plataformas de redes sociais.

Os chatbots são comumente usados para lidar com consultas de atendimento ao cliente, responder  perguntas  frequentes,  realizar  tarefas  de  agendamentoou  fornecer  informações detalhadas sobre um produto ou serviço. Eles são programados para responder de maneira a simular a conversação humana e são especialmente úteis para lidar com interações repetitivas, liberando tempo para que os humanos lidem com tarefas mais complexas.

Existem dois tipos principais de chatbots:

Chatbots  baseados  em  regras:  Esses  chatbots  respondem  a  consultas  específicas  e seguem um conjunto pré-definido de regras. Eles são limitados em termos de capacidade de compreensão e não conseguem lidar com perguntas fora das regras pré-definidas.

Chatbots  baseados  em Inteligência Artificial:  Esses  chatbots  utilizam  técnicas  de Processamento de Linguagem Natural(PLN)e Aprendizado de Máquina (Machine Learning) para entender melhor a intenção do usuário e fornecer respostas mais naturais e contextualmente relevantes. Modelos de linguagem como GPT-3 e GPT-4 da OpenAI são exemplos de tecnologia usada  para  construir  chatbots  baseados  em Inteligência Artificial.O  ChatGPT é  um  chatbot baseado em IA. Esse é o tipo de chatbot que iremos construir agora no Projeto 3.

Esses bots são capazes de aprender com as interações passadas, melhorando assim a qualidade das respostas ao longo dotempo. Eles podem gerenciar uma variedade de perguntas e até mesmo participar de conversas mais complexas com os usuários

# O Que é Um Modelo de Linguagem?

Os  modelos  de  linguagem  são  tipos  de  modelos  de  aprendizado  de  máquina (Machine Learning) que  foram  treinados  para  entender  e  gerar  texto  em  linguagem  humana.  Eles  são capazes de realizar várias tarefas relacionadas à linguagem, como tradução de texto, resposta a perguntas, resumo de texto, geração de texto criativo e muito mais.

Os modelos de linguagem são treinados em grandes quantidades de texto para aprender padrões  na  linguagem  humana,  incluindo  gramática,  sintaxe,  estilo,  tom  e  até  mesmo  alguns fatossobre  o  mundo.  Uma  vez  treinados,  eles  podem  gerar  texto  que  é  frequentemente indistinguível do texto escrito por humanos.

Existem vários tipos de modelos de linguagem, mas os mais recentes e mais poderosos são baseados em uma técnica chamada Transformer. Esses modelos, como o GPT-4 da OpenAI, usam   uma   arquitetura   de   rede   neural artificial conhecida   como   Transformer,   que   é especialmente  eficaz  para  entender  o  contexto  e  a  estrutura  em  sequências  de  texto.O  Deep Learning Book traz vasto material gratuito sobre os Transformers:
https://www.deeplearningbook.com.br/transformadores-o-estado-da-arte-em-processamento-de-linguagem-natural/

Os  modelos  de  linguagem  são  usados em  assistentes  de  voz  como  a  Siri  e  a  Alexa,  em chatbots, em ferramentas de escrita assistida por IA, em sistemas de tradução automática, e em muitos outros aplicativos onde a compreensão ou geração de texto é necessária.

Os modelos de linguagem são estudados aqui na DSA na Formação Engenheiro de IA, em especial  no  curso  de  Processamento  de  Linguagem  Natural  com  Transformers. 

# Generative Pre-Trained Transformer (GPT)

GPT significa Generative Pre-Trained Transformer, um modelo lançado pela OpenAI em 2018.  É  um  modelo  de  linguagem  desenvolvido  para  obter  texto  como  se  fosse  gerado  por humanos.

Baseia-se  principalmente  no  conceito  de  transformadores,  que  forma  a  base  de  seu algoritmo. Transformer é um tipo de arquitetura de rede neural que usa uma camada de auto-atenção para identificar as relações entre diferentes partes da entrada, como palavras em uma frase.Aqui está o paper original da pesquisa sobre a camada de auto-atenção:
https://arxiv.org/abs/1706.03762

O  GPT  tem  várias  camadas  de  transformadores  empilhados  uns  sobre  os  outros.  Cada camada recebe a entrada da camada anterior, processausando camadas de auto-atenção e feed-forward e, em seguida, passa sua saída para a próxima camada na arquitetura. A saída da camada final é usada para obter o texto previsto.

Com base nas palavras anteriores, o GPT usa esse conceito para prever a próxima palavra em uma frase. Isso permite que o modelo aprenda os padrões e relacionamentos nos dados de umidioma para que possa gerar um texto coerente e contextualmente apropriado. Assim, o GPT tem uma variedade de aplicações em classificação de texto, tradução automática e geração de texto.

Com o tempo, a OpenAI lançou várias versões avançadas do GPT. Vejamos brevemente as características especiais de cada um deles:

1. GPT-2: Modelo GPT disponível gratuitamente. A seguir estão suas características:

a.  Ele  foi  treinado  em  um  corpus  de  dados  com  quase  1,5  bilhão  de  parâmetros, permitindo que o modelo estude padrões mais complexos e gere textos mais semelhantes aos humanos.

b.  Possui  um  recurso  para  limitar  o  número  de  previsões  que  o  impede  de  gerar  texto inapropriado ou enganoso.

2. GPT-3: É mais robusto e avançado que o GPT 2. Alguns recursos interessantes são:

a. Ele é treinado em 175 bilhões de parâmetros, tornando-o muito maior que o GPT-2.

b. O OpenAI introduziu um novo recurso chamado "aprendizagem de poucos tiros" ("few-shot learning") e "aprendizado de tiros zero" ("zero-shot learning"), que permite que o modelo tenha um bom desempenho em tarefas nas quais não é treinado. Isso é obtido por meio de pré-treinamento em conjuntos de dados muito diversos.

c. Outro recurso chamado "aprendizagem no contexto" permite que o modelo aprenda com as entradas simultaneamente e ajuste suas respostas de acordo.


3. GPT-3.5: Esta é uma versão mais avançada do GPT-3. Ele executa todas as tarefas que o GPT-3 faz, mas com maior precisão. Está incorporado no ChatGPT em versão gratuita.

4. GPT-4: Esta versão mais recente é 10 vezes mais avançada que sua antecessora. Ele é treinado  para  resolver  problemas  mais  complexos  e  entende  dialetos  que  são  extremamente difíceis para qualquer outro modelo de linguagem entender, pois os dialetos variam de lugar para lugar. Ele pode sintetizar histórias, poemas, redações, etc., e responder aos usuários com alguma emoção.

Outra característica impressionante do GPT-4 é que ele é capaz de analisar imagens. Ele pode ser usado para gerar legendas automáticas e responder a perguntas com base na imagem de entrada. No entanto, não pode sintetizar imagens por conta própria.

Estamos neste momento da história humana ajudando a construir as tecnologias que vão impactar anossa geração e asgerações futurasatravés da Inteligência Artificial. Isso não é incrível?

Os  modelos  GPT  são  estudados  em  detalhes  na  Formação  Engenheiro  de  IA  com Linguagem Python, através de diversos projetos práticos. Confira:
https://www.datascienceacademy.com.br/bundle/formacao-engenheiro-de-ia