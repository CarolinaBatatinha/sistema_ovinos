# Sistema para Análise de Dados na Criação de Ovinos para Reprodução 
<h4 align="center"> 
    :construction:  <b>EM CONSTRUÇÃO</b>  :construction:
</h4>

Esse projeto visa a criação de um sistema, voltado à análise do ciclo completo da criação de ovinos destinados à reprodução (*a princípio*), desde o nascimento até a destinação final.

## Estratégia e Ambiente:

Por se tratar de um sistema (*inicialmente*) offline, serão empregadas as tecnologias descritas abaixo:
- Linguagem de programação: *Python*
- Framework web: *Streamit*
- Banco de dados:  *SQLite*
- Bibliotecas de análise de dados: *Pandas, Matplotlib*
  
## Estrutura das Pastas

A ideia inicial da arquitetura MVC confere ao sistema as seguintes pastas e arquivos:

```
sistema_ovinos/
├── controllers/
│   ├── __init__.py
│   └── animal_controller.py    # Controlador para operações com animais
└── data/
│   ├──  rebanho.db             # Banco de dados SQLite
├── models/
│   ├── __init__.py
│   ├── database.py             # Modelo de dados e conexão com o banco de dados
│   └── animal.py               # Classe Animal
├── utils/
│   ├── __init__.py
│   ├── reports.py              # Geração de relatórios
│   └── charts.py               # Geração de gráficos
├── views/
│   ├── __init__.py
│   └── interface.py            # Interface do usuário Streamlit
├── app.py                      # Aplicação principal Streamlit
└── README.md
```