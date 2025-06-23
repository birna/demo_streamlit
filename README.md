# 📊 Deploy de Aplicação com Streamlit Cloud

Este repositório contém uma aplicação feita com [Streamlit](https://streamlit.io/) para visualização e análise de dados. Siga os passos abaixo para clonar, rodar localmente ou publicar no Streamlit Cloud.

## ✅ Pré-requisitos

- Conta no GitHub
- Conta no [Streamlit Cloud](https://streamlit.io/cloud)
- Aplicação Python com dependências listadas no `requirements.txt`

## 🧾 Requisitos

Crie um arquivo `requirements.txt` com as bibliotecas utilizadas pela sua aplicação. Exemplo:

```txt
streamlit
pandas
numpy
scikit-learn
seaborn
plotly
matplotlib
```

## 🚀 Publicando no Streamlit Cloud

1. **Crie um repositório no GitHub**  
   Suba todos os arquivos da sua aplicação, incluindo o `requirements.txt` e o arquivo principal (ex: `app.py`).

2. **Crie uma conta no Streamlit Cloud**  
   Acesse [https://streamlit.io/cloud](https://streamlit.io/cloud) e clique em **"Sign in with GitHub"** para conectar sua conta do GitHub.

3. **Crie a aplicação no Streamlit Cloud**  
   - Clique em **"New app"**  
   - Escolha o repositório onde sua aplicação está  
   - Selecione a *branch* correta (geralmente `main`)  
   - Informe o caminho do arquivo principal (ex: `app.py`)

4. **Clique em "Deploy"**  
   Aguarde alguns minutos enquanto a aplicação é publicada.

5. **Acesse o link gerado**  
   O Streamlit fornecerá um link público para acessar sua aplicação.
---


## 🛠️ Rodando localmente

Para testar localmente antes do deploy:

```bash
pip install -r requirements.txt
streamlit run app.py
```

---

Feito com ❤️ usando [Streamlit](https://streamlit.io/)