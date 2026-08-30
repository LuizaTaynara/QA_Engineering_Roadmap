# 🛍️ Practical Manual Testing — SauceDemo

## 🎯 Objetivo
Demonstrar competências de Quality Assurance através do planejamento, documentação e execução de testes manuais em uma aplicação web.

O projeto utiliza a aplicação **SauceDemo** como ambiente de prática e reúne os principais artefactos produzidos durante a atividade de testes, incluindo:

- Test Plan
- Test Scenarios
- Test Cases
- Manual Test Execution
- Bug Reports

O objetivo é simular um fluxo de trabalho de QA, desde o planeamento dos testes até a identificação e documentação de defeitos.

## 🌐 Aplicação testada
- [SauceDemo](https://www.saucedemo.com/?utm_source=chatgpt.com)

## 💻 Ambiente de teste
| Item              | Valor                                  |
| ----------------- | -------------------------------------- |
| Sistema Operativo | Windows 11 Pro   |
| Navegador         | Google Chrome    |
| Dispositivo       |Portátil          |
| Tipo de teste     | Manual           |
| Aplicação         | SauceDemo        |

## 📊 Cobertura e resultados
Os testes foram realizados nas principais áreas funcionais da aplicação:

| Área      | Casos de Teste |   PASS |  FAIL | BLOCKED |
| --------- | -------------: | -----: | ----: | ------: |
| Login     |             10 |     10 |     0 |       0 |
| Inventory |             13 |     11 |     2 |       0 |
| Cart      |              9 |      8 |     0 |       1 |
| Checkout  |             19 |     13 |     5 |       1 |
| **Total** |         **51** | **42** | **7** |   **2** |

### Resumo da execução
- **51** casos de teste executados
- **42** casos com resultado **PASS**
- **7** casos com resultado **FAIL**
- **2** casos com resultado **BLOCKED**
- **7 defeitos** identificados e documentados

Os defeitos encontrados foram registados e documentados na secção **Bug Reports**, com referência aos respectivos registos no Jira.


## ❌ Fora do escopo
Este projeto não contempla:
- Testes de desempenho
- Testes de carga
- Testes de segurança
- Testes de compatibilidade entre navegadores
- Testes em dispositivos móveis
- Testes de integrações externas

## 🛠️ Ferramentas utilizadas
- **Google Chrome** — execução dos testes manuais na aplicação web.
- **Google Sheets** — organização e registo dos casos de teste e resultados da execução.
- **Jira** — registo e acompanhamento dos defeitos identificados.
- **Git / GitHub** — versionamento e documentação dos artefactos de teste.

## 📌 Competências demonstradas
- Planeamento de testes
- Definição de cenários de teste
- Escrita de casos de teste
- Execução de testes manuais
- Testes funcionais
- Testes positivos e negativos
- Testes exploratórios
- Validação de requisitos e comportamentos esperados
- Identificação e reporte de defeitos
- Documentação de QA
- Utilização de Jira para gestão de defeitos
- Versionamento e organização de artefactos com Git/GitHub

## 📁 Estrutura do projeto

```text
04.Practical Manual Testing/
├── SauceDemo_Manual_Testing/
|   ├── 1. Test Plan/
|   │   └── TP-01_SauceDemo_Testing_Plan.md
|   ├── 2. Test Scenarios/
|   │   └── TS-01_SauceDemo_Test_Scenarios.md
|   ├── 3. Test Cases/
|   │   ├── 3.01.TC-Login.md
|   |   ├── 3.02.TC-Inventory.md
|   |   ├── 3.03.TC-Cart.md
|   │   └── 3.04.TC-Checkout.md
|   ├── 4. Manual Test Execution/
|   │   └── MTE-01_SauceDemo_Test_Execution.md
|   └── 5. Bug Reports/
|       └── BR-01_SauceDemo_Bug_Reports.md
└──  README.md
```

## 👩🏻‍💻 Autora

- **Luiza Santos**
- **Projeto:** Practical Manual Testing — SauceDemo
- **Ano:** 2026

## Vamos conectar?
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luizataynara/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/LuizaTaynara)
