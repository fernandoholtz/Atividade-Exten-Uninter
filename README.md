# 🔐 Conecta Seguro

Projeto educacional de **inclusão, conscientização e segurança digital** desenvolvido como atividade extensionista acadêmica, com aplicação voltada à comunidade escolar.

🌐 **Projeto publicado:**  
https://fernandoholtz.github.io/Atividade-Exten-Uninter/

---

## 📌 Sobre o projeto

O **Conecta Seguro** foi desenvolvido com o objetivo de aproximar conceitos de segurança digital da realidade cotidiana de estudantes, professores, familiares e demais integrantes da comunidade escolar.

A proposta combina:

- conscientização sobre golpes digitais;
- situações práticas do cotidiano;
- segurança no uso de QR Codes;
- phishing;
- golpes por WhatsApp;
- SMS fraudulentos;
- ligações falsas;
- boletos e PIX;
- falsas promoções;
- invasão de contas;
- autenticação em duas etapas;
- proteção de dados;
- quiz interativo;
- pesquisa anônima;
- análise dos resultados obtidos.

O projeto busca apresentar esses conteúdos em uma linguagem simples, acessível e interativa.

---

## 🎯 Objetivo

Promover conhecimento sobre riscos presentes no ambiente digital e incentivar comportamentos mais seguros no uso de celulares, redes sociais, aplicativos, mensagens, links e QR Codes.

Além do caráter educativo, o projeto permite a obtenção de **indicadores anônimos sobre experiências e conhecimentos relacionados a golpes digitais**.

---

## ⚡ Experiência com QR Code

Uma das estratégias do projeto é utilizar cartazes físicos contendo um QR Code.

Ao escanear o código, o participante acessa o site e recebe inicialmente uma mensagem de conscientização:

> **"Você acabou de confiar em um QR Code."**

O objetivo não é assustar o usuário, mas demonstrar como uma ação aparentemente simples pode representar um risco quando a origem de um QR Code, link ou página não é conhecida.

Após o alerta, o participante pode continuar normalmente para o conteúdo educacional.

---

## 🧠 Conteúdo abordado

O site apresenta exemplos e orientações relacionadas a diferentes tipos de ameaças digitais, entre elas:

### Phishing
Tentativas de obter informações pessoais utilizando páginas, mensagens ou links falsos.

### Smishing
Golpes realizados por mensagens SMS.

### Vishing
Tentativas de fraude realizadas por chamadas telefônicas.

### Golpe do falso familiar
Criminosos se passam por familiares ou pessoas conhecidas, principalmente pelo WhatsApp.

### Falsas compras e cartões
Sites, promoções ou contatos utilizados para obter dados financeiros.

### Boletos falsos

Manipulação ou substituição de dados de pagamento.

### QR Codes maliciosos

Códigos que podem direcionar usuários para páginas falsas ou ambientes fraudulentos.

### Falso suporte técnico

Criminosos se passam por empresas ou profissionais para obter acesso a contas ou dispositivos.

### Golpes envolvendo PIX

Solicitações falsas, engenharia social e transferências fraudulentas.

### Roubo ou invasão de contas

Orientações sobre proteção de contas, senhas e autenticação em duas etapas.

---

## 📝 Quiz interativo

O projeto possui um quiz baseado em situações práticas.

O participante deve analisar diferentes cenários e escolher como agiria diante da situação apresentada.

Ao final, o sistema calcula automaticamente o desempenho do participante.

Atualmente o quiz possui **8 situações relacionadas à segurança digital**.

---

## 📊 Pesquisa anônima

Além do conteúdo educacional, o site possui uma pesquisa para obtenção de indicadores sobre segurança digital.

Entre os dados analisados estão:

- contato anterior com tentativas de golpe;
- ocorrência de golpes;
- experiências de familiares ou pessoas próximas;
- tipos de golpes encontrados;
- meios utilizados pelos criminosos;
- ocorrência de prejuízo financeiro;
- utilização de autenticação em duas etapas;
- percepção de conhecimento antes da atividade;
- desempenho no quiz;
- percepção após a atividade;
- avaliação da utilidade do conteúdo.

---

## 🔒 Privacidade

A coleta foi estruturada para ser **anônima**.

O formulário não solicita:

- nome;
- CPF;
- telefone;
- endereço;
- matrícula;
- e-mail;
- turma;
- outro identificador pessoal obrigatório.

O participante também precisa concordar com a participação antes do envio das informações.

Os resultados são utilizados de forma agregada para fins educacionais e acadêmicos.

---

## 📈 Processamento dos dados

Quando o participante conclui a atividade:

1. o navegador prepara os dados;
2. o site envia as respostas para uma aplicação criada com **Google Apps Script**;
3. o Apps Script processa as informações;
4. as respostas são armazenadas em uma planilha Google Sheets;
5. uma área de resumo é atualizada automaticamente;
6. são calculados indicadores sobre as respostas recebidas.

A planilha utilizada para análise permanece com acesso restrito.

---

## 📊 Indicadores automáticos

O sistema gera automaticamente informações como:

- quantidade total de participantes;
- percentual que já recebeu tentativa de golpe;
- percentual que já foi vítima;
- utilização de autenticação em duas etapas;
- média de conhecimento antes da atividade;
- média do quiz;
- média de percepção depois da atividade;
- taxa de acerto de cada questão;
- principais tipos de golpes identificados;
- principais canais utilizados nos golpes.

---

## ♿ Acessibilidade

O projeto também considera recursos básicos de acessibilidade digital.

Entre eles:

- aumento do tamanho das fontes;
- modo de alto contraste;
- navegação responsiva;
- estrutura adequada para computadores e smartphones;
- preocupação com legibilidade e contraste;
- interface simplificada.

---

## 🌎 Objetivo de Desenvolvimento Sustentável

O projeto está relacionado principalmente ao:

### ODS 4 — Educação de Qualidade

A proposta busca ampliar o acesso ao conhecimento sobre segurança e cidadania digital, utilizando tecnologia como ferramenta educativa.

Também apresenta relação com inclusão digital e redução de vulnerabilidades provocadas pela falta de conhecimento tecnológico.

---

## 💻 Tecnologias utilizadas

O projeto foi desenvolvido utilizando:

- HTML5
- CSS3
- JavaScript
- Google Apps Script
- Google Sheets
- Git
- GitHub
- GitHub Pages
- Visual Studio Code

---

## 🏗️ Arquitetura simplificada

```text
Usuário
   ↓
QR Code
   ↓
GitHub Pages
   ↓
Site Conecta Seguro
   ↓
Conteúdo + Pesquisa + Quiz
   ↓
Google Apps Script
   ↓
Google Sheets
   ↓
Indicadores e análise dos resultados
