# Tipos de Testes

## TESTES DE CAIXA-PRETA
É uma técnica de teste em que avaliamos o comportamento do sistema sem saber ou olhar o código fonte. Mais focando no que o software faz, pode-se dizer que é totalmente voltado a funcionalidades, regras de negócio e documentação. Acredito que a maior parte dos testes efetuados segue nesse modelo.
Os casos de testes criados no modelo caixa-preta são baseados em: requisitos funcionais, regras de negócio e especificações do sistema.

### Extras
Independência da implementação: não exige conhecimento de programação.
Foco em:
* Falhas lógicas
* Requisitos ausentes ou ambíguos
* Comportamentos inesperados
* Problemas de usabilidade

---

## TESTES DE CAIXA-BRANCA
Pode-se dizer que é mais focado em ver a lógica do código e identificar se todos os caminhos do código funcionam em todos os cenários. Importa o que tem no código e podem ser utilizadas diversas ferramentas para auxiliar a validação dos testes.
O benefício do teste é que podem ser identificadas falhas na lógica interna, loops infinitos, erros de sintaxe (código escrito errado) e caminhos de código que nunca foram testados. Tem uma necessidade de entendimento sobre códigos (programação).

## Testes Estruturais (Foco em Caixa-Branca)
* Testes de cobertura de código
* Testes de caminho
* Testes de decisão
* Testes de condição
---

## Testes Funcionais

**Testes de funcionalidade:**
Basicamente, é testar se os botões, os formulários e os fluxos do sistema realmente funcionam para o usuário final.

**Testes de usabilidade:**
Garantir que os botões não estão escondidos ou com um texto confuso. É fácil, intuitivo e agradável de usar!

**Testes de aceitação do usuário (UAT):**
Garante que o sistema entrega o valor desejado do solicitante (na prática, no dia a dia), e que todos os requisitos foram atendidos/finalizados.

**Testes de integração:**
Garante que todas as partes (módulos) de um sistema se comuniquem de forma correta e que se integrem no funcionamento geral do software.

---

## Testes Não Funcionais

**Testes de desempenho (performance):**
Garante que o sistema funcione rápido, seja responsivo e que suas funções apareçam em tempo aceitável.

**Testes de carga:**
Tem como objetivo analisar se o sistema entrega a capacidade de funcionamento para a quantidade normal/máxima de usuários esperada.

**Testes de estresse:**
Testa o comportamento do sistema com estresse, passando da carga deliberada, para descobrir o ponto em que ele vai quebrar e avaliar qual é o seu comportamento ao falhar.

**Testes de segurança:**
Tem como prioridade a proteção do sistema: testes de intrusão, testes para analisar a segurança de modo geral de seus componentes, proteção contra ataques, vazamentos, entre outros.

**Testes de portabilidade:**
Focado em observar como o sistema age quando colocado em diferentes ambientes, navegadores e Sistemas Operacionais, para garantir uma experiência consistente em todos eles.

**Testes de confiabilidade:**
Verifica que o sistema pode funcionar por longos períodos sem falhar, garantindo que ele faça o que foi criado para fazer em pleno funcionamento e estabilidade.

---

