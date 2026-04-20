# Auditoria de Sistemas e Segurança

Para começar sua jornada nesta unidade, o que você deve aprender primeiro são os **Fundamentos e Objetivos da Auditoria**, pois antes de usar ferramentas técnicas, você precisa entender o "porquê" e o "o que" está sendo inspecionado.

---

### 1. O que é Auditoria de Sistemas? (Do Zero)

A auditoria não é apenas uma "caça aos erros", mas uma **inspeção e verificação formal**. O objetivo é checar se os padrões estão sendo seguidos, se os registros estão corretos e se os sistemas são eficazes e eficientes.

- **Exemplo Prático:** Imagine que uma empresa tem uma regra (política) de que ninguém pode usar pen drives nos computadores. O auditor não vai apenas perguntar se as pessoas usam; ele vai testar os computadores, olhar os logs do sistema e verificar se essa regra está sendo cumprida na prática.

### 2. O Papel do Auditor

O auditor é um profissional **independente e imparcial** (geralmente certificado). Ele não deve estar envolvido na gestão do que está auditando para garantir que sua opinião seja objetiva e sem vieses.

### 3. As Três Fases do Processo

Uma auditoria não acontece ao acaso; ela segue um roteiro técnico rigoroso:

1.  **Planejamento:** Define-se o objeto (o que), o objetivo (por que) e o **escopo** (até onde vai a análise).
2.  **Trabalho em Campo (Execução):** É a hora da "mão na massa". O auditor adquire dados, testa os controles e documenta os resultados.
3.  **Relatórios:** Onde as descobertas são organizadas e entregues à alta gestão com recomendações de melhoria.

### 4. O que exatamente é auditado? (Controles)

Os auditores focam em diferentes tipos de controles para garantir a **Tríade CID** (Confidencialidade, Integridade e Disponibilidade):

- **Controles de Software de Sistema:** Verificação de atualizações do Windows/Linux e políticas de senhas.
- **Controles de Acesso:** Revisão de quem pode acessar o quê (biometria, tokens, senhas).
- **Controles Físicos:** Inspecionar se o Data Center está trancado, se há câmeras e se o acesso às instalações é restrito.
- **Controles de Desenvolvimento:** Avaliar se o código dos aplicativos foi revisado para evitar falhas como SQL Injection.

### 5. Técnicas e Ferramentas (Como o auditor trabalha)

O auditor usa três tipos principais de abordagens:

- **Interação com Pessoas:** Entrevistas e questionários para entender a rotina da empresa.
- **Análise Manual:** Revisão de documentos, políticas e análise de código-fonte.
- **Análise Técnica:** Uso de softwares especializados como o **Nmap** (para varredura de rede), **Wireshark** (para analisar tráfego) ou o **Nessus** (para achar vulnerabilidades).

### 6. Tendências: IoT e Auditoria Contínua

Hoje, a auditoria enfrenta novos desafios:

- **Ambientes de IoT:** Auditar dispositivos inteligentes (como câmeras e sensores) é complexo devido à diversidade de aparelhos e protocolos.
- **Auditoria Contínua:** Em vez de fazer uma auditoria uma vez por ano, as empresas usam ferramentas de análise de dados para monitorar os sistemas em **tempo real**.

---

### O que aprender primeiro? (Seu roteiro)

1.  **Conceitos de Auditoria e o papel do Auditor:** Entenda a diferença entre auditoria interna e externa e a importância da independência.
2.  **Fases da Auditoria:** Domine o fluxo Planejamento -> Campo -> Relatório.
3.  **Controles Físicos e Lógicos:** Saiba diferenciar e exemplificar cada um.
4.  **Técnicas de Coleta de Evidências:** Aprenda a importância de documentar tudo o que foi encontrado.

**Dica do Professor:** Lembre-se que o auditor não é um "inimigo" do TI. O objetivo final é assegurar aos investidores e clientes que a organização é **ética e operacionalmente estável**.
