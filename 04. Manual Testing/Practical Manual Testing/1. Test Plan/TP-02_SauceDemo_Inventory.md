# TP-02 - Test Plan | Inventory

## Objetivo

Validar as funcionalidades da página de produtos (Inventory) da aplicação Sauce Demo, garantindo que os produtos são apresentados corretamente e que o utilizador consegue visualizar, ordenar, adicionar e remover produtos do carrinho de compras.

---

## Escopo
- Acesso à página de produtos após login com sucesso
- Visualização da lista de produtos
- Validação do nome, descrição e preço dos produtos
- Validação das imagens dos produtos
- Navegação para o carrinho de compras
- Ordenação dos produtos
- Adição de produtos ao carrinho
- Atualização do contador do carrinho
- Navegação para o carrinho de compras

---

## Fora do Escopo
- Testes de desempenho
- Testes de segurança
- Testes em múltiplos navegadores
- Testes em dispositivos móveis

---

## Critérios de Entrada
- Aplicação disponível e acessível
- Login realizado com sucesso
- Página de produtos carregada corretamente

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
- Alterações na lista de produtos disponibilizada pela aplicação

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
- Validação da interface do utilizador
- Testes exploratórios
