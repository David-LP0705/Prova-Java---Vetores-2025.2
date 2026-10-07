# 📝 Prova de Java — Vetores e Algoritmos (2025.2)

Repositório dedicado à resolução da 1ª Prova de 2025.2 de Java, com foco em manipulação de vetores: união sem repetidos, ordenação com insertion sort, remoção de repetições e rotação *in-place*.

A prova foi resolvida primeiro no papel, depois no computador, e a versão do papel foi corrigida a partir da resolução do computador.

---

## 📁 Programas Desenvolvidos

O arquivo `Prova.java` reúne as funções pedidas e suas auxiliares:

- **uniaun** — Gera o vetor união de A e B, sem elementos repetidos, e retorna o tamanho de U.
- **ordenar** — Ordena o vetor utilizando o algoritmo *insertion sort*.
- **gerarVetorSemRepeticao** — Copia os elementos de V para VSR na mesma ordem, sem repetição, e retorna o tamanho de VSR.
- **rotacionar** — Rotaciona o vetor *in-place* para a esquerda em k posições (k negativo rotaciona para a direita).
- **contem** *(auxiliar)* — Verifica se um valor já existe nas primeiras posições de um vetor.
- **inverter** *(auxiliar)* — Inverte um trecho do vetor, usada na rotação pelo método das três inversões.

---

## 📄 Arquivos do Repositório

- **`Prova.java`** — Solução completa em Java.
- **`prova_corrigida.pdf`** — Fotos da prova no papel, com correção em vermelho, pontuação final e tempos.

---

## ⏱️ Resultado da Atividade

- **Tempo no papel:** 54:57 min
- **Tempo no computador:** 32:19 min
- **Nota final:** 3,25 / 5,0

---

## ⚠️ Problemas Encontrados na Resolução do Papel

- **`uniao`:** O segundo laço não usava `contem`, então os repetidos de B entravam na união.
- **`gerarVetorSemRepeticao`:** A função retornava `tamV` em vez de `tamVSR`.
- **`rotacionar`:** Não havia tratamento para `k` negativo.

---

## 🛠️ Tecnologias e Ferramentas

- **Java (JDK):** Linguagem de programação utilizada para implementar os algoritmos.
- **IDE (VS Code / IntelliJ / Eclipse):** Ambiente de desenvolvimento para escrita e execução dos códigos.

---

## 🚀 Como Executar o Projeto

1. Certifique-se de ter o **Java JDK** instalado no seu computador.
2. Clone este repositório executando o comando abaixo no seu terminal:

```bash
git clone https://github.com/David-LP0705/Prova-Java---Vetores-2025.2.git

```bash
git clone [https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git](https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git)
