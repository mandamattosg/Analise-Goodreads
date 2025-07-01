# Análise de Dados - Goodreads

Este projeto visa a prática de SQL e Análise de Dados.

A base de dados utilizada foi a Goodreads-books presente em: https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks

Esses dados, disponibilizados por "jealousleopard" no Kaggle, foram coletados a partir da API pública do Goodreads. No entanto, desde 8 de dezembro de 2020, o Goodreads deixou de emitir novas chaves de desenvolvedor para sua API pública, o que significa que não há atualizações recentes provenientes diretamente do Goodreads.

## 🛠️ Construído com
* SQL/SQLite, Python, Pandas, Matplotlib, Seaborn, NumPy, Scikit-Learn
*  O projeto foi desenvolvido no Google Colab e pode ser acessado em: https://colab.research.google.com/drive/1uFmcYDV90v5CIIIdKZ3dfx5pIuaku3hp?usp=sharing

## ⚙️ Resultados
![Captura de tela 2025-07-01 104804](https://github.com/user-attachments/assets/0d78081b-9aa9-47fc-b1bb-8529a5e9f7e4)
![Captura de tela 2025-07-01 104902](https://github.com/user-attachments/assets/5356a8cb-c916-4414-8aa0-6f81d11a7b28)
![Captura de tela 2025-07-01 104928](https://github.com/user-attachments/assets/798a4c41-4696-4441-94f0-5019eabe439a)
![Captura de tela 2025-07-01 104957](https://github.com/user-attachments/assets/c4122f7e-857c-482b-a5d7-11ee23546a17)
![Captura de tela 2025-07-01 105044](https://github.com/user-attachments/assets/3cc4589d-d7f3-4aba-b3fc-e667c8094749)
![Captura de tela 2025-07-01 105103](https://github.com/user-attachments/assets/f7e3cd23-092b-4f2f-baa2-6cff9f4d72d1)
![Captura de tela 2025-07-01 105119](https://github.com/user-attachments/assets/cc883b3d-6486-4072-ac70-96d652f86b47)

## 📊 Conclusões
A análise dos dados da base de livros revelou insights interessantes sobre o mercado editorial e o perfil dos autores:

* Autores com maior produção: Os 10 autores com mais livros publicados destacam-se pela produtividade, refletindo grande engajamento e potencial influência no mercado. Empatados em 1º lugar estão Stephen King e P. G. Wodehouse.

* Popularidade e qualidade: Os livros melhores avaliados e com grande volume de avaliações demonstram que títulos bem recebidos pelo público conseguem atingir alta popularidade. Destacam-se sagas famosas como Harry Potter, Percy Jackson, O Hobbit e Senhor dos Anéis.

* Distribuição das avaliações: A maioria dos livros recebe notas entre 3.5 e 4.5, indicando uma tendência geral de avaliações positivas, com uma parcela menor de obras excepcionais (nota 5).

* Autores melhor avaliados: Quando consideramos apenas autores com pelo menos 5 livros, os 5 com maior avaliação média mostram que é possível manter alta qualidade mesmo com volume significativo de publicações.

* Editoras mais presentes: As 10 editoras com mais livros publicados são nomes conhecidos no mercado editorial. O destaque vai para Vintage, Penguin Books e Penguin Classics.

* Idiomas dos livros: A predominância de livros em inglês reflete o foco geográfico e cultural da base analisada.

* Separação de perfis: A análise de clusters identificou 3 perfis de livros:
  * Livros grandes e bem avaliados, com popularidade média. Provavelmente obras densas que agradam ao público fiel.
  * Livros curtos, menos avaliados e com nota abaixo da média. Possivelmente obras menos conhecidas ou com menor engajamento.
  * Livros altamente populares e amplamente resenhados. Provavelmente best-sellers, livros de autores famosos, ou títulos que viralizaram nas redes. Apesar de não terem a nota mais alta, são muito lidos e comentados.

Esses insights podem guiar decisões editoriais, estratégias de marketing, e recomendações personalizadas para leitores, alinhando qualidade, quantidade e popularidade.
