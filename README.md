# Análise de Dados de Cartões de Crédito

Este projeto realiza uma análise exploratória de dados de um conjunto de dados de cartões de crédito. O código baixa um arquivo CSV do Google Drive, carrega os dados em um DataFrame do pandas, realiza uma análise exploratória e gera visualizações.

## Tecnologias Utilizadas

- **Python**
- **pandas**: Para manipulação e análise de dados.
- **matplotlib**: Para geração de gráficos.
- **seaborn**: Para visualizações estatísticas.
- **gdown**: Para download de arquivos do Google Drive.

## Funcionalidades

- **Download do arquivo CSV**: O script baixa o arquivo CSV do Google Drive.
- **Carregamento de Dados**: Carrega os dados em um DataFrame do pandas.
- **Análise Exploratória**: Realiza uma análise básica dos dados.
- **Visualizações**:
  - Histogramas das variáveis numéricas.
  - Gráfico 3D das variáveis `V1`, `V2`, e `V3`.

## Instalação

1. **Clone este repositório**:
   ```bash
   git clone https://github.com/seu_usuario/seu_repositorio.git
Navegue para o diretório do projeto:

bash
Copiar código
cd seu_repositorio
Crie e ative um ambiente virtual (opcional, mas recomendado):

bash
Copiar código
python -m venv venv
source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
Instale as dependências:

bash
Copiar código
pip install -r requirements.txt
Uso
Para executar o script, use o seguinte comando:

bash
Copiar código
python seu_script.py
Isso irá baixar o arquivo CSV, carregar os dados e gerar as visualizações.

Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.


Certifique-se de substituir `seu_usuario`, `seu_repositorio`, `seu_script.py`, e `seu_email@exemplo.com` pelos valores apropriados para o seu projeto.
