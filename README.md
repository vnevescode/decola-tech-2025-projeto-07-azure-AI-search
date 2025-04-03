# Projeto-07-azure-AI-search

![Capa_projeto_07](https://github.com/user-attachments/assets/79def1f2-2161-42e0-b94e-605665f9aac1)

Projeto que faz analise de documentos em containers de armazenamento na Azure com documentos docx utilizando o Ai Search

---

# Análises com o AI Search


## ☕ Azure AI Search - Customer Reviews Insights (Fourth Coffee)
Este projeto demonstra como criar uma solução de Knowledge Mining usando Azure AI Search, Azure AI Services e Azure Blob Storage, baseado nos reviews dos clientes da fictícia rede de cafeterias Fourth Coffee.

A solução permite a extração automática de informações relevantes dos documentos, enriquecimento com inteligência artificial e consulta estruturada por meio de um índice de pesquisa.

---

## 📦 Tecnologias Utilizadas
**Azure Blob Storage**: Armazena os arquivos (reviews dos clientes) em formato .json.

**Azure AI Search**: Indexa os documentos do Blob Storage, aplicando técnicas de busca textual, OCR e enriquecimento semântico.

**Azure AI Services**: Fornece capacidades cognitivas como extração de sentimentos, localização, palavras-chave, tags de imagem, entre outros.

---

## 🛠️ Passo a Passo: Como configurar a solução

Seguir o link do tutorial a seguir : 

``` bash 
https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html
```

---

## 🔍 Exemplos de Consultas no Search Explorer

### Consultas do tutorial
``` bash 
{
  "search": "*",
  "count": true
}
```
``` bash 
{
  "search": "locations:'Chicago'",
  "count": true
}
```
``` bash 
{
  "search": "sentiment:'negative'",
  "count": true
}
```


### Consultas extras
``` bash 
{
  "search": "keyphrases:'latte'",
  "count": true
}
```
``` bash 
{
  "search": "imageTags:'cup'",
  "count": true
}
```
``` bash 
{
  "search": "merged_content:'Wi-Fi'",
  "count": true
}
```
---
# 🧠 Insights e Resultados

## Fotos das telas

![image](https://github.com/user-attachments/assets/bd1c1a09-4a5d-4089-876d-f853ccd9f1da)
![image](https://github.com/user-attachments/assets/884d9d8c-439a-4dc3-a99b-d23d32dd283b)
![image](https://github.com/user-attachments/assets/00392889-f8f9-4e8e-a061-dd74dfed1bcf)

--- 

## 📊 Insight extraído da consulta: merged_content:'Wi-Fi'

### ✅ Resumo dos resultados
A consulta retornou 2 documentos, ambos com sentimento positivo e menções claras ao uso e qualidade do Wi-Fi.

## 📍 Documento 1

**Localização**: Seattle, Washington

**Sentimento**: Positivo

**Comentário relevante**: "Also did I mention that the wi-fi is excellent?"

**Contexto adicional**: Além do Wi-Fi, o cliente aprecia a arte local, as aquarelas e os cartões vendidos no local.

**Tags de imagem**: laptop, table, painting, art etc.

**Legenda gerada por IA**: "a person sitting at a table"

**Insight**: O cliente valoriza não apenas a experiência do café, mas também o ambiente artístico e a conectividade com internet de qualidade, o que pode indicar um ambiente propício para trabalhar ou relaxar.

## 📍 Documento 2

**Localização**: Chicago, Illinois

**Sentimento**: Positivo

**Comentário relevante**: "There are also plenty of drink selections, good wi-fi, and seating."

**Contexto adicional**: Cliente usa o local para reuniões com clientes, destacando o bom atendimento, variedade de bebidas e ambiente confortável.

**Tags de imagem**: laptop, people, restaurant, indoor

**Legenda gerada por IA**: "a woman showing a woman something on a tablet"

**Insight**: O local é visto como ideal para reuniões profissionais e encontros de negócios informais, graças ao bom Wi-Fi, atendimento e estrutura.

## 💡 Conclusão dos insights
O Wi-Fi de qualidade é mencionado de forma espontânea e com forte associação positiva.

Clientes percebem o espaço como adequado para produtividade (trabalho, reuniões) e confortável para permanência prolongada.

O uso de Wi-Fi é um diferencial competitivo que reforça a experiência completa do cliente: boa bebida, ambiente agradável e conectividade.



---
## 📚 Aprendizados Adquiridos

-- Como estruturar um pipeline completo de Knowledge Mining.

-- Aplicação prática dos serviços cognitivos da Azure.

-- Construção e uso de índices de busca enriquecidos com IA.

-- Habilidade de explorar dados textuais e visuais com consultas personalizadas.

---
