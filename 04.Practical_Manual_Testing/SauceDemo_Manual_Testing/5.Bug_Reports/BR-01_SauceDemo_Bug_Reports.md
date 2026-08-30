# 5. Bug Reports

## BUG-001 — Nome incorreto do produto
O nome do produto **Sauce Labs T-Shirt (Red)** é apresentado incorretamente na página de produtos da aplicação SauceDemo.

### Environment
| Item             | Valor          |
| ---------------- | -------------- |
| Operating System | Windows 11 Pro |
| Browser          | Google Chrome  |
| Application      | SauceDemo      |
| Test Type        | Manual         |
| Device           | Portátil       |

### Preconditions
- Aplicação SauceDemo disponível e acessível.
- Utilizador autenticado com `standard_user`.
- Utilizador na página de produtos (Inventory).

### Steps to Reproduce
1. Aceder à página de login da aplicação SauceDemo.
2. Inserir o username `standard_user`.
3. Inserir a password `secret_sauce`.
4. Clicar em **Login**.
5. Localizar o produto **Test.allTheThings() T-Shirt (Red)** na página de produtos.
6. Verificar o nome apresentado para o produto.

### Expected Result
O produto deve ser apresentado com o nome **"Sauce Labs T-Shirt (Red)"**

### Actual Result
O produto é apresentado com o nome **"Test.allTheThings() T-Shirt (Red)"**

### Severity
**Low:** O defeito afeta a identificação do produto, mas não impede a utilização das principais funcionalidades da aplicação.

### Priority
**Medium:** O nome incorreto pode causar inconsistência na identificação do produto e deve ser corrigido para garantir a precisão das informações apresentadas ao utilizador.

### Related Test Case
`TC-INV-002 — Visualização do nome dos produtos`

### Evidence
- ![BUG-001](img/BUG-001.png)

