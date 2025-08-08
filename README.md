# Dashboard de Análise Salarial

Este projeto apresenta um dashboard interativo para análise de dados salariais utilizando Python, Streamlit e Plotly.

## Passo a Passo para Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/joaoPraiaJunior/salarios_dados.git
cd salarios_dados/dashboard
```

### 2. Crie e ative um ambiente virtual (recomendado)

No Windows (PowerShell):
```powershell
python -m venv .venv
.venv\Scripts\Activate
```

No Linux/MacOS:
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4. Execute o dashboard

```bash
streamlit run app.py
```

O dashboard estará disponível no navegador, normalmente em `http://localhost:8501`.

---

**Observações:**
- Certifique-se de ter o Python 3.8 ou superior instalado.
- Os arquivos de dados (`salarios_estudo_final.csv`, etc.) devem estar no diretório correto para o funcionamento do dashboard.
- Para sair do ambiente virtual, use `deactivate`.

---

Dúvidas ou sugestões? Abra uma issue no repositório ou entre em contato!
