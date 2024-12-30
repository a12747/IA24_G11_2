# TP-IA_17694-12747

# Planeamento de Tarefas

Este projeto foi desenvolvido para resolver problemas de planeamento de tarefas utilizando diferentes abordagens, incluindo o algoritmo A*. O objetivo principal é respeitar as restrições de precedência e recursos, minimizando o makespan (tempo total de execução).

---

## **Objetivo**

O projeto inclui:
- Processar datasets que descrevem tarefas, precedências, duração e restrições de recursos.
- Planear a execução das tarefas com diferentes abordagens:
  - Heurísticas simples.
  - Caminho crítico.
  - Algoritmo A*.
- Visualizar cronogramas e analisar os resultados.

---

## **Estrutura do Projeto**

- `notebooks/`
  - `TP-IA.ipynb` — Notebook principal com o código e análises
- `datasets/` — Conjunto de arquivos de entrada
  - `p01_dataset_8.txt`
  - `p01_dataset_10.txt`
  - `p01_dataset_30.txt`
- `docker-compose.yml` — Configuração para execução em Docker Compose
- `Dockerfile` — Configuração do ambiente Docker
- `README.md` — Instruções e documentação do projeto
- `requirements.txt` — Dependências do Python

---

## **Como Configurar e Executar**

### **Pré-requisitos**

- Docker e Docker Compose instalados no sistema.

### **Instruções de Execução**

1. **Clone o Repositório**
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd <PASTA_DO_REPOSITORIO>
   ```
   
2. **Inicie o Ambiente Docker Execute o seguinte comando na raiz do repositório**
   ```bash
   docker-compose up
   ```
   
3. **Aceda ao Notebook**
   ```ruby
   http://127.0.0.1:8888/
   ```
   
4. **Encerrar o ambiente quando terminar**
   ```bash
   docker-compose down
   ```

---

## Funcionalidades

1. **Processamento de Dados**
   - Leitura de datasets que descrevem:
     - Tarefas, precedências, duração e consumo de recursos.
     - Disponibilidade de recursos ao longo do tempo.

2. **Planeamento**
   - Geração de cronogramas utilizando:
     - Heurísticas simples.
     - Caminho crítico.
     - Algoritmo A* com verificação de restrições e uso eficiente de recursos.

3. **Visualização**
   - Criação de gráficos de Gantt para visualizar cronogramas.
   - Análise da utilização de recursos ao longo do tempo.

---

## Resultados

### Dataset `p01_dataset_8.txt`
- **Makespan**: 20 unidades de tempo.
- **Cronograma (Gráfico de Gantt)**:
  - *(Inserir gráfico gerado pelo notebook)*
- **Utilização de Recursos**:
  - *(Inserir gráfico gerado pelo notebook)*

### Dataset `p01_dataset_30.txt`
- **Makespan**: 45 unidades de tempo.
- **Cronograma (Gráfico de Gantt)**:
  - *(Inserir gráfico gerado pelo notebook)*
- **Utilização de Recursos**:
  - *(Inserir gráfico gerado pelo notebook)*

---

## Licença

Este projeto está licenciado sob a **Licença MIT**.
