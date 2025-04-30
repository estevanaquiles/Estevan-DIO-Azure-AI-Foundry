# Estevan-DIO-Azure-AI-Foundry
Repositório criado para laboratório de projeto de AI utilizando Azure AI - Foundry. O modelo desenvolvido tem objetivo de criar um chatbot do tipo RAG, para responder o usuário com base em documentos pré-definidos. O chat criado simula um assistente financeiro para análise de risco em investimentos.

## Os tópicos abaixo demostram as etapas de configuração do ambiente, criação de projeto no AI Foundry, seleção de modelos AI, criação de índice vetorizado para receber os arquivos PDF e testes de prompt.


##### Especificações do AI HUB para receber o projeto:
![Especificações HUB AI Foundry](https://github.com/user-attachments/assets/afc5e410-c1a5-4729-83b9-3494e2721229)

##### Interface do HUB:
![Interface do hub](https://github.com/user-attachments/assets/590fcce2-4352-47a5-8268-4b889d0aef3b)

##### Criação do projeto AI Foundry:
![criacao-do-projeto](https://github.com/user-attachments/assets/fca406ca-0fdd-4e3c-a3ef-3db4b6985db3)

##### Configuração e seleção dos modelos, Gpt-4o e Text Embedding-3-large:

![selecao-Modelo](https://github.com/user-attachments/assets/4692fe01-f62c-475f-a15b-757cdb568e66)

![implantacao-Modelo-gpt4](https://github.com/user-attachments/assets/2350208d-0d5e-4979-892f-2ddfdad59f3a)

![implantacao-Modelo-text-embeding](https://github.com/user-attachments/assets/3959ba18-363e-41ab-80ee-1b4b4bc1031e)

##### Criação de índice vetorizado, utilzado para armazenar os artigos PDF no ambiente azure blob storage:

![criação_índice_vetorizado](https://github.com/user-attachments/assets/5591ccc8-92f1-4417-a692-2c5299b6e06f)

##### Dados carregados no ambiente:
![Dados_carregados_blob_storage](https://github.com/user-attachments/assets/6f2c6aac-3536-4cd6-95db-b8370b006fb9)

##### Configuração de Prompt:
![configuração_do_prompt](https://github.com/user-attachments/assets/93d8cfb4-316a-4f54-a5c7-b182b6dc8636)

##### Perguntas e respostas do prompt:
 Foram realizadas as seguintes perguntas ao modelo: 
"Como posso avaliar os riscos envolvidos em investimentos financeiros?"
"Com base nos critérios de avaliação citados é possível definir a quantidade ideal de ativos na carteira, visando minimizar os riscos envolvidos?"
"Qual é o melhor ativo que posso escolher na Bolsa de Valores do Brasil, para evitar os riscos de mercado?"

O prompt foi eficiente ao retornar as resposta, trazendo as referências dos aquivos informados como fonte de dados.

##### Primeira pegunta e resposta:
![primeira_pergunta](https://github.com/user-attachments/assets/6aeafd9b-2fc8-4a86-8454-d6b4e959ff4b)

##### Resposta:
![referencias_na_resposta](https://github.com/user-attachments/assets/72e6b41e-e741-48d9-b4fc-c517b1b74c96)

##### Segunda pergunta e resposta:
![segunda_pergunta](https://github.com/user-attachments/assets/aeec0ce6-3d20-49fd-b8a6-d650864cd2bd)

##### Resposta:
![referencias_2_na_resposta](https://github.com/user-attachments/assets/42904e7f-99d1-4535-a7c1-ca9c7e5c39f3)

##### Terceira pergunta e resposta: 
![terceira_pergunta_bloqueio_de_prompt](https://github.com/user-attachments/assets/878b86a3-32df-4567-8ce9-3acc32174b25)

Um detalhe interessante na terceira pergunta, ela foi feita para testar o bloqeuio solicitado no prompt. Funcionado perfeitamente, o prompt não forneceu informações específica de ativos financeiro conforme solicitado na configuração ("Seja amigável mas não forneça recomendações de ativos específicos para investimento.")


##### O projeto atendeu as expectativas, como desafio futuro é possível realizar o deploy em um ponto de extremidade na web, por exemplo, e disponibilizar para testes de usuário. Possibilitando novos insights e melhorias no projeto.









