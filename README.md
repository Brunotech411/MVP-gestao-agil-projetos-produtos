# MVP-gestao-agil-projetos-produtos

Repositório do MVP desenvolvido na disciplina **Gestão Ágil de Projetos e Produtos** do curso de Pós-Graduação em Engenharia de Software da PUC-Rio.  

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

---

## 💰 Custo e Esforço Estimado
- **Tempo de desenvolvimento (MVP):** ~6 a 8 semanas com um time de 1 PO, 1 SM e 3 devs.  
- **Esforço total (Sprint 1):** ~15 a 18 Story Points.  
- **Custo estimado:** R$ 120.000 – R$ 150.000 (considerando time ágil com salários médios + infraestrutura mínima de nuvem + tablets Ex-proof para validação).  


---

## 📌 Artefatos da Entrega

- **Lean Inception + MVP Canvas**  
  [Acessar no Miro](https://miro.com/app/board/uXjVJFRopp8=/?share_link_id=287627100484)

- **Product Backlog** (épicos, features, user stories, DoR e DoD)  
  [product-backlog.pdf](https://github.com/Brunotech411/MVP-gestao-agil-projetos-produtos/blob/main/product-backlog.pdf.pdf)

- **Sprint Backlog** (Sprint 1, histórias detalhadas, estimativas, critérios de aceitação)  
  [sprint-backlog.pdf](./sprint-backlog.pdf)

- **Wireframes (protótipos low-fi)**  
  [Wireframes - Tablet](./wireframes/fluxo_tecnico_tablet.pdf)  
  [Wireframes - Desktop](./wireframes/fluxo_engenheiro_desktop.pdf)

---

## 🛠️ Contexto do Produto

O **Smart Field Tech** é um sistema que conecta técnicos em campo e engenheiros na base, permitindo:  
- Registro de tarefas e diagnósticos rápidos pelo **tablet** (modo offline/online).  
- Visualização de backlog, histórico e recomendações inteligentes para o **engenheiro** em desktop.  
- Upload de evidências (fotos, vídeos, relatórios).  
- Geração de insights de manutenção preditiva.  

---

## 👥 Equipe Scrum (hipotética)

- **Product Owner**: Bruno Leonardo Ramos dos Santos  
- **Scrum Master**: (nome fictício)  
- **Development Team**:  
  - Dev Backend (Python/Flask)  
  - Dev Frontend (Figma/HTML/JS)  
  - Engenheiro de Testes  
  - UX Designer  

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


