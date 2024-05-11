<h1>Projeto com o uso da API Gemini da Google</h1>

O objetivo nesse pequeno projeto é testar, através de ajuste dos parâmetros, o recurso da API Gemini
com perfis de respostas diferentes. Quatro personas foram definidas e podem responder de forma diferente,
ponto importante para entender a importância não somente da engenharia dos prompts mas também da capacidade
de cada IA em responder de acordo com a configuração predefinida dos parâmetros.

A persona criada se chama "Wise" e pode assumir quatro perfis:

- Wise, o diversificado
	-  (maior contexto e menos precisão)

- Wise, p moderado 
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
Em andamento:

- API Gemini embeddings
	- Para identificar semântica no texto e sugerir próximas ações ao usuário