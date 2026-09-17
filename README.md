# Bruno Mello

**Profissional de Operações de TI (NOC) que usa automação, integração de sistemas e análise de dados para eliminar trabalho manual e tornar processos operacionais mais rápidos e confiáveis.**

## Sobre mim

Atuo em operações de NOC na Padtec S/A / COPE Fibrasil, lidando diariamente com monitoramento de rede, gestão de incidentes e rotinas operacionais que dependem de múltiplos sistemas internos. A partir dessa rotina, desenvolvo ferramentas e automações que eliminam tarefas manuais repetitivas — de geração e envio de relatórios a apoio à comunicação em situações críticas e painéis de acompanhamento operacional.

Meu foco não é só escrever código: é entender o processo por trás da tarefa, identificar onde o trabalho manual introduz risco ou atraso, e desenhar uma solução confiável para resolver isso.

Também curso Administração (UNIASSELVI), o que reforça a leitura de processo e de impacto organizacional por trás de cada automação que construo.

## 🛠️ Tecnologias

**Linguagens**
- Python
- JavaScript
- React

**Automação**
- pywin32 (automação COM do Microsoft Outlook)
- Execução via atalho (.bat) para uso imediato pela equipe

**Integração / Comunicação**
- Envio automatizado de mensagens para grupos operacionais no Telegram
- *[A confirmar: integração via API/token com o sistema SIGO — em roadmap]*

**Dados**
- Processamento de planilhas Excel exportadas de sistemas internos

**Ferramentas**
- Git & GitHub
- Microsoft Outlook (automação via COM)

## 🚀 Projetos em destaque

### 📧 Automação do Status Diário (SIGO → Outlook)
**Tipo:** Automação de processo · geração e envio de relatório
📁 [`automacao-status-diario-sigo`](https://github.com/brunomellodasilva/automacao-status-diario-sigo)

**Problema:** rotina diária de exportar manualmente um relatório de status do sistema SIGO e montar/enviar um e-mail padronizado com esse anexo, todos os dias, no início do turno.

**Solução:** script Python que localiza o relatório mais recente, monta o e-mail a partir de um template já configurado no Outlook e envia automaticamente — disponível como atalho de duplo clique para uso imediato pela equipe.

**Resultado:** elimina a montagem manual do e-mail diário. *[A preencher: tempo médio economizado, se houver esse dado.]*

---

### 🚨 Gerador de Aviso de Sala de Crise
**Tipo:** Automação de processo · geração de comunicação operacional
📁 [`gerador-aviso-sala-de-crise`](https://github.com/brunomellodasilva/gerador-aviso-sala-de-crise)

**Problema:** ao abrir uma Sala de Crise, a equipe de NOC precisa comunicar o grupo responsável rapidamente e com dados consistentes (local, clientes afetados, equipamento) — montar essa mensagem manualmente, sob pressão de tempo, gera risco de erro e inconsistência.

**Solução:** ferramenta que lê os dados exportados do sistema de gestão de alarmes (arquivo ou print de tela) e gera automaticamente a mensagem padronizada, pronta para envio ao grupo de Telegram responsável.

**Resultado:** padroniza a comunicação de abertura de Sala de Crise e reduz o tempo entre identificação da ocorrência e o aviso à equipe. *[A preencher: métricas, se houver.]*

---

### 📊 Dashboard de Cobrança de TTKs/Parciais
**Tipo:** Painel web · automação de cobrança e visibilidade operacional
📁 [`dashboard-cobranca-ttk-parciais`](https://github.com/brunomellodasilva/dashboard-cobranca-ttk-parciais)

**Problema:** conferir manualmente, entre dezenas de chamados, quais equipes de campo estouraram o prazo prometido de retorno — e montar a mensagem de cobrança para cada uma — consome tempo do NOC várias vezes ao dia, sem visibilidade consolidada do volume cobrado.

**Solução:** painel web em React que importa a planilha de acompanhamento, aplica a regra de prazo, agrupa os chamados por equipe responsável e gera a mensagem de cobrança pronta para o Telegram, além de um dashboard de volumetria com KPIs do dia.

**Resultado:** reduz o tempo gasto para identificar e cobrar chamados parados, com visibilidade do volume de cobranças ao longo do turno. *[A preencher: frequência de uso, tempo economizado por ciclo, se houver esse dado.]*

---

## 📫 Contato

- LinkedIn: [linkedin.com/in/brunomellodasilva](https://linkedin.com/in/brunomellodasilva)
