# Python Insight - Análise de Dados
+ Utilizada uma base de dados (.csv) com 50 mil registros.
+ Analisando os cancelamentos das assinaturas de clientes, visando identificar padrões e motivos.

Nesta análise, foi importada a base de dados para o código utilizando a biblioteca Pandas para visualizar e entender as informações.
Foram identificados problemas/erros com relação a informações faltando (campo vazio).
Como eram minoria (4 linhas), o tratamento seguiu deletando-as da operação.
Na análise inicial, por meio de gráficos gerados a partir da biblioteca Plotly, foram identificados casos extremos na quantidade de cancelamento das assinaturas.
Em uma análise detalhada, foram reportadas as causas e possíveis soluções para estas.
Filtrando os casos extremos, a taxa de cancelamento de 56.8% teve uma considerável queda para 4.9%.

**Como executar:**
```bash
No VS Code baixe a extensão Jupyter.
Garanta ter instalado Python na sua máquina.
Alterar o kernel (o motor de execução) no canto superior direito da tela do seu caderno.
No menu superior, clique para executar.
```

**Ferramentas utilizadas:**
- Visual Studio Code
- Jupyter
- Python 3
- Bibliotecas: Pandas, Plotly, Nbformat e Ipykernel
