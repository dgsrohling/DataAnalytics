# 🎬 MovieLens - Dataset de Avaliações de Filmes

## 📌 Visão Geral

O **MovieLens ml-latest-small** é um conjunto de dados projetado para testes e desenvolvimento de sistemas de recomendação de filmes. Ele contém:

- ⭐ **100.836 avaliações**
- 🏷️ **3.683 tags (marcações)**
- 🎞️ **9.742 filmes**
- 👤 **610 usuários** (ativos de março de 1996 a setembro de 2018)

> ⚠️ Este é um **dataset de desenvolvimento** e pode ser atualizado no futuro. Não é recomendado para resultados científicos finais ou artigos. Para isso, utilize os datasets *benchmark* do [GroupLens](http://grouplens.org/datasets/).

Cada usuário avaliou pelo menos 20 filmes. Os dados são anonimizados e não incluem informações demográficas.

---

## 📁 Arquivos Incluídos

- `ratings.csv` — Avaliações dos usuários (0.5 a 5 estrelas)
- `tags.csv` — Marcações livres feitas pelos usuários
- `movies.csv` — Títulos dos filmes e seus gêneros
- `links.csv` — IDs para cruzamento com IMDb e TMDb

📄 Todos os arquivos estão em formato **CSV codificado em UTF-8**, com cabeçalho. Campos com vírgula são protegidos por aspas (`"`).

---

## 🔐 Licença de Uso

Você pode usar este dataset para fins de pesquisa e estudo, desde que:

- ❌ **Não afirme** que a Universidade de Minnesota ou o GroupLens endossam seu trabalho
- ✅ **Cite corretamente** o dataset em publicações (veja abaixo)
- 🔁 **Pode redistribuir** o dataset (inclusive versões modificadas), mantendo esta mesma licença
- 💸 **Não pode usar comercialmente** sem autorização prévia da equipe GroupLens

> 🛠️ Os scripts e arquivos são fornecidos "no estado em que se encontram", sem qualquer garantia.

---

## 📚 Citação

Se você usar este dataset em qualquer publicação, cite:

> **Harper, F. M., & Konstan, J. A. (2015)**  
> *The MovieLens Datasets: History and Context*  
> ACM Transactions on Interactive Intelligent Systems (TiiS), 5(4), 19:1–19:19.  
> 📎 [https://doi.org/10.1145/2827872](https://doi.org/10.1145/2827872)

---

## 🔎 Sobre o GroupLens

O [**GroupLens Research**](http://grouplens.org/) é um grupo da Universidade de Minnesota que desde 1992 estuda:

- Sistemas de recomendação
- Comunidades online
- Tecnologias móveis e pervasivas
- Bibliotecas digitais
- Sistemas de informação geográfica local

Eles operam o site [**MovieLens.org**](http://movielens.org), onde você pode testar o sistema de recomendação.

> ✉️ Contato: [grouplens-info@cs.umn.edu](mailto:grouplens-info@cs.umn.edu)

---

## ✅ Repositório Oficial de Dados

Você pode baixar este e outros datasets no site oficial:  
🔗 [http://grouplens.org/datasets/](http://grouplens.org/datasets/)