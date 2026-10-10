# curso-python
Minha trajetoria com Python

## Estrutura

| Módulo | Conteúdo |
|---|---|
| [01_fundamentos](01_fundamentos/) | Fundamentos |
| [02_estruturas_de_controle](02_estruturas_de_controle/) | Estruturas de controle |
| [03_estruturas_de_dados](03_estruturas_de_dados/) | Estruturas de dados |
| [04_funcoes](04_funcoes/) | Funções |
| [05_modulos_e_pacotes](05_modulos_e_pacotes/) | Módulos e pacotes |
| [06_arquivos_e_excecoes](06_arquivos_e_excecoes/) | Arquivos e exceções |
| [07_orientacao_a_objetos](07_orientacao_a_objetos/) | Orientação a objetos |
| [08_projetos](08_projetos/) | Projetos |

Cada módulo tem um `README.md` com os tópicos (marque `[x]` quando concluir), uma pasta `aulas/` para os códigos das aulas e uma pasta `exercicios/` para os exercícios.

## Como começar

1. Instale o Python 3 em https://www.python.org/downloads/ (no Windows, marque **Add Python to PATH**).
2. Abra esta pasta no VS Code.
3. Crie e ative um ambiente virtual:
   ```powershell
   python -m venv .venv
   .venv\Scripts\activate
   ```
4. Instale as dependências (quando houver): `pip install -r requirements.txt`
5. Rode a primeira aula: `python 01_fundamentos/aulas/aula01_ola_mundo.py`

## Convenções

- Nomes de arquivos em minúsculas, sem acento e com `_` no lugar de espaço.
- Aulas: `aulaNN_tema.py`. Exercícios: `exNN_tema.py`.
- Faça um commit ao terminar cada aula ou exercício.
