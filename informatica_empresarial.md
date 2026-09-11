# 🚀 Missão Prática: Informática Empresarial 


**Curso:** Técnico em Administração

**Disciplina:** Informática Empresarial 



---

## 🎯 A Missão: "Operação Resgate Financeiro" 

> **Cenário:** O dono da *Distribuidora Paranaense* recebeu uma lista com vendas do mês, mas **não sabe se está ganhando ou perdendo dinheiro**. Ele precisa de uma resposta  antes de uma reunião de emergência.  
> **Sua Equipe:** Foi contratada como Consultoria de Elite em Gestão para resolver o problema usando o Google Sheets/Excel!

---

## 📋 Tabela Bruta (Para Copiar e Colar na Célula A1 da Planilha)

> **Instruções para o Aluno:** Copie todo o bloco de dados abaixo ou da planilha em anexo e cole na célula **A1** do Google Sheets.

```text
Codigo	Produto	Categoria	Qtd Vendida	Preco Venda (R$)	Custo Unitario (R$)
101	Suco de Laranja 1L	Bebidas	120	8,50	5,20
102	Biscoito Recheado 140g	Alimentos	250	3,20	3,80
103	Cafe Torrado 500g	Matinais	80	18,90	12,50
104	Agua Mineral 500ml	Bebidas	400	2,50	1,10
105	Detergente Liquido 500ml	Limpeza	180	4,20	2,80
106	Papel Toalha c/2	Limpeza	95	6,50	4,10
107	Chocolate em Barra 90g	Alimentos	150	5,50	3,90
108	Leite Integral 1L	Matinais	310	4,80	3,90
```

---

## 💡 Colinha Rápida (Cheat Sheet - Fórmulas Prontas)

Para não perder tempo procurando no teclado, use este guia visual:

| O que você quer calcular? | Coluna de Destino | Como digitar na célula (Fórmula) | O que ela faz na prática? |
| :--- | :---: | :--- | :--- |
| **Faturamento** | **G2** | `=D2*E2` | Multiplica Qtd Vendida (D2) pelo Preço de Venda (E2) |
| **Custo Total** | **H2** | `=D2*F2` | Multiplica Qtd Vendida (D2) pelo Custo Unitário (F2) |
| **Resultado (Lucro/Prejuízo)** | **I2** | `=G2-H2` | Subtrai o Custo Total (H2) do Faturamento (G2) |
| **Alerta Automático (SE)** | **J2** | `=SE(I2<0; "🚨 PREJUÍZO"; "✅ LUCRO")` | Escreve "PREJUÍZO" se o resultado for menor que zero |

---

```

---

## 🛠️ Passo a Passo Prático para a Equipe

### 🟢 Nível 1: Mestre das Fórmulas 

1. Abra uma nova planilha no Google Sheets (`sheets.new`).
2. Cole a **Tabela Bruta** a partir da célula **A1**.
3. Na célula **G1**, escreva o cabeçalho `Faturamento`. Na célula **G2**, digite `=D2*E2` e aperte **ENTER**.
4. Clique no quadradinho no canto inferior direito da célula **G2** e **arraste para baixo até a linha 9** para calcular tudo automaticamente!
5. Na célula **H1**, escreva `Custo Total`. Na célula **H2**, digite `=D2*F2` e arraste para baixo.
6. Na célula **I1**, escreva `Resultado (R$)`. Na célula **I2**, digite `=G2-H2` e arraste para baixo.
7. Na célula **J1**, escreva `Status`. Na célula **J2**, cole: `=SE(I2<0; "🚨 PREJUÍZO"; "✅ LUCRO")` e arraste para baixo.

### 🟡 Nível 2: Detetive dos Dados

1. Olhe para a coluna **J (Status)**. 
2. Localize qual linha ficou com a marcação **🚨 PREJUÍZO**.
3. Responda em 1 frase no campo abaixo da tabela:
   * **Produto Vilão:** *Biscoito Recheado 140g*
   * **Prejuízo do Mês:** *R$ 150,00 de prejuízo acumulado!*
   * **Recomendação Gerencial:** *Subir o preço para pelo menos R$ 4,50 ou negociar custo menor com o fornecedor.*

### 🔴 Nível 3: Consultor Executivo 

1. Selecione a coluna de **Produtos (Coluna B)** e a coluna de **Resultado (Coluna I)**.
2. Clique no menu superior: **Inserir $\rightarrow$ Gráfico**.
3. Escolha o gráfico de **Colunas ou Barras**.
4. Pronto! O dashboard está pronto para a reunião de diretoria!
