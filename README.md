# Mini-projeto-de-Intelig-ncia-Artificial-com-linguagem-Python
Este repositório contém o desenvolvimento de um mini modelo de Inteligência Artificial criado a partir de linguagem python para fins de estudo e experimentação. Aqui serão adicionados códigos, datasets, testes, treinamentos e melhorias relacionadas ao funcionamento do modelo. 
pip install scikit-learn
ia_simples.py
# Importando a biblioteca de Machine Learning
from sklearn.feature_extraction.text import CountVectorizer
from sklearn.naive_bayes import MultinomialNB
# 1. Os dados (Exemplos que a IA vai usar para aprender)
frases = [
"Eu amo programação"                  Positivo          1
"Eu odeio bugs"                       Negativo          0
"Programar é divertido"               Positivo          1
"Código ruim me deixa triste"         Negativo          0
"Eu adoro aprender novas Linguagens"  Positivo          1
"Codar é frustante quando buga"       Negativo          0
]
#0= Negativo, #1 = Positivo
rotulos = [1, 0, 1, 0, 1, 0]
# 2. Pré-processsamento dos dados: A IA possui dificuldade e entender vetorizador 
X = vetorizador.fit_transform(frases)
#3. Criando e transformando a IA
ia = MultinomialNB()
ia.fit(X, rotulos)
# 4. Testando a IA
Frase_teste = ["Eu amo aprender novas Linguagens"]
X_teste = vetorizador.transform(Frase_teste)
X_teste = vetorizador.transform(frase_teste)
#5: A IA faz previsão
resultado = ia.predict(X_teste)
print(resultado)
#6: A IA responde
if resultado[0] == 1:
    print( "A IA acha que a frase é positiva!")
    else:
    print( "A IA acha que a frase é negativo!")
