# Certificados Automáticos de Participação

## Descrição do Projeto
Este projeto automatiza a geração de certificados personalizados para cursos ou treinamentos. Com base em uma lista de participantes (fornecida em um arquivo CSV) e utilizando um template gráfico, os certificados são gerados em PDF contendo informações específicas, como nome do participante, título do curso, datas e carga horária.

## Funcionalidades
- Geração automática de certificados personalizados em formato PDF.
- Baseado em um template gráfico pré-definido.
- Possibilidade de personalização dos textos e layout diretamente no script.

## Arquivos do Projeto
- **`app.py`**: Script Python principal que realiza a geração dos certificados.
- **`dados.csv`**: Arquivo com a lista dos participantes. Deve conter uma coluna `nomecompleto`.
- **`template.png`**: Template gráfico utilizado como plano de fundo dos certificados.

## Tecnologias Utilizadas
- **Python**: Linguagem principal do projeto.
- **FPDF**: Biblioteca para geração de arquivos PDF.
- **Pandas**: Biblioteca para manipulação de dados.
  
## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com sugestões e melhorias.

## Pré-requisitos
Certifique-se de ter o Python instalado em sua máquina. Em seguida, instale as dependências necessárias:


```bash
pip install fpdf pandas
