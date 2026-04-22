# mcp-curso Udemy

Este projeto foi desenvolvido com base nos ensinamentos do curso "MCP na Prática: Crie Agentes LLM Conectados e Inteligentes" da Udemy. + +Link do Curso: https://www.udemy.com/course/mcp-na-pratica-crie-agentes-llm-conectados-e-inteligente/

## Configuração do Ambiente

Siga os passos abaixo para preparar o ambiente de desenvolvimento.

### 1. Criar o Ambiente Virtual (Python 3.12)

É necessário ter o Python 3.12 instalado. Para criar o ambiente virtual, execute:

```bash
python3.12 -m venv .venv
```

Para ativar o ambiente virtual:

- **Linux/macOS:**
  ```bash
  source .venv/bin/activate
  ```
- **Windows:**
  ```bash
  .venv\Scripts\activate
  ```

### 2. Instalar Dependências do Python

Com o ambiente virtual ativo, instale os pacotes necessários:

```bash
pip install -r requirements.txt
```

### 3. Instalar Node.js

O Node.js é essencial para o ecossistema MCP. Recomendamos a instalação da versão LTS mais recente disponível em [nodejs.org](https://nodejs.org/).

### 4. Executar o Exemplo

Após configurar o ambiente, utilize os comandos abaixo para executar os exemplos:

**Servidor de Teste:**

```bash
mcp dev servers/server_test.py
```
