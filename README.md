# Simulador de Lançamento de Moeda

Este projeto simples em Python utiliza Streamlit para criar um aplicativo web interativo que simula o lançamento de uma moeda. O usuário pode definir o número de tentativas e observar a convergência da média dos resultados para 0.5 (a probabilidade teórica de obter "cara" em um lançamento justo).

## Como usar:
### 1. Clone o repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git

### 2. Instale as dependências:

Snippet de código
pip install -r requirements.txt

### 3. Execute o aplicativo:

Bash
streamlit run app.py

### 4. Interaja com o aplicativo:

* Use o controle deslizante para ajustar o número de tentativas.
* Clique no botão "Executar" para iniciar a simulação.
* Observe o gráfico de linha que mostra a média dos resultados ao longo das tentativas.
* A tabela abaixo do gráfico registra os resultados de cada experimento.

## Dependências:
* pandas
* scipy
* streamlit

## Observações:

* O código inclui comentários para facilitar a compreensão.
* O aplicativo salva o histórico dos experimentos na sessão do usuário.
* A função toss_coin utiliza a distribuição Bernoulli da biblioteca SciPy para simular os lançamentos da moeda.
* O atraso de 0.05 segundos na função toss_coin é para visualização gradual dos resultados no gráfico.

## Contribuições:

* Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

* Divirta-se explorando a convergência da média para a probabilidade teórica!