# Segurança na Internet, Dispositivos Móveis e Testes de Intrusão

Para começar sua jornada nesta etapa, o que você deve aprender primeiro é o conceito de **Segurança nas Transações Web e as Vulnerabilidades de Aplicações**, pois elas são a base dos ataques que vemos todos os dias.

---

### 1. O Ponto de Partida: Segurança na Internet

A segurança na internet envolve proteger o caminho que a informação percorre desde o seu dispositivo até o servidor final (como um banco ou loja virtual).

- **Vulnerabilidades Comuns (OWASP Top 10):** Você deve conhecer as falhas mais exploradas por invasores:
  - **Injeção de SQL (SQL Injection):** O invasor insere comandos maliciosos em campos de entrada (como um formulário de login) para manipular o banco de dados.
    - _Exemplo Prático:_ Em vez de digitar um nome, o hacker digita um comando que "pede" ao banco para mostrar todas as senhas dos usuários.
  - **Cross-Site Scripting (XSS):** Injeção de scripts maliciosos em páginas que outros usuários visitam.
    - _Exemplo Prático:_ Um cliente de uma loja online vê pop-ups suspeitos ao ler comentários de produtos porque alguém injetou um código malicioso naquela seção.
  - **Cross-Site Request Forgery (CSRF):** Induz o usuário a realizar ações não intencionais em uma aplicação onde ele já está autenticado.

### 2. Proteção para Dispositivos Móveis

Os smartphones expandem o "perímetro" das empresas, pois levamos dados corporativos para qualquer lugar, aumentando os riscos.

- **Principais Riscos:** Malware móvel, uso de redes Wi-Fi públicas inseguras, perda ou roubo do aparelho e o processo de _Jailbreaking/Rooting_ (que remove proteções do sistema).
- **Modelos de Gestão:**
  - **BYOD (Bring Your Own Device):** O funcionário usa seu próprio aparelho para trabalhar.
  - **COPE (Corporate-Owned, Personally-Enabled):** O aparelho é da empresa, mas permite uso pessoal.
- **Soluções de Defesa:** O uso de **MDM (Mobile Device Management)** e **EMM (Enterprise Mobility Management)** permite que a empresa controle senhas, criptografe dados e até apague o conteúdo do celular remotamente em caso de perda.

### 3. Engenharia Social: A Arte de Enganar

Diferente dos ataques técnicos, este foca em explorar a **psicologia humana** (medo, curiosidade, ganância) para obter dados.

- **Técnicas Comuns:**
  - **Phishing:** E-mails ou sites falsos que imitam instituições legítimas.
  - **Smishing:** Phishing via SMS.
  - **Vishing:** Ataques por chamadas de voz ou mensagens de voz falsas.
- **Como se proteger:** Educação dos usuários, uso de **2FA (Autenticação de Dois Fatores)** e desconfiança de solicitações urgentes de dados sensíveis.

### 4. Análise de Vulnerabilidades e Pentest (Teste de Intrusão)

É a prática de simular ataques reais de forma ética para encontrar falhas antes dos criminosos.

- **Tipos de Pentest:**
  - **Caixa Preta (Black-Box):** O testador não tem nenhuma informação prévia sobre o sistema (simula um hacker real).
  - **Caixa Branca (White-Box):** O testador tem acesso total ao código-fonte e diagramas (mais profundo e rápido).
  - **Caixa Cinza (Gray-Box):** Um meio-termo, onde se possui algumas informações, como uma credencial de usuário.
- **Métodos de Análise:**
  - **SAST (Estática):** Analisa o código-fonte sem executá-lo.
  - **DAST (Dinâmica):** Analisa o sistema em execução, detectando falhas sob o ponto de vista do usuário.

---

### O que aprender primeiro neste módulo? (Roteiro)

1.  **Vulnerabilidades Web (SQL Injection e XSS):** Entenda como os dados são manipulados na internet.
2.  **Tríade CID aplicada a Transações:** Como garantir que uma compra online seja confidencial, íntegra e esteja disponível.
3.  **Fundamentos de Engenharia Social:** Aprenda a reconhecer golpes de Phishing, pois eles são a porta de entrada para a maioria dos ataques.
4.  **Gestão de Dispositivos Móveis (MDM/EMM):** Entenda como as empresas protegem dados em celulares.

**Dica do Professor:** Comece explorando o **OWASP Top 10**. Ele é o "guia definitivo" do que há de mais crítico em segurança de aplicações hoje.
