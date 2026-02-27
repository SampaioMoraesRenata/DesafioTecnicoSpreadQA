# Desafio QA - Testes de API Pública

## 📋 Objetivo

Realizar testes funcionais em uma API pública usando Postman, seguindo as melhores práticas de QA e garantindo a qualidade através de casos de teste bem estruturados.

## 🎯 API Selecionada

**[API ViaCEP]**

- **URL Base**: [https://viacep.com.br/ws]
- **Documentação**: [https://viacep.com.br/]

## 📁 Estrutura do Projeto
- **casos-de-teste/**: Especificação em Gherkin dos 3 casos de teste
- **postman/**: Coleção JSON exportada do Postman
- **evidencias/**: Prints e documentação dos resultados
- **relatorio/**: Relatório resumido da execução

## ✅ Casos de Teste Implementados

### CT01 - CEP Válido
- **Descrição**: Teste do fluxo básico da API
- **Status**: ✅ Passou
- **Evidência**: `evidencias/CT01_ CEPValido.png`

### CT02 - CEP Inexistente
- **Descrição**: Teste de fluxo alternativo
- **Status**: ✅ Passou
- **Evidência**: `evidencias/CT02_CEPInexistente.png`

### CT03 - CEP Inválido
- **Descrição**: Teste de tratamento de erros
- **Status**: ✅ Passou
- **Evidência**: `evidencias/CT03_CEPInválido.png`

## 🚀 Como Utilizar Este Projeto

### Pré-requisitos
- Postman instalado (baixar em [postman.com](https://www.postman.com/downloads/))
- Git configurado (opcional, se usar localmente)

### Passos para Executar

1. **Importe a Coleção no Postman**
   - Abra o Postman
   - Clique em "Import"
   - Selecione o arquivo `postman/collection.json`

2. **Execute os Testes**
   - Selecione a coleção importada
   - Clique em "Run" ou execute cada teste individualmente
   - Valide os resultados

## 📊 Resultados da Execução

Todos os **3 casos de teste foram executados com sucesso**.

**Resumo:**
- ✅ Casos positivos: 2
- ✅ Casos negativos: 1
- ✅ Taxa de sucesso: 100%

Para detalhes completos, consulte a pasta `evidencias/`.

## 📝 Critérios de Aceite Atendidos

- ✅ Cenários especificados com Gherkin
- ✅ Caso de teste do fluxo básico baseado na documentação Swagger/OpenAPI
- ✅ Ao menos 1 caso de teste de fluxos alternativos
- ✅ Ao menos 1 caso de teste de fluxo de exceção
- ✅ Artefatos publicados neste repositório GitHub

## 📚 Documentação Adicional

- [Casos de Teste Detalhados](./casos-de-teste/)
- [Coleção Postman](https://renatasampaio-ml-6050587.postman.co/workspace/Renata-Sampaio's-Workspace~7f008231-21d1-4f5b-838e-da70949064e1/collection/52764279-6873edd1-585f-4a81-8af5-b58b6ed2130a?action=share&creator=52764279./postman/)
- [Evidências de Execução](./evidencias/)

## 👤 Informações do Autor

- **Nome**: Renata de Moraes Sampaio Lopes
- **Data**: 27 de Fevereiro de 2026
- **Desafio**: SPREAD QA - Teste de Software



**Status do Projeto**: ✅ Concluído

