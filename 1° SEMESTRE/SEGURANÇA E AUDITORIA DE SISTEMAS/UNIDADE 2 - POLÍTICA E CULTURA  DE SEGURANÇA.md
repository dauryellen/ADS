# Unidade 2 - Políticas e Cultura de Segurança

Nesta nova etapa, vamos focar nos **aspectos não tecnológicos** e na **gestão** da segurança, tratando a proteção como uma integração entre **processos, pessoas e tecnologias**.

### O que você deve aprender primeiro?
O ponto de partida essencial é a **Política de Segurança da Informação (PSI)** e a **Cultura de Segurança**. Sem uma política clara e pessoas conscientizadas, qualquer tecnologia de ponta pode falhar, pois o fator humano é frequentemente o elo mais fraco.

---

### 1. Política de Segurança da Informação (PSI)
A PSI é um documento formal que define o "tom" da segurança na empresa, estabelecendo diretrizes, regras e responsabilidades para proteger os ativos.

*   **Conceito Prático:** Imagine o regimento interno de um condomínio. Ele define quem pode entrar, o que acontece se alguém quebrar uma regra e quem é responsável por cada área. A PSI faz o mesmo com os dados da empresa.
*   **Responsabilidade:** A segurança não é apenas do setor de TI, mas de **todos**. Para ser eficaz, a PSI deve ser apoiada pela alta direção e comunicada regularmente a todos os funcionários através de treinamentos e termos de ciência.

### 2. Sistema de Gestão de Segurança da Informação (SGSI)
Para organizar essas políticas, utiliza-se o SGSI, baseado principalmente na norma **ISO 27001**. O coração do SGSI é o ciclo de melhoria contínua **PDCA**:
*   **Plan (Planejar):** Estabelecer o sistema e os objetivos.
*   **Do (Executar):** Implementar e operar as políticas.
*   **Check (Verificar):** Monitorar e analisar o desempenho.
*   **Act (Agir):** Manter e melhorar continuamente o sistema.

### 3. Controle de Acesso e Autenticação (Tecnologia AAA)
Uma das partes mais críticas da gestão é garantir que apenas as pessoas certas acessem os dados certos. Isso é feito através do modelo **AAA**:
*   **Autenticação:** Verificar a identidade (ex: uso de **biometria** ou **2FA - Autenticação de dois fatores**).
*   **Autorização:** Definir o que o usuário pode fazer após entrar (ex: um estagiário pode ler um arquivo, mas não deletá-lo).
*   **Auditoria:** Registrar e monitorar as atividades para identificar comportamentos suspeitos.

### 4. O Ciclo de Vida e os Estados dos Dados
Os dados não são estáticos; eles existem em três estados principais que exigem proteções diferentes:
*   **Data-at-Rest (DAR):** Dados armazenados em discos ou nuvem. Protegem-se com criptografia de mídia física.
*   **Data-in-Motion (DIM):** Dados sendo transmitidos por redes. Protegem-se com protocolos como HTTPS.
*   **Data-in-Use (DIU):** Dados sendo processados pela memória ou aplicativos.

### 5. Técnicas de Proteção e Privacidade (LGPD)
De acordo com a **Lei Geral de Proteção de Dados (LGPD)**, as empresas devem proteger a privacidade dos indivíduos. Algumas técnicas incluem:
*   **Mascaramento:** Ocultar parte do dado na exibição. *Exemplo:* Ver apenas os últimos dígitos de um cartão de crédito (**12XX XXXX XX34**).
*   **Anonimização:** Processo onde um dado perde a possibilidade de ser associado a um indivíduo de forma irreversível.
*   **Pseudonimização:** O dado é descaracterizado, mas pode ser reidentificado se houver uma chave mantida em ambiente seguro.

### Resumo do Roteiro de Aprendizado:
1.  **Fundamentos de Gestão:** Estude a **ISO 27001** e o ciclo **PDCA**.
2.  **Cultura e Ética:** Entenda a importância da conscientização humana e da **PSI**.
3.  **Controle de Acesso:** Domine os conceitos de **AAA** e **IAM** (Gestão de Identidades).
4.  **Proteção de Dados:** Aprenda a diferenciar os estados dos dados e as técnicas de anonimização exigidas pela **LGPD**.
