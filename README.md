# BAT Tracker 📉

Notebook em Python para monitorar o preço do token BAT (Basic Attention Token) e enviar alertas via Telegram.

## 🔧 Funcionalidades

- Consulta o preço atual do BAT em BRL usando a API do CoinGecko
- Calcula o valor do saldo do usuário em reais
- Mostra gráfico da variação de preço nos últimos 30 dias
- Envia alertas automáticos via bot do Telegram quando o preço ultrapassa limites definidos

## 📦 Bibliotecas utilizadas

- `requests`
- `pandas`
- `matplotlib`

## ▶️ Como usar

1. Configure o arquivo `telegram_alert.py` com seu token e chat_id
2. Execute o notebook `bat_tracker.ipynb`
3. O alerta será enviado ao Telegram se o preço do BAT ultrapassar os limites definidos

---

MIT License
