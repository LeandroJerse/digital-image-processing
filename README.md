# Processamento Digital de Imagem (PDI)

Este repositório contém os trabalhos e experimentos realizados na disciplina de Processamento Digital de Imagem.

## 📁 Estrutura do Projeto

```
digital-image-processing/
│
├── lab00/                    # Laboratório 00: Fundamentos de Visualização
│   ├── basics_matlab.ipynb   # Notebook introdutório sobre matplotlib
│   └── grafico.png           # Exemplo de gráfico salvo
│
├── .gitignore                # Regras de arquivos ignorados pelo Git
└── README.md                 # Este arquivo
```

## 🔬 Laboratórios

### Lab 00: Fundamentos de Visualização com Matplotlib

**Arquivo:** `lab00/basics_matlab.ipynb`

Este notebook apresenta os conceitos básicos de visualização usando `matplotlib` em Python, simulando operações comuns do MATLAB.

#### Conteúdo abordado:

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

## 🛠️ Tecnologias Utilizadas

- **Python 3.12**
- **NumPy**: Manipulação de arrays e operações matemáticas
- **Matplotlib**: Visualização de dados e gráficos
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
pip install numpy matplotlib jupyter
```

4. Execute os notebooks:
```bash
jupyter notebook
```

## 📝 Notas

- Este projeto utiliza Jupyter Notebooks para facilitar a experimentação
- Os gráficos gerados são salvos na mesma pasta dos notebooks
- O venv e arquivos temporários são ignorados pelo Git (consulte `.gitignore`)

## 📚 Próximas Atualizações

- Lab 01: [A ser adicionado]
- Lab 02: [A ser adicionado]
- ...

---

**Disciplina:** Processamento Digital de Imagem  
**Instituição:** Universidade Federal de Uberlândia (UFU)  
**Semestre:** 2025.2
