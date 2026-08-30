# 1. Test Plan 

## Objetivo
Validar as principais funcionalidades da aplicação SauceDemo, verificando se os fluxos de autenticação, gestão de produtos, carrinho de compras e checkout funcionam conforme o comportamento esperado.

O teste tem como objetivo identificar defeitos funcionais, comportamentos inesperados e problemas nas principais jornadas do utilizador.

## Escopo
O projeto contempla as seguintes áreas funcionais:

### Login
- Acesso à tela de login
- Login com credenciais válidas
- Login com credenciais inválidas
- Validação de campos obrigatórios
- Mensagens de erro
- Comportamento para utilizador bloqueado
- Ocultação da palavra-passe
- Logout

### Inventory
- Acesso à página de produtos após login
- Visualização da lista de produtos
- Validação do nome, descrição e preço dos produtos
- Validação das imagens dos produtos
- Ordenação dos produtos
- Adição de produtos ao carrinho
- Atualização do contador do carrinho
- Navegação para o carrinho

### Cart
- Acesso ao carrinho
- Visualização dos produtos adicionados
- Validação das informações dos produtos
- Remoção de produtos
- Continuação das compras
- Atualização do contador do carrinho
- Navegação para o checkout

### Checkout
- Acesso ao processo de checkout
- Validação dos campos obrigatórios
- Mensagens de erro
- Preenchimento das informações do cliente
- Visualização do resumo da compra
- Conclusão da compra
- Cancelamento do checkout
- Mensagem de confirmação da compra

## Fora do Escopo
- Recuperação de palavra-passe
- Testes de desempenho
- Testes de carga
- Testes de segurança
- Testes de compatibilidade entre navegadores
- Testes em dispositivos móveis

## Estratégia de Testes
Os testes serão executados manualmente, com foco na validação funcional das principais jornadas da aplicação.

Serão utilizados:
- Testes funcionais
- Cenários positivos e negativos
- Validação de campos e mensagens de erro
- Testes exploratórios, quando apropriado
- Validação de comportamentos relacionados às principais jornadas do utilizador

Os testes serão derivados dos cenários e casos de teste definidos para cada área funcional.

## Critérios de Entrada
- Aplicação disponível e acessível
- Ambiente de teste disponível
- Credenciais de teste disponíveis
- Navegador Google Chrome instalado
- Funcionalidades incluídas no escopo disponíveis para teste

## Critérios de Saída
- Casos de teste planejados executados
- Resultados da execução registrados
- Defeitos identificados documentados
- Resultados analisados
- Testes concluídos para as áreas definidas no escopo

## Dados de Teste
A aplicação SauceDemo disponibiliza diferentes utilizadores para testes.

| Username                  | Descrição                                                                                        | Password       |
| ------------------------- | ------------------------------------------------------------------------------------------------ | -------------- |
| `standard_user`           | Utilizador padrão para execução dos principais fluxos                                            | `secret_sauce` |
| `locked_out_user`         | Utilizador bloqueado                                                                             | `secret_sauce` |
| `problem_user`            | Utilizador disponibilizado para testar comportamentos específicos da aplicação                   | `secret_sauce` |
| `performance_glitch_user` | Utilizador disponibilizado pela aplicação com comportamento relacionado ao desempenho            | `secret_sauce` |
| `error_user`              | Utilizador disponibilizado para testar comportamentos específicos da aplicação                   | `secret_sauce` |
| `visual_user`             | Utilizador disponibilizado pela aplicação para comportamentos relacionados à apresentação visual | `secret_sauce` |

Para os principais fluxos funcionais deste projeto, o `standard_user` será utilizado como utilizador principal.

O `locked_out_user` será utilizado para validar o comportamento de autenticação de um utilizador bloqueado.

Os demais utilizadores serão utilizados apenas quando houver um objetivo de teste relacionado ao comportamento que pretendemos avaliar.

### Dados para Checkout
| Campo         | Valor    |
| ------------- | -------- |
| Nome          | John     |
| Apelido       | Doe      |
| Código Postal | 1000-100 |

> Os dados utilizados são fictícios e destinam-se exclusivamente ao teste da aplicação.

## Ambiente de Testes
| Item              | Valor          |
| ----------------- | -------------- |
| Sistema Operativo | Windows 11 Pro |
| Navegador         | Google Chrome  |
| Aplicação         | SauceDemo      |
| Tipo de teste     | Manual         |
| Dispositivo       | Portátil       |

## Riscos e Limitações
- Dependência da disponibilidade da plataforma SauceDemo.
- Possíveis alterações no ambiente de demonstração sem aviso prévio.
- Alterações nas funcionalidades ou dados disponibilizados pela aplicação.
- O projeto está limitado às funcionalidades incluídas no escopo definido.
- A execução será realizada em um único navegador e dispositivo.

---