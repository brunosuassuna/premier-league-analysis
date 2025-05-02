# ⚽ **Análise de Dados da Premier League 2023-2024**

**Autor:** Bruno Suassuna  
**Data:** Abril 2025  
**Fonte:** [Football-Data.org API](https://www.football-data.org/)

---

## 📖 **Descrição**

Este projeto realiza uma análise detalhada dos dados da Premier League para a temporada 2023-2024, com foco em informações sobre a **classificação dos times**, **desempenho individual dos jogadores**, **gols**, **assistências** e a correlação entre esses fatores. A análise foi realizada utilizando dados obtidos da [Football-Data.org API](https://www.football-data.org/), uma fonte confiável e completa sobre o futebol mundial.

---

## 🎯 **Objetivos**

O principal objetivo deste projeto é explorar e analisar as seguintes métricas:

1. **Classificação de Times** 📊 - A tabela de classificação atualizada dos times da Premier League.
2. **Análise de Artilheiros** ⚽ - Desempenho dos jogadores com maior número de gols e assistências.
3. **Desempenho dos Times** 🏆 - Comparação entre as vitórias dos times e a distribuição de pontos na competição.
4. **Análise Combinada** 🔍 - Relação entre a posição dos times na tabela e a produção ofensiva (gols e assistências).

---

## 🛠 **Tecnologias Utilizadas**

- **Python** 🐍: Linguagem de programação para análise de dados.
- **Pandas** 📊: Biblioteca para manipulação e análise de dados.
- **NumPy** 🔢: Biblioteca para operações numéricas.
- **Matplotlib & Seaborn** 📈: Bibliotecas para visualização de dados.
- **Requests** 🌐: Biblioteca para realizar requisições HTTP à API.
- **Football-Data.org API** 📡: API utilizada para buscar dados sobre a Premier League.

---

## 🔧 **Funcionalidades**

### 1. **Carregamento e Análise de Dados** 📥
O código realiza o carregamento dos dados da API da Football-Data.org, incluindo a classificação da Premier League e os detalhes dos jogadores. Além disso, apresenta as estatísticas de gols e assistências dos principais jogadores da competição.

### 2. **Visualizações** 📊
Diversos gráficos são gerados para facilitar a visualização dos dados:
- **Gráficos de barras** 📊 mostrando a classificação dos times e o número de vitórias.
- **Gráficos de dispersão** 📍 para analisar a relação entre a posição dos times e a produção ofensiva.
- **Boxplots** 📦 para ilustrar a distribuição de pontos entre os times.

### 3. **Análise Combinada** 🔍
Foi realizada uma análise combinando a tabela de classificação dos times com as estatísticas individuais dos jogadores, permitindo uma visão mais detalhada sobre o impacto das estrelas da competição nos resultados dos times.

---

## 📂 **Estrutura do Projeto**

```bash
├── README.md                   # Este arquivo
├── data_analysis.py             # Código principal para análise dos dados
├── requirements.txt             # Dependências do projeto
└── .gitignore                   # Arquivos para serem ignorados pelo Git

```

---

## 🚀 Como Rodar o Projeto

### 1. Clonar o Repositório
Para iniciar o projeto, clone este repositório em sua máquina local:

```bash
git clone https://github.com/brunosuassuna/premier-league-analysis.git 
```

### 2. Instalar Dependências
Instale as dependências necessárias utilizando o `pip`:

```bash
pip install -r requirements.txt
```

### 3. Obter uma Chave de API
Para carregar os dados da Premier League, você precisará de uma chave da [Football-Data.org API](https://www.football-data.org/client/register). Substitua a chave no código da variável `API_KEY`.

### 4. Executar a Análise
Para rodar a análise, execute o script principal:

```bash
python data_analysis.py
```

---

## 📊 Resultados Esperados

O código gerará os seguintes resultados:

- **Tabela de Classificação da Premier League** 🏆: As 10 primeiras posições, com informações sobre jogos disputados, vitórias, empates, derrotas e pontos.
- **Top 5 Artilheiros** ⚽: Análise dos jogadores com maior número de gols e assistências.
- **Distribuição de Pontos** 📊: Um gráfico de boxplot para ilustrar a distribuição de pontos dos times na temporada.
- **Gráficos de Análise Combinada** 🔍: Relação entre a posição do time e a produção ofensiva (gols e assistências).

---

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para fazer sugestões ou abrir pull requests.

### Passos para Contribuir

1. Fork este repositório.
2. Crie uma branch para a sua funcionalidade: `git checkout -b minha-nova-funcionalidade`.
3. Faça as alterações e commit: `git commit -am 'Adiciona nova funcionalidade'`.
4. Envie para o seu fork: `git push origin minha-nova-funcionalidade`.
5. Abra um pull request.

---

## 📝 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

## ✉️ Contato
- **Email:** brunosuassuna.dev@gmail.com
- **LinkedIn:** www.linkedin.com/in/brunosuassuna
