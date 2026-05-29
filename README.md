# 🧮 Operações Matriciais (Java & Python)

Este repositório reúne uma coleção de algoritmos matemáticos voltados para a manipulação, cálculo e escalonamento de matrizes de dimensões genéricas \(N \times M\). O projeto foi inicialmente desenvolvido durante a disciplina de **Geometria Analítica e Álgebra Linear (GAAL)** e estendido como um projeto pessoal com o intuito de praticar conceitos de programação e revisitar conhecimentos em múltiplas linguagens.

O repositório é híbrido e demonstra a aplicação da mesma base lógica em ambientes de execução distintos: **Java** e **Python**.

---

## 📁 Estrutura do Repositório

O projeto é dividido em módulos independentes baseados na linguagem e na operação realizada:

### ☕ 1. Módulo Java (`GausJordanGAAL/`)
Focado na resolução de sistemas e transformações lineares utilizando Programação Orientada a Objetos (POO).
*   📂 `src/`: Contém o código-fonte principal.
    *   📄 `Matriz.java`: Classe que encapsula a estrutura de dados bidimensional e implementa as operações elementares nas linhas (troca de linhas, multiplicação por escalar e combinação linear).
    *   📄 `App.java`: Ponto de entrada (`main`) que gerencia a interface via console, captura os dados de entrada e dispara as resoluções.

### 🐍 2. Módulo Python (`Soma2Matriz-Python/`)
Focado em scripts diretos e manipulação estruturada de matrizes.
*   📄 `introducao.py`: Script principal responsável pela lógica de manipulação algébrica e soma de matrizes.
*   📄 `inserts.txt`: Arquivo auxiliar contendo casos de teste, estruturas de matrizes e dados de entrada pré-configurados para validação rápida do algoritmo.

---

## 📌 Recursos Implementados

*   **Escalonamento por Gauss-Jordan (Java):** Algoritmo completo que reduz uma matriz \(N \times M\) à sua forma escalonada reduzida por linhas, permitindo a inversão de matrizes e resolução de sistemas lineares associados.
*   **Operações Elementares (Java):** Implementação manual de pivoteamento parcial para evitar divisões por zero durante o escalonamento.
*   **Soma Algébrica (Python):** Algoritmo estruturado para validação e adição de matrizes compatíveis.

---

## 🚀 Como Executar os Módulos

### Pré-requisitos
*   **Java Development Kit (JDK)** 11 ou superior instalado.
*   **Python 3.x** instalado.

### Executando o Módulo Java
1. Acesse o diretório do módulo:
   ```bash
   cd GausJordanGAAL
   ```
2. Compile os arquivos fontes da pasta `src`:
   ```bash
   javac src/*.java -d bin/
   ```
3. Execute a aplicação:
   ```bash
   java -cp bin App
   ```

### Executando o Módulo Python
1. Acesse o diretório do módulo:
   ```bash
   cd Soma2Matriz-Python
   ```
2. Execute o script via terminal:
   ```bash
   python introducao.py
   ```

---

## 🛠️ Tecnologias Utilizadas

*   **Java** (Lógica de matrizes baseada em POO no ecossistema clássico)
*   **Python** (Scripts rápidos e manipulação de arrays nativos)

---

## 👤 Autor

*   **Iviner Cássio** - [ivinercassio](https://github.com)
