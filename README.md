# prova2sestemasdristribuidos

A- A configuração que modifiquei entre evidencia 1 e evidencia 2 foi a linha 19 do codigo, MAXIMO_SIMULTANEO = 2.

B- Na função sincronizar(). Em vez de pegar o valor de principal["estoque"] estava puxando o valor de Replica["estoque"].

C- A alteração foi na função consultar_estoque(). Onde ela se repetia nos 2 if de forma errada, após alteração o sistema começou a consultar após falhas.
