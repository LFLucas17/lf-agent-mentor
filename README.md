# LF Agent Mentor — Plugin Claude

**Desenvolvido por Lucas Augusto | [LF Soft Soluções](https://lfsoftsolucoes.com.br)**

Plugin para Claude que transforma o assistente em um **mentor estratégico de criação de agentes Claude**. Ao instalar, o Claude passa a diagnosticar o contexto do usuário, ensinar o ecossistema (Skills, Plugins, Projects, Cowork) e guiar a criação de agentes personalizados passo a passo.

---

## O que este plugin faz

Quando instalado, o Claude passa a:

- **Diagnosticar** o perfil e objetivo do usuário antes de recomendar qualquer solução
- **Educar** sobre o ecossistema Claude (Skills, Plugins, Projects, Cowork, API) de forma contextualizada ao nível técnico de quem pergunta
- **Guiar a execução** — da ideia até o plugin publicado no GitHub
- **Adaptar o idioma** automaticamente (PT-BR, EN, etc.)
- **Agir como mentor**, não como executor — faz perguntas estratégicas, não entrega respostas genéricas

---

## Como instalar

### Opção 1 — Upload manual (Claude Desktop ou Cowork)

1. Baixe este repositório como ZIP (botão verde "Code" → "Download ZIP")
2. Abra o Claude Desktop ou Cowork
3. Vá em **Customize → Plugins → Upload**
4. Selecione o arquivo `.zip` ou a pasta extraída

### Opção 2 — Apontar o repositório GitHub (Claude Cowork, plano Teams/Enterprise)

1. Vá em **Organization Settings → Plugins → Add Plugin → GitHub**
2. Informe: `lucas-augusto/lf-agent-mentor` (ajuste para o seu usuário GitHub)
3. Clique em conectar — o plugin sincroniza automaticamente

---

## Como usar após instalar

Após instalar, basta conversar normalmente. O Claude acionará o mentor automaticamente quando detectar contextos como:

- "Quero criar um agente..."
- "Como faço um plugin para..."
- "Qual a diferença entre skill e projeto?"
- "Quero automatizar X com Claude..."
- "Estou perdido, por onde começo?"

Você também pode invocar diretamente digitando `/agent-mentor` no chat.

---

## Estrutura do plugin

```
lf-agent-mentor/
├── .claude-plugin/
│   └── plugin.json          ← manifest do plugin
├── skills/
│   └── agent-mentor/
│       └── SKILL.md         ← toda a lógica e metodologia do mentor
└── README.md                ← este arquivo
```

---

## Sobre

**Lucas Augusto** é desenvolvedor e fundador da LF Soft Soluções, especializado em desenvolvimento de sistemas, automação com IA e soluções de tecnologia personalizadas.

- 🌐 [lfsoftsolucoes.com.br](https://lfsoftsolucoes.com.br)
- 💼 [LinkedIn](https://linkedin.com/in/lucas-augusto-f17/)
