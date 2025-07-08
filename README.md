
# Arquitetura RPA

Descrição breve do projeto de automação Python.


## Estrutura do Projeto

```plaintext
arquitetura_rpa/
│
├── config/
|   ├── __init__.py
|   ├── .env
|   └── config.py
|
├── database/
│   ├── models/
|   |   └──tabela.py
│   └── conexao.py
│   
├── docs/
│   └── arquivo.docx
│
├── exceptions/
│   ├── __init__.py
|   └── exceptions.py
│
├── image/
|
├── logs/
|   └──anomesdia.log
|
├── scripts/
|   └── script1.py
|
├── tests/
|   └── tests_script1.py
|
├── utils/
|   ├── __init__.py
|   └── funcoes_projeto.py
│
├── .gitignore
├── mestre.py
├── readme.md
└── requirements.txt
```

## Descrição das Pastas e Arquivos

### config/
Contém as configurações de variaveis globais.
- `__init__.py`: Este arquivo armazena as variaveis gerais.
- `.env`: Este arquivo armazena variaveis privadas.
- `config.py`: Este arquivo armazenar as variaveis do projeto.

### database/
Contém arquivos relacionados ao banco de dados.
- `models/tabela.py`: Este arquivo armazena as classes que representam as tabelas do banco de dados.
- `conexao.py`: Configurações acesso ao banco.

### docs/
Diretório para armazenar documentos.
- `arquivo.docx`: Este arquivo armazena todo passo a passo de como realizar os processos manualmente .

### exceptions/
Contém os testes unitários para os scripts de automação.
- `__init__.py`: Armazena exceções gerais.
- `exceptions.py`: Armazena exceções do projeto.

### image/
Contém as imagens necessarias do projeto.

### Logs/
Contém os arquivos de log do sistema.

### Scripts/
Contém os arquivos de responsaveis pelas automações do projeto.
- `script1.py`: Armazena o script de automação do processo.

### Tests/
Contém os arquivos de teste dos scripts.
- `tests_scripts1.py`: Armazena o script de teste do arquivo script1.

### Utils/
Contém as funcoes globais.
- `__init__.py`: Armazenas as funções gerais.
- `funcoes_projeto`: Armazena as funções do projeto.

### Arquivos Raiz
- `.gitignore`: Arquivo que especifica quais arquivos e diretórios devem ser ignorados pelo Git.
- `meste.py`: Script de controle de execução dos scripts.
- `README.md`: Arquivo de documentação do projeto. Deve conter informações sobre o projeto, como configurar e executar.
- `requirements.txt`: Lista de dependências do projeto. Deve conter todos os pacotes Python necessários.


