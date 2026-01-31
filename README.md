# 🐦 Extração e Classificação de Sentimentos (Twitter/X API)

## 📖 Sobre o Projeto

Este repositório contém a etapa inicial de um ecossistema de análise de sentimentos. O foco aqui é a **Ingestão de Dados** e a **Rotulagem Automática (Labeling)**. Através da API do Twitter, coletamos dados reais para criar um dataset robusto que servirá de base para o treinamento de modelos de Machine Learning.

## ⚙️ Fluxo de Trabalho

1. **Extração**: Conexão com a API do Twitter via biblioteca Tweepy.

2. **Processamento**: Limpeza inicial dos textos (remoção de links, caracteres especiais, etc.).

3. **Análise de Sentimento (Léxica)**: Utilização da biblioteca **LEIA** (Léxico para Inteligência Artificial), um fork do VADER otimizado para a língua portuguesa (PT-BR).

4. **Estruturação**: Geração de um dataset rotulado em formato `.csv` para as próximas etapas de Machine Learning.

## 🛠️ Tecnologias Utilizadas

- **Tweepy**: Para autenticação e consumo da API.

- **LEIA (VADER fork)**: Classificação semântica adaptada ao contexto brasileiro.

- **Pandas**: Manipulação e estruturação dos dataframes.

- **RegEx**: Limpeza e normalização de strings.

## 🚀 Como Executar

1. Clone o repositório:

```
git clone https://github.com/alan-vieira/extrai_dados_do_twitter.git
```

2. Instale as dependências:

```
pip install tweepy leia pandas
```

3. Configure suas credenciais da API do Twitter no notebook.

**Nota**: As chaves de acesso à API foram omitidas por questões de segurança. Você deve obter suas próprias credenciais no Twitter Developer Portal.

## 📺 Demonstração

Acompanhe a explicação técnica detalhada no YouTube:

🔗 [Assistir vídeo explicativo](https://www.youtube.com/watch?v=ZqQ1eDmgF7A)

## 👤 Autor

**Alan Vieira** - *Engenheiro de Telecomunicações & Especialista em Dados*

- [LinkedIn](https://www.linkedin.com/in/alansilvavieira)

- [GitHub Portfólio](https://github.com/alan-vieira)
