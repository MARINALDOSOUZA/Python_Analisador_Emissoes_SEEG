# Pipeline e Analisador de Dados SEEG 🌍📊

**Criado por: marinaldosouza@gmail.com**

Uma ferramenta robusta de linha de comando (CLI) desenvolvida em Python para extração, processamento, cache inteligente e visualização de dados de emissões de Gases de Efeito Estufa (GEE) do Brasil, utilizando a base de dados oficial do SEEG.

## 🚀 Principais Funcionalidades

* **Download Autônomo e Anti-Bloqueio:** Identifica a ausência da base de dados local e realiza o download automático (20MB+) contornando bloqueios de servidor (Erro 403 Forbidden) via spoofing de `User-Agent`.
* **Gestão Dinâmica de Diretórios:** Detecta automaticamente o caminho nativo da Área de Trabalho (Desktop) do usuário, independente do sistema operacional (Windows/Linux/Mac), e gerencia a criação de pastas de trabalho.
* **Cache Inteligente de Alta Performance:** Transforma o arquivo Excel original (formato *wide*) em um arquivo CSV (*long format*), pré-tipando colunas como `category` e otimizando o uso de memória RAM em leituras futuras para carregamento instantâneo.
* **Interface Interativa (CLI):** Menus de navegação fluídos no terminal para consulta geral e detalhada.
* **Tabelas Dinâmicas (Pivot Tables):** Resumos cruzados inteligentes com filtragem booleana avançada, exibindo apenas dados matematicamente relevantes (ocultando matrizes zeradas).
* **Análise Visual:** Geração automática de gráficos de linha com marcações de picos, mínimas e médias históricas utilizando `matplotlib` e `seaborn`.

## 🛠️ Tecnologias Utilizadas

* **Python 3.x**
* **Pandas:** Para modelagem estrutural, filtragem vetorial e operações de *melt* e *pivot*.
* **Matplotlib & Seaborn:** Para renderização de estatísticas gráficas.
* **Pathlib & Winreg:** Para portabilidade de rotas do sistema operacional.
* **Urllib:** Para requisições web seguras.

## 📦 Como Instalar e Rodar

1. **Clone este repositório:**
   ```bash
   git clone [https://github.com/SEU-USUARIO/nome-do-repositorio.git](https://github.com/SEU-USUARIO/nome-do-repositorio.git)
   cd nome-do-repositorio
