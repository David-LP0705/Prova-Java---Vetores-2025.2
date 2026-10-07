📝 Prova de Java — Vetores e Algoritmos (2025.2)

Repositório dedicado à resolução da 1ª Prova de 2025.2 de Java, com foco em manipulação de vetores: união sem repetidos, ordenação com insertion sort, remoção de repetições e rotação in-place.

A prova foi resolvida primeiro no papel, depois no computador, e a versão do papel foi corrigida a partir da resolução do computador.

📂 Programas Desenvolvidos

O arquivo Prova.java reúne as funções pedidas e suas auxiliares:

uniao — Gera o vetor união de A e B, sem elementos repetidos, e retorna o tamanho de U.
ordenar — Ordena o vetor utilizando o algoritmo insertion sort.
gerarVetorSemRepeticao — Copia os elementos de V para VSR na mesma ordem, sem repetição, e retorna o tamanho de VSR.
rotacionar — Rotaciona o vetor in-place para a esquerda em k posições (k negativo rotaciona para a direita).
contem (auxiliar) — Verifica se um valor já existe nas primeiras posições de um vetor.
inverter (auxiliar) — Inverte um trecho do vetor, usada na rotação pelo método das três inversões.
📄 Arquivos
Prova.java — Solução completa em Java.
prova_corrigida.pdf — Fotos da prova no papel, com correção em vermelho, pontuação final e tempos.
⏱️ Resultado da Atividade
Tempo no papel: 54:57 min
Tempo no computador: 32:19 min
Nota final: 3,25 / 5,0

Problemas encontrados na resolução do papel:

uniao: o segundo laço não usava contem, então os repetidos de B entravam na união.
gerarVetorSemRepeticao: a função retornava tamV em vez de tamVSR.
rotacionar: não havia tratamento para k negativo.
