# Projeto Joker

Bem-vindo ao projeto **Joker**, uma ferramenta para conversão de código entre várias linguagens e aplicação da fórmula SEA Learning Multi Scalae.

## Tabela de Conversão de Qubits para Bits

A tabela a seguir é usada para mapear a conversão de qubits para bits no contexto da fórmula SEA Learning Multi Scalae:

| Qubits | Bits | Porcentagem de Quebra |
|--------|------|-----------------------|
| 1      | 1    | 100%                  |
| 2      | 4    | 75%                   |
| 3      | 8    | 50%                   |
| 4      | 16   | 25%                   |
| 5      | 32   | 12.5%                 |
| 6      | 64   | 6.25%                 |
| 7      | 128  | 3.125%                |

### Explicação da Tabela

- **Qubits**: Quantidade de qubits utilizados.
- **Bits**: Quantidade de bits resultantes da conversão.
- **Porcentagem de Quebra**: Percentual que representa a perda de eficiência na conversão de qubits para bits.

## Como Funciona a Conversão de Código

A conversão de código utiliza a fórmula SEA Learning Multi Scalae e é realizada com base na tabela de conversão de qubits para bits. Aqui estão os passos principais:

1. **Seleção da Linguagem**: O usuário seleciona a linguagem do código a ser convertido (Solidity, JavaScript, Python ou Ruby).

2. **Conversão para Lua**: O código é convertido para Lua utilizando regras específicas para cada linguagem.

3. **Processamento SEA Learning**: O código convertido é então processado usando a fórmula SEA Learning Multi Scalae. Esse processamento pode incluir adição de comentários ou modificações baseadas na lógica SEA Learning.

## Estrutura do Código

O projeto inclui:

- **`index.html`**: Arquivo HTML que contém a interface do usuário para a conversão de código.
- **`styles.css`**: Arquivo CSS para estilização da interface.
- **`scripts.js`**: Arquivo JavaScript que contém a lógica para conversão e processamento do código.

### Exemplos de Conversão

#### Código Solidity

Entrada:
```solidity
pragma solidity ^0.8.0;

contract MyContract {
    uint public myNumber;
    
    function setNumber(uint _number) public {
        myNumber = _number;
    }
}
