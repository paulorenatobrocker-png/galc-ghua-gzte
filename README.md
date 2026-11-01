# GALC-GHUA-GZTE BOT

Estrutura:
- GALC-GHUA-GZTE/bot_galc.py -> codigo com tabela GHUA 288 entradas
- Dockerfile -> aponta para GALC-GHUA-GZTE/bot_galc.py
- requirements.txt
- fly.toml -> app = galc-ghua-gzte-bot

Como subir:
1. Cria repo novo no GitHub: galc-ghua-gzte
2. Sobe esses arquivos
3. No Fly.io: Create app -> galc-ghua-gzte-bot -> Connect GitHub repo
4. Em Secrets: TOKEN = token novo do @galc_ghua_gzte_bot
5. Deploy
