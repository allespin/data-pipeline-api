# Pipeline de dados com integração via API 🎓

<img width="1202" height="852" alt="image" src="https://github.com/user-attachments/assets/9d45f49f-9fc5-44c2-a1a6-f6b5a76bd454" />


Projeto de pipeline de dados (ETL) desenvolvido para demonstrar o processo de extração, transformação e disponibilização de dados por meio de uma API REST.

Os dados são carregados a partir de um arquivo CSV contendo informações de alunos, passam por etapas de processamento e são disponibilizados em formato estruturado para consumo por aplicações externas. A solução simula um cenário de integração de dados, permitindo que ambientes de análise e serviços em nuvem, como o Google Colab, acessem as informações de forma padronizada.

O projeto aborda conceitos fundamentais de engenharia de dados, incluindo ETL, integração de sistemas, exposição de dados via API e consumo remoto de informações.


## 🚀 Tecnologias Utilizadas
- **Python**
- **Google Colab**
- **FastAPI**: Criação da API e documentação automática (Swagger).
- **Pandas**: Para leitura e manipulação do arquivo CSV.
- **Uvicorn**: Servidor para rodar a aplicação.
- **Ngrok**: Permite expor a API via nuvem para qualquer pessoa acessar remotamente

## 📋 Como Executar
1. Instale as dependências: `pip install -r requirements.txt`
2. Inicie o servidor: `uvicorn main:app --reload`
3. Acesse o Swagger em: `http://127.0.0.1:8000/docs`
