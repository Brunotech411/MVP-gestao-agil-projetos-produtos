# MVP-gestao-agil-projetos-produtos

Repositório do MVP desenvolvido na disciplina **Gestão Ágil de Projetos e Produtos** do curso de Pós-Graduação em Engenharia de Software da PUC-Rio.  

## 📌 Artefatos da Entrega

- **Lean Inception + MVP Canvas**  
  [Acessar no Miro](https://miro.com/app/board/uXjVJFRopp8=/?share_link_id=287627100484)

- **Sprint Backlog** (Sprint 1, histórias detalhadas, estimativas, critérios de aceitação)  
  [sprint-backlog.pdf](https://github.com/Brunotech411/MVP-gestao-agil-projetos-produtos/blob/main/sprint-backlog.pdf.pdf)

- **Wireframes (protótipos low-fi)**  
  [Wireframes - Tablet](https://github.com/Brunotech411/MVP-gestao-agil-projetos-produtos/blob/main/wireframe/Fluxo%20T%C3%A9cnico%20(Tablet%201280x800).pdf)  
  [Wireframes - Desktop](https://github.com/Brunotech411/MVP-gestao-agil-projetos-produtos/blob/main/wireframe/Fluxo%20do%20Engenheiro%20(Desktop).pdf)

---

## 👥 Equipe Scrum (hipotética)

- **Product Owner**: **Phelipe**  
  Responsável por priorizar o Product Backlog, definir metas da sprint, aceitar/rejeitar histórias e representar as necessidades do negócio no dia a dia (Jira, critérios de aceitação, valor de negócio).

- **Scrum Master / Dev Backend**: **Bruno Leonardo Ramos dos Santos**  
  Facilita cerimônias, remove impedimentos e garante a aderência ao framework. Atua também como **desenvolvedor backend** (Python/Flask, SQLite, documentação Swagger, integração com dados).

- **Dev Frontend**: **Milene**  
  Responsável pelo **Figma → HTML/CSS/JS**, padronização de componentes, responsividade (tablet/desktop) e fidelidade ao wireframe.

- **Stakeholder (Cliente principal)**: **Lucas**  
  Participação **apenas no Kickoff e no Showcase/Review**, validando escopo, demonstrativos e incrementos entregues (papel de cliente e principal stakeholder).

### Participação nas cerimônias
- **Sprint Planning**: Phelipe, Bruno, Milene (Lucas opcional para alinhar expectativas).
- **Daily Scrum**: Bruno, Milene.
- **Sprint Review / Showcase**: Phelipe, Bruno, Milene **+ Lucas**.
- **Retrospective**: Phelipe, Bruno, Milene.

### Habilidades-chave (resumo)
- **Phelipe**: priorização, descoberta de produto, escrita de histórias, gestão de stakeholders (Jira/Miro).
- **Bruno**: arquitetura e APIs em Flask, banco de dados SQLite, testes básicos, automação de documentação (Swagger).
- **Milene**: prototipação no Figma, implementação front-end, usabilidade, design system low-fi → high-fi.
- **Lucas**: validação de necessidades, feedback de negócio, aceite de demonstrações no showcase.

Equipe enxuta, com foco na entrega incremental do MVP.

---

## ✅ Definition of Ready (DoR)
- História descrita no formato "Como [persona], quero [ação] para [benefício]".  
- Critérios de aceitação definidos.  
- Estimativa atribuída em story points.  
- Dependências identificadas.  

## ✅ Definition of Done (DoD)
- Código implementado, revisado e testado.  
- Critérios de aceitação atendidos.  
- Testes automatizados executados.  
- Protótipo atualizado no Figma.  
- **Requisito não funcional**: resposta das telas < 3s em 95% dos acessos.

---

## 📌 Contexto
O **Smart Field Tech** é um assistente digital voltado para técnicos de manutenção em campo em ambientes industriais.  
A solução nasceu da necessidade de agilizar o acesso a informações técnicas críticas durante manutenções preventivas e corretivas, reduzindo a dependência dos técnicos em relação aos supervisores e evitando o retrabalho causado por deslocamentos até a oficina.

Nosso foco é oferecer um **MVP funcional** que demonstre valor imediato ao usuário final, ao mesmo tempo em que pavimenta o caminho para incrementos futuros mais robustos.

---

## 🛠 Problema
Em plantas industriais complexas, como petroquímicas, técnicos de manutenção frequentemente enfrentam dificuldades para acessar documentação técnica no campo. Isso gera:
- Perda de tempo ao retornar para a oficina em busca de documentos.  
- Dependência excessiva dos técnicos juniores em relação a colegas mais experientes.  
- Supervisores sobrecarregados com consultas recorrentes.  
- Risco de falhas devido à ausência de informações no momento da manutenção.  

---

## 💡 Solução
O **Smart Field Tech** concentra em um tablet **Ex-proof** todas as informações necessárias para a execução de tarefas em campo.  
Com a solução, técnicos podem consultar dados do equipamento, acessar diagramas e gerar relatórios automáticos de forma rápida e segura.

---

## 🚀 Principais Funcionalidades (MVP – Sprint 1)
- **Consulta por TAG** → localizar rapidamente equipamentos no sistema.  
- **Acesso a Documentação Técnica** → visualizar P&ID, diagramas de loop e cable list associados ao TAG.  
- **Relatórios Digitais Automáticos** → gerar e enviar relatórios ao final de cada tarefa, garantindo rastreabilidade e comunicação imediata com supervisores.  

---

## 📈 Próximos Passos (Evolução do Produto)
- **Checklist digital de manutenção** para padronizar inspeções.  
- **Tablet Master** para supervisores acompanharem atividades em tempo real.  
- **Dashboards de KPIs** para engenheiros de base acompanharem desempenho e criticidade.  
- **Sugestões de análise de causa raiz** para acelerar diagnósticos complexos. 
- **Inteligência artificial generativa** para auxiliar com insights e estudos complexos.

---

## 💰 Custo e Esforço Estimado
- **Tempo de desenvolvimento (MVP):** ~6 a 8 semanas com um time de 1 PO, 1 SM e 3 devs.  
- **Esforço total (Sprint 1):** ~15 a 18 Story Points.  
- **Custo estimado:** R$ 120.000 – R$ 150.000 (considerando time ágil com salários médios + infraestrutura mínima de nuvem + tablets Ex-proof para validação).  


---