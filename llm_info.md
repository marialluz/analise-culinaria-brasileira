# Informações sobre o Uso da LLM

## 🤖 Modelo de Linguagem Utilizado
- **ChatGPT 4.0** (OpenAI)

---

## 🎯 Objetivo do Uso da LLM
O modelo de linguagem foi utilizado para **identificar os ingredientes** a partir das imagens de 51 receitas da culinária brasileira, conforme solicitado na tarefa.

Além disso, o modelo também foi responsável por **classificar cada ingrediente** em uma das categorias definidas:

- **Proteína**
- **Carboidrato**
- **Vegetal**
- **Fruta**
- **Laticínio**
- **Gordura**
- **Condimento**
- **Leguminosa**
- **Outro**

---

## 💬 Prompt Utilizado
O seguinte prompt foi aplicado de forma padrão para cada imagem de receita:

> **Prompt:**
> 
> *"Você é um especialista em gastronomia brasileira. A partir da imagem fornecida, identifique o nome da receita e os ingredientes mais prováveis utilizados na receita apresentada. Liste apenas os ingredientes principais, separando por vírgulas, sem quantidades ou modos de preparo. Além disso, classifique cada ingrediente em uma das seguintes categorias: Proteína, Carboidrato, Vegetal, Fruta, Laticínio, Gordura, Condimento, Leguminosa, Outro."*

---

## 📂 Resultado
As respostas da LLM foram organizadas no arquivo `Ingredientes.csv`, contendo:

- Nome da receita
- Lista de ingredientes principais
- Tipos de ingredientes
- Estado de origem da receita

Esse arquivo serviu de base para a construção do grafo e a análise de assortatividade.

