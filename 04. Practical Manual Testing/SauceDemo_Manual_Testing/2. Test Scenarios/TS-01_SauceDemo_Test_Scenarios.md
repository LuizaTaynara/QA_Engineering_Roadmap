# 2. Test Scenarios 

## Login
| ID            | Test Scenario                  |Objetivo      |
| ---------------- | ------------------------------------ | ----------------------------------- |
| **TS-LOGIN-001** | Login com credenciais válidas        | Verificar se um utilizador válido consegue autenticar-se e aceder à aplicação.                                              |
| **TS-LOGIN-002** | Login com credenciais inválidas      | Verificar se o sistema impede o acesso quando são fornecidas credenciais inválidas e apresenta a mensagem de erro adequada. |
| **TS-LOGIN-003** | Login com campos obrigatórios vazios | Verificar se o sistema valida os campos obrigatórios quando o formulário é submetido sem informações.                       |
| **TS-LOGIN-004** | Login com utilizador bloqueado       | Verificar se um utilizador bloqueado não consegue aceder à aplicação e se o sistema apresenta a mensagem correspondente.    |
| **TS-LOGIN-005** | Visibilidade da palavra-passe        | Verificar se a palavra-passe inserida é ocultada no campo de autenticação.                                                  |
| **TS-LOGIN-006** | Logout                               | Verificar se um utilizador autenticado consegue terminar a sessão corretamente.          |

## Inventory
| ID             | Test Scenario                   | Objetivo                                |
| -------------- | ----------------------------------------- | ----------------------------- |
| **TS-INV-001** | Acesso à página de produtos               | Verificar se o utilizador autenticado consegue aceder à página de produtos corretamente.                     |
| **TS-INV-002** | Visualização dos produtos                 | Verificar se os produtos são apresentados corretamente, incluindo nome, descrição, preço e imagem.           |
| **TS-INV-003** | Ordenação dos produtos                    | Verificar se a lista de produtos pode ser ordenada de acordo com as opções disponibilizadas pela aplicação.  |
| **TS-INV-004** | Adição de produtos ao carrinho            | Verificar se o utilizador consegue adicionar produtos ao carrinho e se o contador é atualizado corretamente. |
| **TS-INV-005** | Remoção de produtos da página de produtos | Verificar se um produto adicionado ao carrinho pode ser removido diretamente a partir da página de produtos. |
| **TS-INV-006** | Navegação para o carrinho                 | Verificar se o utilizador consegue aceder ao carrinho através da página de produtos.         |

## Cart
| ID              | Test Scenario                          | Objetivo                                                                                                       |
| --------------- | -------------------------------------- | ------------------------------------------------------------------------------------ |
| **TS-CART-001** | Acesso ao carrinho                     | Verificar se o utilizador consegue aceder ao carrinho a partir da página de produtos.                          |
| **TS-CART-002** | Visualização dos produtos no carrinho  | Verificar se os produtos adicionados são apresentados corretamente, incluindo nome, descrição e preço.         |
| **TS-CART-003** | Gestão dos produtos no carrinho        | Verificar se o utilizador consegue gerir os produtos adicionados, incluindo remoção e alteração da quantidade. |
| **TS-CART-004** | Acesso ao produto a partir do carrinho | Verificar se o utilizador consegue aceder aos detalhes de um produto a partir do carrinho.                     |
| **TS-CART-005** | Continuação das compras                | Verificar se o utilizador consegue retornar à página de produtos para continuar as compras.                    |
| **TS-CART-006** | Navegação para o checkout              | Verificar se o utilizador consegue iniciar o processo de checkout a partir do carrinho.                        |



## Checkout
| ID               | Test Scenario                                | Objetivo                                                                                                                             |
| ---------------- | -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **TS-CHECK-001** | Acesso ao checkout                           | Verificar se o utilizador consegue iniciar o processo de checkout a partir do carrinho.                                              |
| **TS-CHECK-002** | Validação dos campos obrigatórios            | Verificar se o sistema valida o preenchimento dos campos obrigatórios antes de permitir o avanço no checkout.                        |
| **TS-CHECK-003** | Preenchimento das informações do cliente     | Verificar se o utilizador consegue preencher as informações necessárias para avançar no checkout.                                    |
| **TS-CHECK-004** | Visualização e validação do resumo da compra | Verificar se o resumo apresenta corretamente os produtos, valores e informações relacionadas ao pedido antes da conclusão da compra. |
| **TS-CHECK-005** | Cancelamento do checkout                     | Verificar se o utilizador consegue cancelar o processo de checkout e retornar ao fluxo anterior sem concluir a compra.               |
| **TS-CHECK-006** | Conclusão da compra                          | Verificar se o utilizador consegue concluir o pedido com sucesso e se a confirmação da compra é apresentada corretamente.            |
| **TS-CHECK-007** | Funcionalidades após a conclusão da compra   | Verificar se as funcionalidades disponibilizadas após a conclusão da compra funcionam corretamente.                                  |

---
