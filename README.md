# Acompanhamento de Expedição — PA ANA (J&T Express)

Painel de linhas troncal: chegada ao centro, inserção em lote e carregamento, com abas por ID, base, lotes para carregar e consulta de pedidos.

- `index.html`: painel completo (dados do JMS de 22/11/2026 já embutidos).
- `app.py`: abre o painel no Streamlit.
- `requirements.txt`: dependências.

## Publicar
1. Repositório **privado** no GitHub (o painel mostra operadores e dados da operação).
2. Suba os 4 arquivos na raiz (Add file > Upload files).
3. Em share.streamlit.io: New app > escolha o repositório, branch `main`, arquivo principal `app.py` > Deploy.

Para atualizar os dados, substitua apenas o `index.html` no repositório.
