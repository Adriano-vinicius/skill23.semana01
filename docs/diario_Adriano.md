# Diário Técnico Individual - Semana 01
**Competidor:** [Seu Nome]

---

## 📅 Dia 1 (26/05) - Diagnóstico, Triagem e Organização
### Atividades Executadas:
- **Organização da Bancada:** Realizei a triagem física de todos os itens e componentes contidos no kit de robótica móvel, posicionando-os de forma estruturada na bancada de trabalho para garantir um ambiente limpo e seguro.
- **Digitalização do Inventário:** Efetuei a digitalização e o registro fotográfico de todos os componentes para iniciar a linha de base de rastreabilidade do hardware.

---

## 📅 Dia 2 (27/05) - Estudo de Ecossistema, Cabeamento e Inicialização
### Atividades Executadas:
- **Estudo de Cabeamento:** Analisei detalhadamente os tipos de cabos do kit, compreendendo suas funções, pinagens e conexões apropriadas para evitar falhas de comunicação ou alimentação.
- **Primeira Inicialização do VMX2:** Executei o procedimento de inicialização do controlador principal. Realizei a conexão física de potência conectando a bateria de 12V no driver de motores Titan Quad e, em seguida, derivando a alimentação correta do Titan para o VMX2.
- **Reset do Controlador:** Em trabalho conjunto com Vitor, executei o procedimento de reset de fábrica/firmware do controlador VMX2 para garantir um estado limpo de operação e livre de parametrizações anteriores.
- **Governança no Git:** Estruturei o repositório oficial da equipe no GitHub, configurando o arquivo README principal e o Checklist Elétrico de Bancada obrigatório.

### Aprendizado Técnico e Conclusões do Dia:
Compreendi a arquitetura de distribuição de energia do ecossistema: a corrente flui da bateria para o Titan Quad, que por sua vez gerencia a potência e alimenta o VMX2 de forma protegida. 

O mapeamento rigoroso dos cabos e o checklist pré-energização reduzem drasticamente o risco de danos por inversão de polaridade. O procedimento de reset realizado em dupla foi fundamental para estabelecer um ponto de partida confiável (baseline) para o desenvolvimento de software que iniciaremos nas próximas etapas.

---
