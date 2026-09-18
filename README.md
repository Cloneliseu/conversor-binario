# CTC_CONVERSOR BINARIO— Assembly ClonerTech_Conversor

> Ferramenta interativa para conversão binário/decimal e simulação de instruções Assembly x86 (MOV, ADD, SUB, MUL, DIV).

![HTML](https://img.shields.io/badge/HTML-5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

# Sobre o Projeto

CTC_CONVERSOR BINARIO foi desenvolvido como projeto académico no âmbito da cadeira de Arquitectura de Computadores / Assembly no INSTIC — Instituto Superior de Tecnologias de Informação e Comunicação(https://instic.ao), Angola.

O objetivo é simular visualmente o comportamento de instruções Assembly x86, facilitando a compreensão de:

- Representação de dados em binário e decimal
- Funcionamento dos registadores (AX, BX)
- Operações aritméticas ao nível dos bits

# Funcionalidades

| Módulo | Instruções simuladas | Descrição |
|--------|---------------------|-----------|
| Conversor | `MOV` | Converte binário ↔ decimal / decimal ↔ binario|
| Aritmética | `ADD`, `SUB`, `MUL`, `DIV`| Soma, subtracção, multiplicação e divisão de binários|
| Log | — | Histórico de todas as instruções executadas na sessão |

# Como Usar

## Online (recomendado)
Acede directamente via GitHub Pages:

https://Cloneliseu.github.io/conversor-binario/

## Clonar o repositório
git clone https://github.com/Cloneliseu/conversor-binario.git

# Abrir no browser
cd asm-tool
open index.html   # macOS
xdg-open index.html   # Linux
start index.html  # Windows

Não requer servidor, frameworks, nem instalação. *100% HTML/CSS/JS puro.*

# Demonstração

## Conversão Binária
```
Entrada: 1011
→ MOV AX, 11
→ 11 decimal
```

### Operação ADD
```
A = 1011  (11d)
B = 0110  (6d)
→ MOV AX, 11
→ ADD AX, 6
→ Resultado = 10001 binario (17 em decimal)
```

# Estrutura do Projecto

```
ctc-conversor binario/
│
├── index.html      # Aplicação completa (single file)
└── README.md       # Documentação
```

# Contexto Académico

- **Instituição:** INSTIC — Instituto Superior de Tecnologias de Informação e Comunicação
- **Curso:** Informática de Gestão
- **Cadeira:** Arquitectura de Computadores
- **País:** Angola

# Licença

Este projecto está licenciado sob a [MIT License](LICENSE) — podes usar, modificar e distribuir livremente com atribuição.

*Desenvolvido por Francisco R. Elias (https://github.com/ClonerTech) · INSTIC · Angola*
