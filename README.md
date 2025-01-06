# TP-IA_17694-12747

# Aprendizagem Automática (ML)

Este projeto faz parte de um estudo que procura explorar, analisar e modelar dados referentes a valores de casas na Califórnia, bem como aplicar técnicas de Classificação, Agrupamento (Clustering) e Regras de Associação.
---

## **Objetivo**

- Entender as principais características do dataset de habitação, como renda mediana (MedInc), idade das casas (HouseAge), número de cômodos (AveRooms), etc.
- Aplicar técnicas de ML supervisionado (Classificação) e não supervisionado (Clustering, Regras de Associação) para extrair insights.
- Desenvolver habilidades em limpeza e preparação de dados, visualização e análise exploratória.
- Documentar o processo, resultados intermediários e finais, de forma que a solução seja reprodutível e compreensível.

---

## **Estrutura do Projeto**

- `notebooks/`
  - `TP-IA.ipynb` — Notebook principal com o código e análises
- `datasets/` — Conjunto de arquivos de entrada
  - `houses.csv`
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

## Licença

Este projeto está licenciado sob a **Licença MIT**.
