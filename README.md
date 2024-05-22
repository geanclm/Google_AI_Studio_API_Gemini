<h1>Projeto com o uso da API Gemini da Google</h1>

O objetivo nesse pequeno projeto foi o de explorar e testar, através de ajuste dos parâmetros, o recurso da API Gemini da Google,
com perfis de respostas diferentes. Quatro personas foram inicialmente definidas e podem responder de forma diferente.
Um aspecto importante para entender a importância não somente da engenharia dos prompts mas também da capacidade
de cada IA em responder de acordo com a configuração predefinida dos parâmetros, seja Top K, Top P e Temperature.

A persona de IA criada se chama "Wise" e pode assumir quatro perfis:

- Wise, o diversificado
	-  (maior contexto e menos precisão)

- Wise, o moderado 
	- (intermediário, e pode ficar em cima do muro!)

- Wise, o assertivo
	- (maior precisão)


- Wise, o mestre
	- (maior probabilidade de contexto e auxílio na construção de conhecimento)

<br>
Código:

- As conversas são salvas no Google Drive e é possível listá-las

- Foram inseridos exemplos de promtp "ZERO-SHOT PROMPTING" e "CHAIN-OF-THOUGHT PROMPTING" para melhor instruir o modelo LLM nas respostas

- Gráfico das expressões mais frequentes nas conversas.


<br>
Em estudo:

- API Gemini embeddings
	- Para identificar semântica no texto e sugerir próximas ações ao usuário


<br>
Insights:
0 - Alicerce primordial de aprendizado: engenharia de prompt;
1 - A personalização de um agente permite atender uma necessidade específica do usuário;
2 - O uso de embeddings parece ser uma ótima solução para compor contextualização específica
acerca de um cenário definido. Por exemplo: é possível criar uma banco de dados reduzido com os tokens
da mesma informação e agrupado por assunto. O recurso de embeddings permite economizar
recurso de espaço e tempo em consulta;
3 - Com o domínio dos dados diários do usuário será possível recomendar as próximas ações,
seja pessoal, profissional, social e outras inerentes e de interesse;