# Consulta de CEP Microsserviço

Este projeto é um microsserviço em Java utilizando Spring Boot que consulta informações de endereço a partir de um CEP fornecido, utilizando a API ViaCep.

## Descrição do Projeto

**Objetivo:** Criar um microsserviço que consulta o CEP em uma API dos Correios e retorna as informações sobre o endereço.

**Tecnologias Recomendadas:**
- Linguagem: Java
- Framework: Spring Boot
- Testes: JUnit
- Controle de versão: Git (repositório no GitHub)
- API para consulta de CEP: ViaCep (https://viacep.com.br/)

### Requisitos do Projeto

1. **Microsserviço:**
   - O microsserviço deve ter um endpoint para receber um CEP como parâmetro.
   - Consultar a API ViaCep com o CEP fornecido.
   - Retornar as informações do endereço em um formato JSON.

2. **Lógica Adicional:**
   - Se o CEP não for encontrado, retornar uma mensagem de erro apropriada.
   - Validar o formato do CEP antes de fazer a consulta (CEP deve ter 8 dígitos numéricos).
   - Cachear as respostas das consultas de CEP para melhorar a performance (opcional, pode ser implementado com Spring Cache).

3. **Testes:**
   - Implementar testes unitários e de integração para garantir o correto funcionamento do microsserviço.

4. **Documentação:**
   - Documentar a API utilizando Swagger ou outra ferramenta similar.
   - Incluir um README no repositório com instruções claras sobre como configurar e rodar o projeto.

5. **Acessibilidade:**
   - Garantir que a documentação e as instruções de uso do repositório estejam claras e acessíveis.
   - Sugerir boas práticas de acessibilidade no código, como comentários claros e legíveis.

## Estrutura do Projeto

### 1. Configuração do Projeto

- Crie um novo projeto Spring Boot utilizando o Spring Initializr (https://start.spring.io/), incluindo as seguintes dependências:
  - Spring Web
  - Spring Boot DevTools
  - Lombok (opcional)
  - Spring Cache (opcional)
  - Spring Boot Starter Test

### Instruções para o Candidato
Clone o repositório:

Crie um fork do repositório e clone para a sua máquina local.
Implementação:

Implemente o serviço conforme os requisitos descritos.
Utilize commits pequenos e frequentes para demonstrar o progresso.
Documentação:

Adicione um README com instruções claras sobre como configurar, executar o projeto e rodar os testes.
Documente a API utilizando Swagger ou outra ferramenta similar.

### Critérios de Avaliação
Funcionamento correto do microsserviço.
Implementação correta das validações e lógica adicional.
Qualidade e clareza do código.
Cobertura e qualidade dos testes.
Documentação adequada e clara.
Uso adequado do Git (commits significativos e bem descritos).
