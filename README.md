Multibanco à Portuguesa: Só Falta o Pastel de Nata - Fundamentos de Inteligência Artificial e Ciência de Dados  
Licenciatura em Inteligência Artificial e Ciência de Dados  
Universidade da Beira Interior

DESCRIÇÃO:
Este projeto analisa estatísticas económicas de municípios portugueses, com foco em dois indicadores:
1. CAIXAS AUTOMÁTICAS MULTIBANCO
2. DEPÓSITOS DE CLIENTES NOS BANCOS, CAIXAS ECONÓMICAS E CAIXAS DE CRÉDITO AGRÍCOLA

Os dados utilizados foram obtidos da base de dados pública PORDATA, organizados e limpos previamente.

INSTRUÇÕES DE UTILIZAÇÃO:

1. Certifique-se de que os seguintes ficheiros estão na mesma pasta:
   - analise_municipios.py
   - dados_municipais_integrados_limpos.csv

2. Execute o script Python com um ambiente que tenha instaladas as bibliotecas:
   - pandas
   - matplotlib

3. Quando solicitado, introduza o nome de um município de Portugal (ex.: Lisboa, Porto, Braga, etc.).  
   O programa exibirá:
   - Estatísticas descritivas dos indicadores escolhidos
   - Gráficos da evolução temporal dos dados
   - Comparação com a média nacional

4. Para terminar o programa, escreva “sair” quando for solicitado o nome do município.

REQUISITOS TÉCNICOS:

- Python 3.7 ou superior
- Bibliotecas necessárias:
    pip install pandas matplotlib

OBSERVAÇÕES:

- O ficheiro CSV deve manter o nome **dados_municipais_integrados_limpos.csv**.
- Apenas municípios existentes nos dados serão analisados. Nomes incorretos resultarão numa mensagem de erro apropriada.
