# TP-01 - Test Plan | Login

## Objetivo
Validar o fluxo de autenticação da aplicação Sauce Demo, garantindo que o utilizador consiga aceder ao sistema com credenciais válidas e que as validações e mensagens de erro são apresentadas corretamente em cenários inválidos.

---

## Escopo
- Tela de login
- Login com credenciais válidas
- Login com credenciais inválidas
- Validação de campos obrigatórios
- Mensagens de erro
- Utilizador bloqueado
- Ocultação da palavra-passe
- Logout

---

## Fora do Escopo
- Recuperação de palavra-passe (funcionalidade não disponível na aplicação)
- Testes de desempenho
- Testes de carga
- Testes de segurança
- Testes de compatibilidade entre navegadores
- Testes em dispositivos móveis

---

## Critérios de entrada
- Aplicação disponível e acessível
- Credenciais de teste disponíveis
- Navegador Google Chrome instalado
  
---

## Critérios de saída
- Todos os casos de teste executados
- Defeitos registados no Jira
- Evidências anexadas ao repositório

---

## Dados de teste
Utilizadores disponibilizados pela própria aplicação:

| Username | Descrição | Password |
|----------|-----------|-----------|
|standard_user | Utilizador válido| secret_sauce |
|locked_out_user | Utilizador bloqueado | secret_sauce |
|problem_user	| Utilizador com comportamento inesperado | secret_sauce |
|performance_glitch_user |Utilizador para testes de desempenho|secret_sauce |
|error_user	| Utilizador para testes específicos da aplicação | secret_sauce |
|visual_user	| Utilizador para testes visuais | secret_sauce |

---

## Riscos e Limitações
- Dependência da disponibilidade da plataforma Sauce Demo
- Possíveis alterações no ambiente de demonstração sem aviso prévio
- Projeto limitado às funcionalidades disponibilizadas pela aplicação

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
- Testes Funcionais
- Testes Positivos
- Testes Negativos
- Validação de mensagens de erro
- Validação de campos obrigatórios
