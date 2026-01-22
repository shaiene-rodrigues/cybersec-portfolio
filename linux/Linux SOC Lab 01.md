# Linux SOC Lab 01 - Comandos básicos e simulação de logs
Data: 22/01/2026
Objetivo: Praticar comandos básicos do Linux e iniciar simulações de análise de logs voltados para SOC / Blue Team.
---
## O que foi praticado
Durante este laborátorio, utilizei o terminal Ubuntu para simular um ambiente inicial de analista de segurança, focando em navegação no sistema e manipulação de arquivos de log.
---
## Comandos utilizados
```bash
pwd
ls
ls -1
cd
touch alerta.log
cat alerta.log
tail alerta.log
tail -f alerta.log
echo "Falha de login detectada - user=admin" >> alerta.log
grep "Falha" alerta.log
grep "Login bem" alerta.log
wc -l alerta.log
