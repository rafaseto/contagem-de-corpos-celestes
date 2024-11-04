# Contagem de Corpos Celestes

## Descrição da Aplicação

Descrição da Aplicação
Esta aplicação foi desenvolvida para ajudar os entusiastas da astronomia a aprimorarem suas habilidades de observação de astros. O programa oferece diversas imagens de galáxias, e o usuário deve identificar quantas delas estão mais adequadas visualmente para serem analisadas posteriormente. Logo, utilizamos métodos de processamento digital de imagens para contar o número de corpos celestes visíveis. Por fim, o usuário pode comparar sua contagem manual com a do programa e verificar seus acertos.

## Instalação e Execução

### Pré-requisitos

Certifique-se de ter o Python 3.x instalado. Além disso, você precisará dos seguintes pacotes Python:

- pandas
- numpy
- matplotlib
- scikit-image

### Instalação dos Pacotes

Você pode instalar os pacotes necessários utilizando o `pip`. Execute o seguinte comando no terminal:

```bash
pip install pandas numpy matplotlib scikit-image
```

## Como Executar o Código

1. Clone o repositório para o seu ambiente local:
```bash
git clone https://github.com/seuusuario/identificador-de-galaxias.git
```
2. Navegue até o diretório do projeto:
```bash
cd identificador-de-galaxias
```
3. Abra o Jupyter Notebook:
```bash
jupyter notebook
```
4. No Jupyter, abra o arquivo app.ipynb e execute as células do notebook para processar as imagens e visualizar os resultados.

 ## Estrutura do Projeto
 
- app.ipynb: Código principal da aplicação.
- apresentacao.pdf: Apresentação do projeto.
- Data/: Pasta contendo as imagens utilizadas no dataset.
- Resultados/: Pasta onde as imagens resultantes serão salvas.
- .gitignore: Arquivo para ignorar a pasta __pycache__/.
