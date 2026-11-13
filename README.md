# SMA Labirinto (SPADE)

Sistema multiagentes com tres agentes cegos (Labirinto, Pai e Filho) que
resolvem um labirinto usando busca em profundidade (DFS). O Pai explora e
otimiza o caminho antes de enviar ao Filho.

## Instalacao
pip install -r requirements.txt

## Execucao (dois terminais)
1) spade run
2) python labirinto_spade.py

Para ver as mensagens do protocolo:
VERBOSE=1 python labirinto_spade.py

## Arquivos
- labirinto_spade.py: codigo dos tres agentes
- log.txt: saida de uma execucao com as mensagens trocadas
