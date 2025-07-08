# BAT Tracker 📉

Notebook em Python para monitorar o preço do token BAT (Basic Attention Token) e enviar alertas via Telegram.

## 🔧 Funcionalidades

- Consulta o preço atual do BAT em BRL usando a API do CoinGecko
- Mostra gráfico da variação dos últimos 30 dias
- Calcula o valor estimado do saldo do usuário
- Envia alertas automáticos via Telegram se o preço ultrapassar limites definidos

## 📦 Bibliotecas utilizadas

- `requests`
- `pandas`
- `matplotlib`

## ▶️ Como usar

1. Abra e execute o notebook `bat_tracker.ipynb`
2. No início do notebook, configure seu token e chat_id do Telegram
3. O notebook enviará alertas automáticos quando os limites forem atingidos

---

MIT License
