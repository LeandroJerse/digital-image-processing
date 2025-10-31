# Processamento Digital de Imagem (PDI)

Este repositório contém os trabalhos e experimentos realizados na disciplina de Processamento Digital de Imagem.

## 📁 Estrutura do Projeto

```
digital-image-processing/
│
├── lab00/                    # Laboratório 00: Fundamentos
│   ├── basics_matlab.ipynb   # Notebook introdutório sobre matplotlib
│   ├── basics_numpy.ipynb    # Notebook sobre manipulação de matrizes NumPy
│   ├── basics_opencv.ipynb   # Notebook sobre processamento de imagens OpenCV
│   ├── foz.jpg               # Imagem de exemplo para testes
│   └── grafico.png           # Exemplo de gráfico salvo
│
├── .gitignore                # Regras de arquivos ignorados pelo Git
└── README.md                 # Este arquivo
```

## 🔬 Laboratórios

### Lab 00: Fundamentos

Este laboratório contém três notebooks introdutórios que cobrem os fundamentos necessários para trabalhar com processamento digital de imagens.

#### `basics_matlab.ipynb` - Fundamentos de Visualização com Matplotlib

Este notebook apresenta os conceitos básicos de visualização usando `matplotlib` em Python, simulando operações comuns do MATLAB.

**Conteúdo abordado:**

1. **Gráfico Simples Exponencial**
   - Criação de gráficos com pontos azuis
   - Uso de `plt.plot()` para funções exponenciais
   - Adição de títulos e textos personalizados

2. **Múltiplas Funções no Mesmo Gráfico**
   - Plotagem de funções exponenciais, logarítmicas e trigonométricas
   - Uso de `plt.legend()` para identificação das curvas
   - Customização de cores e estilos de linha

3. **Subplots**
   - Criação de múltiplos gráficos em uma única figura
   - Demonstração das funções seno, cosseno e tangente
   - Uso de `plt.subplot()` para organizar visualizações

4. **Salvamento de Gráficos**
   - Exportação de gráficos em formato PNG
   - Configuração de limites de eixos com `plt.axis()`
   - Customização de labels dos eixos

5. **Gráfico de Barras**
   - Representação de dados categóricos
   - Exemplo com população de estados do Sudeste
   - Customização de cores e labels

6. **Histogramas**
   - Geração de distribuições usando `np.random.randn()`
   - Criação de histogramas de probabilidade
   - Adição de grade para melhor visualização

#### `basics_numpy.ipynb` - Manipulação de Matrizes NumPy

Este notebook aborda operações fundamentais com matrizes usando NumPy, essenciais para processamento de imagens.

**Conteúdo abordado:**

1. **Criação e Acesso a Matrizes**
   - Criação de matrizes usando `np.matrix()`
   - Acesso a elementos, linhas e colunas
   - Indexação e fatiamento (slicing) de matrizes

2. **Operações com Matrizes**
   - Criação de matrizes zeros com `np.zeros()`
   - Geração de números aleatórios com `np.random.randint()`
   - Criação de matriz identidade com `np.eye()`

3. **Referências e Cópias**
   - Diferença entre atribuição por referência e cópia
   - Uso de `np.matrix()` para criar cópias independentes
   - Atribuição em blocos de matrizes

4. **Operações Aritméticas**
   - Adição e multiplicação de matrizes
   - Potenciação de matrizes
   - Cálculo de matriz inversa
   - Transposição com `np.transpose()`
   - Cálculo do traço com `np.trace()`

5. **Concatenação**
   - Concatenação horizontal com `np.hstack()`
   - Concatenação vertical com `np.vstack()`

6. **Funções Matemáticas**
   - Aplicação de funções matemáticas (ex: `np.sqrt()`)

#### `basics_opencv.ipynb` - Processamento de Imagens com OpenCV

Este notebook introduz o uso do OpenCV para leitura, conversão e visualização de imagens.

**Conteúdo abordado:**

1. **Leitura de Imagens**
   - Leitura de imagens com `cv2.imread()`
   - Diferentes modos de leitura (`cv2.IMREAD_COLOR`)

2. **Conversão de Espaços de Cores**
   - **Importante:** OpenCV lê imagens no formato BGR (Blue-Green-Red)
   - Conversão de BGR para RGB com `cv2.cvtColor()`
   - Visualização correta de imagens com matplotlib

3. **Visualização Comparativa**
   - Comparação lado a lado de imagens BGR e RGB
   - Uso de subplots para exibir múltiplas versões

4. **Salvamento de Imagens**
   - Uso de `cv2.imwrite()` para salvar imagens processadas

## 🛠️ Tecnologias Utilizadas

- **Python 3.12**
- **NumPy** (2.2.6): Manipulação de arrays e operações matemáticas com matrizes
- **Matplotlib**: Visualização de dados e gráficos
- **OpenCV** (4.12.0.88): Processamento de imagens e visão computacional
- **Jupyter Notebook**: Ambiente de desenvolvimento interativo

## 🚀 Como Usar

1. Clone este repositório:
```bash
git clone <url-do-repositorio>
```

2. Crie e ative um ambiente virtual:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# ou
venv\Scripts\activate  # Windows
```

3. Instale as dependências:
```bash
pip install numpy matplotlib opencv-python jupyter
```

4. Execute os notebooks:
```bash
jupyter notebook
```

## 📝 Notas

- Este projeto utiliza Jupyter Notebooks para facilitar a experimentação
- Os gráficos gerados são salvos na mesma pasta dos notebooks
- O venv e arquivos temporários são ignorados pelo Git (consulte `.gitignore`)
- **Importante:** OpenCV lê imagens no formato BGR, não RGB. Sempre converta com `cv2.cvtColor(img, cv2.COLOR_BGR2RGB)` antes de visualizar com matplotlib
- O notebook `basics_opencv.ipynb` requer uma imagem de exemplo (como `foz.jpg`) para funcionar corretamente

## 📚 Próximas Atualizações

- Lab 01: [A ser adicionado]
- Lab 02: [A ser adicionado]
- ...

---

**Disciplina:** Processamento Digital de Imagem  
**Instituição:** Universidade Federal de Uberlândia (UFU)  
**Semestre:** 2025.2
