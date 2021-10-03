# **Gerenciador de Memória projetado em linguagem de programação C.**

-Aluno: Jeanluca Martins de Abreu     |    -Matrícula: ER05960

### **Descrição:**

Esse código foi desenvolvido para a disciplina de Sistemas Operacionais - SIN 351 da Universidade federal de Viçosa - Campus Rio Paranaíba, o objetivo desse projeto é apresentar alguns dos algoritmos de substituição de páginas mais utilizados por sistemas operacionais modernos, ao final da execução de cada um destes algoritmos foi comparado o desempenho dos mesmos com uma função que gera substituição de páginas de forma aleatória. Os algoritmos propostos para a implementação são: 

* FIFO; 
* FIFO + Bit R (Segunda Chance);
* NRU;
* Aging (Envelhecimento);
* Random (já implementado)

### **Como Executar:**

Para realizar a execução do algoritmo é necessário compilar e executar o código a partir dos seguintes comandos:

* $ gcc -Wall vmm.c -o vmm (Compilação do Gerenciador de Memória).
* $ ./vmm random 10 < anomaly.dat (Execução do Gerenciador de Memória 

**Observação:** substituir ./vmm pelo caminho onde se encontra o arquivo main.c


 
