# Python-database-population
Este projeto foi desenvolvido para realizar o tratamento, limpeza e preparação dos dados disponibilizados pela Receita Federal relacionados a CNPJs. O objetivo é facilitar a manipulação dessas informações para análises posteriores, integração com sistemas ou estudos de dados empresariais no Brasil.

## 📂 Sobre o Projeto

- **Linguagem:** Python
- **Funcionalidade:**
  - Carregamento dos arquivos da Receita Federal
  - Limpeza e padronização dos dados
  - Conversão de formatos
  - Filtragem de registros relevantes
  - Exportação dos dados tratados para banco de dados.

## 🛠 Tecnologias Utilizadas

- Python 3
- Pandas
- NumPy

## ⚙ Como Usar

1. Clone o repositório:
   ```bash
   git clone [https://github.com/SidemarRosa/Python-database-population]
   ```

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. Execute o script principal:
   ```bash
   python main.py
   ```

4. Os dados tratados serão salvos no banco salvo no script.

## 📂 Estrutura do Projeto

```
├── data/          # Pasta para colocar os arquivos brutos da Receita
├── output/        # Pasta onde os arquivos tratados são salvos
├── main.py        # Script principal
├── requirements.txt
└── README.md
```

## ✨ Funcionalidades Futuras

- Implementar filtros personalizados (por estado, porte, CNAE)
- Adicionar suporte a grandes volumes de dados com melhor performance
- Criação de relatórios automáticos

## 🧑‍💻 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues, sugerir melhorias ou fazer pull requests.

## 📄 Licença

Este projeto está sob a licença MIT.
