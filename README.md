# Exercícios em RISC-V Assembly

Este repositório contém uma coleção de códigos desenvolvidos em **Assembly RISC-V** como parte de estudos e exercícios práticos.  
O objetivo é praticar conceitos fundamentais de arquitetura de computadores, organização de sistemas e programação de baixo nível.

---

## Requisitos

Para rodar os códigos, é necessário ter instalado:

- [RARS](https://github.com/TheThirdOne/rars).
- Alternativamente, ferramentas como `riscv64-unknown-elf-gcc` e `qemu-riscv64` podem ser usadas para compilação e execução em terminal.

---

## Como Executar

### Usando o RARS
1. Abra o RARS.  
2. Carregue o arquivo `.riscv` desejado.  
3. Monte e execute (`Assemble` → `Run`).  

### Usando GCC + QEMU
```bash
# Compila
riscv64-unknown-elf-gcc -o programa programa.s

# Executa
qemu-riscv64 ./programa
