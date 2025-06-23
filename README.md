# demo_streamlit
Deploy Cloud StreamLit
📊 Deploy de Aplicação com Streamlit Cloud
Este guia descreve como preparar e publicar sua aplicação Streamlit no Streamlit Cloud a partir de um repositório no GitHub.

✅ Pré-requisitos
Conta no GitHub

Conta no Streamlit Cloud

Aplicação pronta em Python (ex: app.py)

🚀 Passo a Passo
Criar o arquivo requirements.txt
Crie um arquivo chamado requirements.txt na raiz do seu repositório. Este arquivo deve listar todas as bibliotecas utilizadas pela sua aplicação. Exemplo:

txt
Copiar
Editar
streamlit
pandas
numpy
scikit-learn
seaborn
plotly
matplotlib
Criar um repositório no GitHub
Crie um novo repositório no GitHub e faça o upload de todos os arquivos do seu projeto, incluindo o requirements.txt e o arquivo principal (ex: app.py).

Criar uma conta no Streamlit Cloud
Acesse streamlit.io/cloud e clique em "Sign in with GitHub" para criar sua conta vinculando ao GitHub.

Criar a aplicação no Streamlit Cloud

Faça login no Streamlit Cloud.

Clique em "New app".

Escolha o repositório do GitHub, selecione a branch (geralmente main ou master) e informe o caminho para o arquivo principal (ex: app.py).

Deploy da aplicação
Clique em "Deploy" e aguarde alguns minutos até que a aplicação seja disponibilizada.

Acessar a aplicação
Após o deploy, o Streamlit Cloud fornecerá um link público. Acesse esse link para visualizar e testar sua aplicação.

