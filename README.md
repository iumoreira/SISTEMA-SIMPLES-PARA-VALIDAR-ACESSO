# SISTEMA DE ABERTURA DE PORTA

**Projeto 03**  
**Autor:** Iury Moreira Lopes 
**Linkedin:** https://linkedIn.com/in/iury-moreira-lopes-3b06073b6
**Data:** 05/11/2026  

Este é um programa desenvolvido em linguagem C que simula um sistema de acesso a à uma instuição qualquer. Ele valida crendenciais como crachá de acesso, se está matriculado ou se possui uma autorização especial que permite a entrada sem precisar das outras duas credenciais.

## Tecnologias Utilizadas

* **Linguagem C** (Padrão C99/C11)
* **Biblioteca `<windows.h>`** (Utilizada para configurar o suporte a caracteres UTF-8 no console do Windows)

## Como Funciona o Sistema

O programa solicita três informações principais ao usuário:
1. **Se possui crachá** de acesso.
2. **Se possui matrícula** na instituição.
3. **Se possui alguma autorização especial** da diretoria, como um vistante ou autoridade que não possui um crachá e matricula. Possuir autorização especial pode ser uma "carta coringa" caso alguém não tenha o crachá ou uma matrícula).

### Parâmetro importante:
* **Trava de dígitos:** por funcionar a base da lógica booleana com 0 e 1, o programa solicita que digite 1 para sim e 0 para não. Porém, caso alguem digite um valor diferente desse dois numerais, o programa exibe uma mensagem de erro.

## Como Executar o Projeto

Para compilar e rodar este programa na sua máquina, certifique-se de ter um compilador C (como o GCC) instalado.

1. Abra o terminal na pasta do projeto.
2. Compile o código com o comando:
   ```bash
   gcc main.c -o sistema_simples
   ```
3. Execute o programa:
   * No Windows:
     ```bash
     .\sistema_simples.exe
     ```
   * No Linux/Mac (caso adapte a biblioteca Windows):
     ```bash
     ./sistema_simples
     ```


---
*Nota: Este projeto foi desenvolvido para fins educacionais e de estudo da lógica de programação estruturada e livre de inteligencia artificial.*
