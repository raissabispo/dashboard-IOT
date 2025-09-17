# 📊 Dashboard IoT - Monitoramento de Umidade e Temperatura

Este projeto cria um **dashboard interativo** para monitoramento de ambiente usando dados de sensores IoT. Ele permite visualizar gráficos de **Umidade (%)** e **Temperatura (°C)**, separados ou juntos, com indicadores de **últimas leituras**.

---

## 🌟 Funcionalidades

- ✅ Dashboard interativo com **Plotly**
  - Gráficos de linhas suaves (`spline`) para Umidade e Temperatura.
  - Hover customizado mostrando valor e horário.
  - Botões para alternar entre:
    - Ambos os gráficos (Umidade + Temperatura)
    - Apenas Umidade
    - Apenas Temperatura
- ✅ **Últimas leituras** destacadas diretamente no gráfico.
- ✅ **Relatório resumido** com média, mínimo, máximo e última leitura.
- ✅ Visual **clean e moderno**, cores originais mantidas:
  - 🔵 Azul → Umidade  
  - 🔴 Vermelho → Temperatura

---

## ⚙️ Tecnologias utilizadas

- **Python 3.x**  
- Bibliotecas:
  - `pandas` → manipulação de dados
  - `requests` → requisição HTTP para obter os dados da API
  - `plotly` → visualização interativa (dashboard)

---

## 🛠️ Como usar

1. **Instalar dependências**:

```bash
pip install pandas plotly requests
