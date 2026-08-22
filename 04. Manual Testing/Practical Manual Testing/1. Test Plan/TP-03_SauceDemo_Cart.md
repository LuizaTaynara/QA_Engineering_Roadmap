# TP-03 – Test Plan | Cart

## Objetivo

Validar as funcionalidades do carrinho de compras da aplicação Sauce Demo, garantindo que os produtos adicionados são apresentados corretamente e que o utilizador consegue gerir os itens antes de iniciar o processo de checkout.

---

## Escopo
- Acesso ao carrinho de compras
- Visualização dos produtos adicionados
- Validação das informações dos produtos (nome, descrição e preço)
- Remoção de produtos do carrinho
- Continuação das compras
- Atualização do contador do carrinho
- Navegação para o checkout

---

## Fora do Escopo
- Processo de autenticação
- Validação da listagem de produtos (Inventory)
- Processamento do checkout
- Testes de desempenho
- Testes de segurança
- Testes em múltiplos navegadores e dispositivos

---

## Critérios de Entrada
- Aplicação disponível e acessível
- Login realizado com sucesso
- Pelo menos um produto adicionado ao carrinho

---

## Critérios de Saída
- Todos os casos de teste executados
- Defeitos registados no Jira
- Evidências anexadas ao repositório
- Relatório de execução concluído

---

## Dados de Teste
As credenciais de teste são fornecidas pela plataforma Sauce Demo.
- Dados para login:<br>
**Utilizador:** standard_user <br>
**Palavra-passe:** secret_sauce

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
Os testes serão executados manualmente com base nos requisitos funcionais da aplicação.
<br>
Serão aplicadas as seguintes abordagens:
- Testes funcionais
- Testes positivos
- Testes negativos
- Testes exploratórios
- Validação da interface do utilizador
