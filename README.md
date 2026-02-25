# 💸 App Controle de Finanças da Isabela - Vibe Coding

### PRD final no Copilot:

```txt
# Contexto  
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.  

# Problema  
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.  

# Público-Alvo  
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.  

# Funcionalidades-Chave  
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Registrar entradas de dinheiro (salário, bônus, presentes, etc.).  
4. Mostrar a cada interação se o usuário está no verde (saldo positivo) ou no vermelho (saldo negativo).  
5. Definir e acompanhar metas financeiras.  
6. Receber dicas de economia do “Agente Financeiro”.  
7. Visualizar relatórios simples e personalizados.  
8. Acompanhar investimentos em renda fixa (atualização manual com notificação):  
   - O usuário informa a data e o valor da aplicação.  
   - Todo primeiro dia útil do mês seguinte, o app envia uma notificação ou mensagem pedindo que o usuário atualize o saldo.  
   - O usuário responde via chat com o valor atualizado, e o app registra a evolução.  
   - O app mostra a evolução mês a mês dessas aplicações, permitindo visualizar crescimento e rendimento acumulado.  
9. No fechamento de cada mês, informar se o usuário conseguiu poupar (saldo positivo após entradas e saídas).  

# Entregável da IA  
Gerar um plano de MVP com:  
- As principais telas do aplicativo.  
- Recursos necessários para implementar cada funcionalidade.  
- Um esboço de validação inicial com usuários reais.  
- Tom educativo e linguagem acessível, em português.  
```

## Interações com a Lovable e prints do resultado "final";  

> criar um aplicativo para controle de finanças conforme o PRD (product requirement document) abaixo: {PRD}

> separar os investimentos em uma aba, fazendo o controle por data de aplicação, saldo inicial aplicado, e aí criar uma coluna para cada mês com o saldo atualizado

<img width="1310" height="601" alt="image" src="https://github.com/user-attachments/assets/dbeeb447-05b4-48e7-bac2-df9c9c3029a4" />

<img width="1310" height="451" alt="image" src="https://github.com/user-attachments/assets/bd77c618-bbb1-4d45-b0c1-0935e2febf81" />


## Funcionalidades do aplicativo;

### 1. Registro de Transações
- **Gastos**: informados via chat em linguagem natural.
- **Entradas**: salários, bônus, presentes em dinheiro.
- **Classificação automática** das transações por categoria.

### 2. Controle de Saldo
- Mostra em tempo real se o usuário está:
  - **No verde** (saldo positivo).
  - **No vermelho** (saldo negativo).

### 3. Metas e Economia
- Definição de **metas financeiras**.
- No fechamento de cada mês:
  - Informa se o usuário conseguiu **poupar**.
  - Apresenta saldo final consolidado.

### 4. Investimentos
- Registro de aplicações em renda fixa ou variável.
- **Atualização manual com notificação**:
  - Usuário informa data e valor inicial da aplicação.
  - No primeiro dia útil de cada mês, o app envia uma notificação pedindo atualização do saldo.
  - Usuário responde via chat e o sistema registra a evolução.
- Exibição da **evolução mês a mês** e rendimento acumulado.

### 5. Relatórios e Dashboards
- Painel com:
  - Saldo atual.
  - Receitas, despesas e economia.
- Gráficos:
  - Evolução dos últimos meses.
  - Distribuição de gastos por categoria.
- Tabelas de investimentos:
  - Valores iniciais.
  - Evolução mensal.
  - Percentual de rendimento.


## Reflexão sobre o processo:

### O que funcionou bem?
A base do PRD disponibilizada pela DIO é muito boa e traz a ideia geral de como o documento tem que ser estruturado. experiência simples e acessível.  

### O que não funcionou como o esperado?
Surgiram necessidades ao longo da construção que não foram possíveis de serem sanadas nesse primeiro momento devido à limitação de interações (por exemplo, gostaria de ter incluído a possibilidade de se excluir/editar as entradas e saídas).

### O que aprendeu sobre conversar com IAs?
Os prompts/PRDs precisam do máximo de detalhes possíveis, o óbvio precisa ser dito. 


