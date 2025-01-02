# planilha
Organização financeira
Para criar uma planilha de organização financeira, você pode usar ferramentas como Microsoft Excel, Google Sheets ou outras ferramentas de planilhas. Vou te mostrar um exemplo básico de como você pode estruturar sua planilha de organização financeira utilizando Google Sheets:

### Passos para Criar a Planilha:

1. **Abrir o Google Sheets:**
   - Acesse [Google Sheets](https://sheets.google.com) e crie uma nova planilha.

2. **Estruturar a Planilha:**
   - Nas colunas, você pode organizar suas receitas e despesas. Aqui está um exemplo de como você pode estruturar suas colunas:

### Exemplo de Estrutura de Planilha:

| Data       | Descrição           | Categoria         | Tipo      | Valor (R$) | Saldo (R$) |
|------------|---------------------|-------------------|-----------|------------|------------|
| 01/01/2025 | Salário             | Receita           | Receita   | 5000,00    | 5000,00    |
| 02/01/2025 | Aluguel             | Despesa Fixa      | Despesa   | -1500,00   | 3500,00    |
| 03/01/2025 | Supermercado        | Despesa Variável  | Despesa   | -300,00    | 3200,00    |
| 04/01/2025 | Transporte          | Despesa Variável  | Despesa   | -200,00    | 3000,00    |
| 05/01/2025 | Internet            | Despesa Fixa      | Despesa   | -100,00    | 2900,00    |
| 06/01/2025 | Venda de Produtos   | Receita Extra     | Receita   | 400,00     | 3300,00    |

### Dicas:

1. **Categorias:** Crie categorias para suas despesas e receitas para facilitar o acompanhamento. Exemplo: Despesa Fixa, Despesa Variável, Receita Fixa, Receita Extra.
2. **Tipo:** Identifique se é uma Receita ou Despesa.
3. **Saldo:** Calcule o saldo acumulado para ter uma visão clara das suas finanças.

### Fórmulas Úteis:

1. **Cálculo do Saldo:**
   - Na célula `F2`, insira o valor inicial do saldo.
   - Na célula `F3`, insira a fórmula: `=F2 + E3`
   - Arraste a fórmula para baixo para calcular o saldo automaticamente para cada linha.

2. **Total de Receitas e Despesas:**
   - Para calcular o total de receitas, use a função `SOMASE`:
     - `=SOMASE(D:D, "Receita", E:E)`
   - Para calcular o total de despesas, use a função `SOMASE`:
     - `=SOMASE(D:D, "Despesa", E:E)`

### Passo a Passo:

1. **Inserir Dados:**
   - Preencha a planilha com suas receitas e despesas diárias.

2. **Manter Atualizado:**
   - Atualize a planilha regularmente para manter o controle das suas finanças.

3. **Análise:**
   - Analise seus gastos e receitas mensalmente para identificar possíveis ajustes.

Essa é uma estrutura básica e você pode personalizar conforme suas necessidades. Manter uma planilha financeira organizada ajuda a ter um melhor controle sobre suas finanças e a tomar decisões mais informadas.
