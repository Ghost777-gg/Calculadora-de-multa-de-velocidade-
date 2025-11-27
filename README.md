# 🚓 Calculadora de Multas por Excesso de Velocidade (C++)

## 📝 Descrição do Projeto

Este projeto é uma ferramenta de linha de comando (CLI) desenvolvida em **C++** para simular as penalidades de multas por excesso de velocidade no Brasil. O sistema utiliza as regras percentuais e os valores estabelecidos no **Código de Trânsito Brasileiro (CTB)** para classificar a infração e calcular a penalidade exata.

O usuário insere o limite de velocidade da via e a velocidade registrada, e o programa fornece o resultado completo.

### ✨ Funcionalidades

* Cálculo da penalidade com base nas faixas de percentual excedido (até 20%, 20% a 50%, acima de 50%).
* Determinação do tipo de infração (Média, Grave ou Gravíssima).
* Aplicação do fator multiplicador de 3x para infração gravíssima.
* Retorno do valor da multa e dos pontos na CNH.

## 🛠️ Tecnologias Utilizadas

* **Linguagem Base:** C++ (Compilado para alta performance)
* **Padrão:** C++11 ou superior
* **Ambiente:** Linha de Comando (CLI)

## ⚙️ Como Compilar e Executar

Para rodar este projeto, você precisará de um compilador C++ (como o `g++` no Linux/macOS ou MinGW no Windows).

1.  **Clone o Repositório:**
    ```bash
    git clone https://github.com/Ghost777-gg/Calculadora-de-multa-de-velocidade-.git
    
    cd Calculadora-de-multa-de-velocidade
    ```

2.  **Compile o Código Fonte:**
    Se o seu arquivo principal se chama `main.cpp`:
    ```bash
    g++ main.cpp -o calculadora_multa
    ```

3.  **Execute o Programa:**
    O programa pedirá os dados da infração:
    ```bash
    ./calculadora_multa
    ```

## 📊 Regras de Penalidade (Referência CTB)

O cálculo é baseado no percentual de excesso de velocidade:

| Excesso (Acima do Limite) | Infração | Pontos | Valor Base (2025) | Penalidade Adicional |
| :---: | :---: | :---: | :---: | :---: |
| **Até 20%** | Média | 4 | R$ 130,16 | - |
| **20% a 50%** | Grave | 5 | R$ 195,23 | - |
| **Acima de 50%** | Gravíssima (3x) | 7 | **R$ 880,41** | Suspensão da CNH |

## 🤝 Contribuições

Contribuições são sempre bem-vindas! Se você encontrar um bug ou tiver sugestões de melhoria (ex: inclusão da tolerância do radar), sinta-se à vontade para abrir uma *Issue* ou enviar um *Pull Request*.

