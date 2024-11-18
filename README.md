# 📑 Folha de Pagamento

Este é um sistema simples para gerenciar a folha de pagamento de funcionários, desenvolvido em **JavaScript (Node.js)**. A aplicação permite cadastrar funcionários, registrar horas trabalhadas e gerar relatórios com cálculos de salário bruto, descontos de INSS e salário líquido.

## 🛠️ Funcionalidades
- **Cadastro de funcionários**: Inclui informações como ID, nome, cargo e taxa horária.
- **Registro de horas trabalhadas**: Permite adicionar horas trabalhadas por funcionário.
- **Cálculo automático de salário**: Com base nas horas trabalhadas e na taxa horária.
- **Cálculo de INSS**: Aplica as alíquotas de INSS de acordo com o salário bruto.
- **Geração de relatórios**: Exibe o salário bruto, desconto de INSS e o salário líquido.

## 🗂️ Estrutura do Código
O projeto contém as seguintes funções:

- `adicionarFuncionario()`: Adiciona um novo funcionário à lista.
- `registrarHoras()`: Registra as horas trabalhadas por um funcionário específico.
- `calcularSalarioMensal()`: Calcula o salário bruto com base nas horas registradas.
- `calcularInss()`: Calcula o valor do desconto de INSS com base no salário bruto.
- `gerarRelatorioPagamento()`: Gera um relatório detalhado para cada funcionário.
- `gerenciarFolhaPagamento()`: Exibe o menu de interação e gerencia o fluxo do sistema.

## 🛠️ Pré-requisitos

Certifique-se de ter o **Node.js** instalado em sua máquina. Para verificar, utilize o comando:
```bash
node -v