### Jira 
**Issue:** [BUG-1](https://taynaraluiza.atlassian.net/browse/BUG-1)

---

# BUG-002 — Descrição incorreta do produto
A descrição do produto Sauce Labs Backpack é apresentada incorretamente na página de produtos da aplicação SauceDemo.

### Environment
| Item             | Valor          |
| ---------------- | -------------- |
| Operating System | Windows 11 Pro |
| Browser          | Google Chrome  |
| Application      | SauceDemo      |
| Test Type        | Manual         |
| Device           | Portátil       |

### Preconditions
- Aplicação SauceDemo disponível e acessível.
- Utilizador autenticado com `standard_user`.
- Utilizador na página de produtos (Inventory).

### Steps to Reproduce
1. Aceder à página de login da aplicação SauceDemo.
2. Inserir o username `standard_user`.
3. Inserir a password `secret_sauce`.
4. Clicar em **Login**.
5. Localizar o produto **Sauce Labs Backpack** na página de produtos.
6. Verificar a descrição apresentada para o produto.

### Expected Result
O produto Sauce Labs Backpack deve apresentar a descrição correspondente.

### Actual Result
A descrição apresentada para o produto Sauce Labs Backpack contém erros. A aplicação apresenta: *carry.allTheThings()* with the sleek, streamlined Sly Pack that melds uncompromising style with unequaled laptop and tablet protection.

### Severity
**Low:** O defeito afeta a informação apresentada ao utilizador, mas não impede a utilização das principais funcionalidades da aplicação.

### Priority
**Medium:** A descrição incorreta pode comprometer a precisão das informações do produto e deve ser corrigida.

### Related Test Case
`TC-INV-003 — Visualização da descrição dos produtos`

### Evidence
- ![BUG-002](img/BUG-002.png)

### Jira 
**Issue:** [BUG-2](https://taynaraluiza.atlassian.net/browse/BUG-2)

---

## BUG-003 — First Name aceita apenas números
No checkout step one, o campo **First Name** aceita valores compostos exclusivamente por números, permitindo que o utilizador avance para a etapa seguinte do processo.

### Environment

| Item             | Valor          |
| ---------------- | -------------- |
| Operating System | Windows 11 Pro |
| Browser          | Google Chrome  |
| Application      | SauceDemo      |
| Test Type        | Manual         |
| Device           | Portátil       |

### Preconditions
- Aplicação SauceDemo disponível e acessível.
- Utilizador autenticado com `standard_user`.
- Pelo menos um produto adicionado ao carrinho.
- Utilizador na primeira etapa do checkout.

### Steps to Reproduce
1. Aceder ao carrinho com pelo menos um produto.
2. Clicar em **Checkout**.
3. Inserir `12345` no campo **First Name**.
4. Inserir `Doe` no campo **Last Name**.
5. Inserir `1000-001` no campo **Postal Code**.
6. Clicar em **Continue**.

### Expected Result
O sistema deve validar o conteúdo do campo **First Name** e impedir o avanço quando o valor informado é inválido e apresentar uma mensagem de validação adequada.

### Actual Result
O sistema aceita o valor `12345` no campo **First Name** e permite que o utilizador avance para a etapa seguinte do checkout.

### Severity
**Medium:** O defeito permite a introdução de dados inválidos em um campo de identificação do utilizador e pode resultar no registo de informações incorretas no pedido.

### Priority
**Medium:** A validação inadequada deve ser corrigida para garantir a integridade dos dados introduzidos durante o checkout.

### Related Test Case
`TC-CHECK-003 — Preencher nome somente com números no checkout step one`

### Evidence
- [Video](https://jam.dev/c/35421ada-4257-47b9-8b73-9f6da21384aa)

### Jira
**Issue:** [BUG-3](https://taynaraluiza.atlassian.net/browse/BUG-3)

---

## BUG-004 — Last Name aceita apenas números
No checkout step one, o campo **Last Name** aceita valores compostos exclusivamente por números, permitindo que o utilizador avance para a etapa seguinte do processo.

### Environment

| Item             | Valor          |
| ---------------- | -------------- |
| Operating System | Windows 11 Pro |
| Browser          | Google Chrome  |
| Application      | SauceDemo      |
| Test Type        | Manual         |
| Device           | Portátil       |

### Preconditions
- Aplicação SauceDemo disponível e acessível.
- Utilizador autenticado com `standard_user`.
- Pelo menos um produto adicionado ao carrinho.
- Utilizador na primeira etapa do checkout.

### Steps to Reproduce
1. Aceder ao carrinho com pelo menos um produto.
2. Clicar em **Checkout**.
3. Inserir `John` no campo **First Name**.
4. Inserir `12345` no campo **Last Name**.
5. Inserir `1000-001` no campo **Postal Code**.
6. Clicar em **Continue**.

### Expected Result
O sistema deve validar o conteúdo do campo "Last Name" e impedir o avanço quando o valor informado é inválido e apresentar uma mensagem de validação adequada.

### Actual Result
O sistema aceita o valor `12345` no campo **Last Name** e permite que o utilizador avance para a etapa seguinte do checkout.

### Severity
**Medium:** O defeito permite a introdução de dados inválidos em um campo de identificação do utilizador e pode resultar no registo de informações incorretas no pedido.

### Priority
**Medium:** A validação inadequada deve ser corrigida para garantir a integridade dos dados introduzidos durante o checkout.

### Related Test Case
`TC-CHECK-005 — Preencher sobrenome somente com números no checkout step one`

### Evidence
- [Video](https://jam.dev/c/559287a2-7aab-4172-bce6-ea6e8fae3334)

### Jira
**Issue:** [BUG-4](https://taynaraluiza.atlassian.net/browse/BUG-4)

---

## BUG-005 — Postal Code aceita apenas letras
No checkout step one, o campo **Postal Code** aceita valores compostos exclusivamente por letras, permitindo que o utilizador avance para a etapa seguinte do processo.

### Environment

| Item             | Valor          |
| ---------------- | -------------- |
| Operating System | Windows 11 Pro |
| Browser          | Google Chrome  |
| Application      | SauceDemo      |
| Test Type        | Manual         |
| Device           | Portátil       |

### Preconditions
- Aplicação SauceDemo disponível e acessível.
- Utilizador autenticado com `standard_user`.
- Pelo menos um produto adicionado ao carrinho.
- Utilizador na primeira etapa do checkout.

### Steps to Reproduce
1. Aceder ao carrinho com pelo menos um produto.
2. Clicar em **Checkout**.
3. Inserir `John` no campo **First Name**.
4. Inserir `Doe` no campo **Last Name**.
5. Inserir `abcd` no campo **Postal Code**.
6. Clicar em **Continue**.

### Expected Result
O sistema deve validar o conteúdo do campo "Postal Code" e impedir o avanço quando o valor informado é inválido e apresentar uma mensagem de validação adequada.

### Actual Result
O sistema aceita o valor `abcd` no campo **Postal Code** e permite que o utilizador avance para a etapa seguinte do checkout.

### Severity
**Medium:** O defeito permite a introdução de um código postal em formato inválido e a continuação do processo de checkout com dados inconsistentes.

### Priority
**Medium:** A validação inadequada deve ser corrigida para garantir que o código postal informado esteja em um formato válido antes de o utilizador avançar no processo.

### Related Test Case
`TC-CHECK-007 — Preencher código postal somente com letras no checkout step one`

### Evidence
- [Video](https://jam.dev/c/02da9baf-c8b3-4620-88be-384f9cc5adc1)

### Jira
**Issue:** [BUG-5](https://taynaraluiza.atlassian.net/browse/BUG-5)

---

## BUG-006 — Valor de taxa não identificada no checkout
O checkout apresenta o valor de Shipping como Free, mas adiciona uma taxa ao cálculo do valor total sem identificar claramente a origem ou descrição desse valor.

### Environment
| Item             | Valor          |
| ---------------- | -------------- |
| Operating System | Windows 11 Pro |
| Browser          | Google Chrome  |
| Application      | SauceDemo      |
| Test Type        | Manual         |
| Device           | Portátil       |

### Preconditions
- Aplicação SauceDemo disponível e acessível.
- Utilizador autenticado com `standard_user`.
- Pelo menos um produto adicionado ao carrinho.
- Utilizador na etapa de resumo do checkout (Step Two).

### Steps to Reproduce
1. Aceder ao carrinho com pelo menos um produto.
2. Clicar em **Checkout**.
3. Preencher os campos obrigatórios da primeira etapa do checkout.
4. Clicar em **Continue**.
5. Na etapa de resumo, verificar o valor dos produtos.
6. Verificar o valor apresentado para Shipping.
7. Verificar o cálculo do valor total do pedido.

### Expected Result
O sistema deve apresentar de forma clara e consistente a natureza e a origem de qualquer valor que compõem o total do pedido.

### Actual Result
Os valores dos produtos são apresentados corretamente. Entretanto, apesar de o sistema informar que o Shipping é Free, uma taxa adicional é incluída no cálculo do valor total sem identificação clara do que representa esse valor.

### Severity
**Medium:** O defeito pode gerar inconsistência ou falta de transparência no cálculo apresentado ao utilizador durante a finalização da compra.

### Priority
**Medium:** O problema deve ser analisado para garantir que os valores apresentados no resumo do pedido sejam claros, consistentes e compreensíveis para o utilizador.

### Related Test Case
`TC-CHECK-012 — Validação dos valores no checkout step two`

### Evidence
- [Video](https://jam.dev/c/86d79d0e-2f51-4a62-8d5c-e2cf2fedc990)

### Jira
**Issue:** [BUG-6](https://taynaraluiza.atlassian.net/browse/BUG-6)

---

## BUG-007 — Clicar em **Cancel** no Checkout Step Two retorna para página incorreta
O botão Cancel na segunda etapa do checkout (Checkout Step Two) direciona o utilizador para a página de produtos (Inventory) em vez de retornar ao carrinho.

### Environment
| Item             | Valor          |
| ---------------- | -------------- |
| Operating System | Windows 11 Pro |
| Browser          | Google Chrome  |
| Application      | SauceDemo      |
| Test Type        | Manual         |
| Device           | Portátil       |

### Preconditions
- Aplicação SauceDemo disponível e acessível.
- Utilizador autenticado com `standard_user`.
- Pelo menos um produto adicionado ao carrinho.
- Utilizador na etapa de resumo do checkout (Step Two).

### Steps to Reproduce
1. Aceder ao carrinho com pelo menos um produto.
2. Clicar em **Checkout**.
3. Preencher os campos obrigatórios da primeira etapa do checkout.
4. Clicar em **Continue**.
5. Na segunda etapa do checkout, clicar em **Cancel**.
6. Verificar a página apresentada.

### Expected Result
O checkout deve ser cancelado e o utilizador deve retornar à página do carrinho, mantendo o contexto do pedido iniciado.

### Actual Result
O checkout é cancelado, porém o utilizador é direcionado para a página de produtos (Inventory) em vez de retornar ao carrinho.

### Severity
**Medium:** O comportamento incorreto interrompe o fluxo esperado de navegação e faz com que o utilizador perca o contexto da etapa anterior do processo de compra.

### Priority
**Medium:** O comportamento deve ser corrigido para que o botão Cancel mantenha a navegação consistente com o fluxo esperado do checkout.

### Related Test Case
`TC-CHECK-014 — Cancelar checkout na etapa checkout step two`

### Evidence
- [Video](https://jam.dev/c/bb779eec-60d0-4c81-8bb2-83bc503f4f62)

### Jira
**Issue:** [BUG-7](https://taynaraluiza.atlassian.net/browse/BUG-7)

---