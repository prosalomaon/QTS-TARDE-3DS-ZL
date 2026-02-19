# Débito Técnico?

É quando uma equipe de desenvolvimento escolhe uma solução mais rápida ou mais simples para entregar algo logo, mesmo sabendo que essa decisão pode gerar retrabalho no futuro.

É como fazer um empréstimo: você resolve o problema agora, mas depois precisa “pagar a dívida” com mais tempo, esforço e custo.

O termo foi popularizado por Ward Cunningham, um dos autores do Manifesto Ágil.

---

## Por que o débito técnico acontece?

Alguns motivos comuns:

- Pressão por prazos curtos  
- Mudanças frequentes nos requisitos  
- Falta de conhecimento técnico  
- Falta de padronização no código  
- Ausência de testes automatizados  

---

# Tipos de Débito Técnico

## 1. Débito Técnico Intencional (ou estratégico)

A equipe sabe que está fazendo algo menos ideal, mas aceita isso para ganhar velocidade.

**Exemplos:**
- Criar uma solução provisória para validar uma ideia rapidamente.
- Lançar uma funcionalidade simples primeiro e melhorar depois.

---

## 2. Débito Técnico Não Intencional

Acontece por falta de conhecimento, erro de arquitetura ou decisões mal planejadas.

**Exemplos:**
- Código duplicado em várias partes do sistema.
- Estrutura de banco de dados mal planejada que dificulta alterações futuras.

---

## 3. Débito Técnico de Arquitetura

Relacionado a decisões estruturais do sistema.

**Exemplos:**
- Sistema monolítico difícil de escalar.
- Dependência excessiva entre módulos.

---

## 4. Débito Técnico de Código

Problemas diretamente no código-fonte.

**Exemplos:**
- Código difícil de entender.
- Funções muito grandes e confusas.
- Falta de comentários importantes.

---

## 5. Débito Técnico de Testes

Falta de cobertura ou ausência de testes automatizados.

**Exemplos:**
- Não criar testes para acelerar a entrega.
- Testes frágeis que quebram facilmente.

---

## 6. Débito Técnico de Documentação

Falta ou desatualização de documentação.

**Exemplos:**
- API sem documentação.
- Manual do sistema desatualizado.

---

# Consequências do Débito Técnico

Se não for tratado, pode causar:

- Aumento do tempo para implementar novas funcionalidades  
- Mais bugs  
- Dificuldade de manutenção  
- Desmotivação da equipe  
- Aumento de custos  

---

# Como reduzir o Débito Técnico

Boas práticas:

- Refatoração contínua  
- Testes automatizados  
- Revisão de código (code review)  
- Planejamento técnico adequado  
- Reservar tempo para melhorias técnicas  

---

## Resumo Final

Débito técnico não é necessariamente algo ruim — pode ser uma estratégia. O problema é quando ele não é controlado.

Se ignorado, ele cresce como juros acumulados e pode comprometer a qualidade e evolução do software.
