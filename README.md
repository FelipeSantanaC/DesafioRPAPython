# Desafio RPA - Preenchimento Automático de Formulário

Este é um projeto que visa automatizar o preenchimento de um formulário da web usando o Selenium WebDriver em Python.

# Descrição
O script Python lê os dados de um arquivo Excel (formato .xlsx) e preenche automaticamente um formulário da web com esses dados. O objetivo é demonstrar a automação de tarefas repetitivas usando Selenium WebDriver.

# Funcionalidades
- Automatiza o preenchimento de formulários web com dados de um arquivo Excel.
- Usa o Selenium WebDriver para interagir com o navegador Chrome.

# Dependências
Para executar este projeto, você precisará ter o seguinte instalado:
- Python 
- Selenium
- Pandas
- Openpyxl
- Google Chrome

# Clone
Você pode clonar o repositório usando: git clone https://github.com/FelipeSantanaC/DesafioRPAPython

# Instalação
Certifique-se de ter o Python instalado.

Instale o Selenium, Pandas e Openpyxl usando o pip:
- pip install selenium
- pip install pandas
- pip install openpyxl
  
OBS: Se der erro na instalação, colocar o --user no final. Exemplo: pip install selenium --user

Baixe e instale o Chrome WebDriver (ChromeDriver) de acordo com a versão do seu navegador Chrome. Você pode encontrar o ChromeDriver em https://sites.google.com/a/chromium.org/chromedriver/downloads.
Coloque o arquivo challenge.xlsx na mesma pasta do script Python.

# Uso
Execute o script Python main.py.
- python main.py

O navegador será aberto automaticamente e começará a preencher o formulário com os dados do arquivo challenge.xlsx.
Após o preenchimento do formulário, aguarde o tempo especificado no script antes de fechar o navegador.
