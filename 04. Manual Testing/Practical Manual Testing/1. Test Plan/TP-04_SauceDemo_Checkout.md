# TP-04 – Test Plan | Checkout

## Objetivo
Validar o processo de checkout da aplicação Sauce Demo, garantindo que o utilizador consegue fornecer as informações necessárias, visualizar o resumo da compra e concluir o pedido com sucesso.

---

## Escopo
- Acesso ao processo de checkout
- Validação dos campos obrigatórios
- Validação das mensagens de erro
- Preenchimento das informações do cliente
- Visualização do resumo da compra
- Conclusão da compra
- Cancelamento do checkout
- Validação da mensagem de confirmação da compra

---

## Fora do Escopo
- Processo de autenticação
- Navegação na página de produtos (Inventory)
- Gestão do carrinho de compras
- Testes de desempenho
- Testes de segurança
- Testes em múltiplos navegadores e dispositivos

---

## Critérios de Entrada
- Aplicação disponível e acessível
- Login realizado com sucesso
- Pelo menos um produto adicionado ao carrinho
- Utilizador na página do carrinho de compras

---

## Critérios de Saída
- Todos os casos de teste executados
- Defeitos registados no Jira
- Evidências anexadas ao repositório
- Relatório de execução concluído

---

## Dados de Teste
- Dados para login:<br>
**Utilizador:** standard_user <br>
**Palavra-passe:** secret_sauce

- Dados para Checkout: <br>
  Nome: João <br>
  Apelido: Silva <br>
  Código Postal: 1000-001 <br>

---

## Riscos e Limitações
- Dependência da disponibilidade da plataforma Sauce Demo
- Possíveis alterações no ambiente de demonstração sem aviso prévio
- O projeto contempla apenas as funcionalidades disponíveis na aplicação

---

## Ambiente de Testes
| Item |	Valor |
|----------|-----------|
|Sistema Operativo |Windows 11 Pro|
|Navegador	| Google Chrome |
|Aplicação	|Sauce Demo|
|Tipo de teste	|Manual|
|Dispositivo|	Desktop|

---

## Estratégia de Testes
Os testes serão executados manualmente com base nos requisitos funcionais da aplicação. <br>
Serão aplicadas as seguintes abordagens: <br>
- Testes funcionais
- Testes positivos
- Testes negativos
- Validação dos campos obrigatórios
- Validação das mensagens de erro
- Testes exploratórios
