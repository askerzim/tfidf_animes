# tfidf_animes

Hoje finalizei um sistema de recomendação baseado em conteúdo textual, usando PLN e técnicas simples, mas poderosas, para encontrar animes com sinopses parecidas.

📚 O foco foi aplicar o TF-IDF (Term Frequency–Inverse Document Frequency), uma das ferramentas mais conhecidas do PLN, para transformar sinopses em vetores que capturam a importância de cada termo no contexto do dataset.

🔍 Com isso, calculei a similaridade de cosseno entre os vetores para identificar animes com enredos semelhantes. A função recomendar(nome, matriz_similaridade) retorna os 10 títulos mais similares com base no texto — e agora, realmente com base no input do usuário!

💡 Destaques técnicos:

Aplicação prática de PLN para recomendação de conteúdo.

Vetorização com TF-IDF diretamente sobre sinopses.

Uso de similaridade do cosseno para comparar vetores de texto.

Correção de um erro comum: uso indevido de variáveis externas dentro de funções, o que antes fazia o sistema recomendar sempre os mesmos títulos (valeu, Naruto 😅).

🛠️ Melhorias futuras:

Testar modelos de embeddings semânticos como BERT.

Criar uma interface visual com Streamlit.

Integrar feedbacks dos usuários para adaptar recomendações.

🚀 Ver projetos como esse ganhando forma é um ótimo exercício para quem estuda PLN e sistemas de recomendação.

Se você trabalha com dados, curte animes ou está mergulhando em PLN, comenta aqui ou manda mensagem! Vamos trocar experiências.

#NLP #TFIDF #MachineLearning #DataScience #PLN #SistemaDeRecomendação #Python #Cosseno #Animes #ProjetosDeDados #LinkedInTech #NaturalLanguageProcessing
