# Eleitores da Paraíba 🗳️  

Este repositório contém um notebook desenvolvido no **Google Colab** voltado para a análise e **visualização geográfica interativa** do eleitorado da Paraíba.  

## 📌 Descrição  
O objetivo do projeto é explorar e visualizar a distribuição dos eleitores no estado da Paraíba a partir de um **mapa interativo**, permitindo compreender melhor a composição do eleitorado por região.  

- Foram utilizados **dados oficiais do IBGE** (geográficos) e uma **base fornecida por um cliente**, contendo a quantidade de eleitores por **sexo/gênero**.  
- Combinando **GeoPandas** e **Folium**, o notebook gera um **mapa interativo do estado da Paraíba**, que é exportado como **HTML** para fácil visualização em qualquer navegador.  

Atualmente, este é apenas o **primeiro passo** de uma ferramenta mais completa, que será expandida com análises adicionais, comparações e novos filtros.  

## 🚀 Tecnologias utilizadas  
- Google Colab  
- Python 3  
- Bibliotecas principais:  
  - `pandas`  
  - `geopandas`  
  - `folium`
    
## 📂 Estrutura do projeto  
- `Eleitores_da_Paraíba.ipynb` → notebook com o código de análise e geração do mapa.  
- `Eleitores_da_Paraíba.html` → mapa interativo gerado pelo notebook (abrir em qualquer navegador).  

## 🛠️ Como usar  
### Opção 1 – Executar no Google Colab  
1. Acesse o notebook diretamente no Colab.  
2. Execute as células para carregar os dados e gerar novamente o mapa interativo.  

### Opção 2 – Visualizar apenas os resultados  
- Baixe ou abra o arquivo `Eleitores_da_Paraíba.html` no navegador e explore o **mapa interativo do estado da Paraíba**.  

## 📊 Próximos passos  
- Adicionar filtros para selecionar regiões específicas;  
- Incluir comparações entre diferentes eleições;  
- Explorar relações estatísticas entre variáveis socioeconômicas e eleitorado;  
- Criar versão em dashboard interativo.  

## ⚠️ Observação  
Alguns trechos de código foram inspirados em fontes externas (como exemplos de notebooks e fóruns). Caso você identifique algum trecho de sua autoria, entre em contato para que eu adicione a devida referência.  
