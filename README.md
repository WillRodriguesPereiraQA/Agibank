# Agibank
Teste técnico QA – Web

## Framework (Playwright + TypeScript)
Neste framework de automação de casos de testes de QA, realizei a validação da funcionalidade de search do blog, com a correta exibição dos artigos e correto funcionamento do serviço de simulação de empréstimo pessoal. 

Criei 2 casos de testes:

- Validar a exibição com sucesso do artigo sobre diminuição da parcela do empréstimo consignado
- Validar que a simulação de empréstimo pessoal funciona com sucesso



### Requisitos
- Node.js

### Instalação
```bash
npm install
npx playwright install
```

### Rodando os testes
```bash
npx playwright test tests/agibank-cases.spec.ts --headed
```

### Relatório HTML
```bash
npx playwright show-report
```
