# Projeto Peneira Bragantino — PWA

## O que foi adicionado
O painel agora possui notificações inteligentes que verificam:
- treino do dia;
- academia;
- estudos/recuperação;
- falta de progresso depois das 17h;
- conclusão do checklist;
- contagem regressiva dos últimos 7 dias;
- “AMANHÃ É A PENEIRA!” em 19/10;
- “É HOJE!” em 20/10.

Cada aviso possui controle diário para evitar spam.

## iPhone
1. Publique em HTTPS.
2. Abra no Safari.
3. Compartilhar → Adicionar à Tela de Início.
4. Abra o app pela Tela de Início.
5. Ative notificações.

## Limitação importante
Um PWA local/estático não consegue garantir notificações agendadas quando o app está totalmente fechado apenas com JavaScript.
Para notificações realmente automáticas em horários definidos mesmo com o app fechado, é necessário Web Push + um backend/serviço de push.

O Service Worker já está preparado para receber Web Push.
