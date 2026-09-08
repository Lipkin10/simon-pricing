# simon-pricing

Skill de agente gerada a partir de *Confessions of the Pricing Man: How Price Affects Everything* (Hermann Simon, 2015) com o [book-to-skill](https://github.com/virgiliojr94/book-to-skill).

**O que é:** notas de estudo estruturadas — frameworks, regras de decisão, números e anti-padrões do autor — que um agente (Claude Code, Copilot CLI, Amp, Codex) carrega sob demanda. Não é o texto do livro: nada foi copiado; tudo é síntese. Use com o seu exemplar; não redistribua.

## Instalar

```bash
npx skills add https://github.com/Lipkin10/simon-pricing --skill simon-pricing
# ou, no Claude Code:
git clone https://github.com/Lipkin10/simon-pricing ~/.claude/skills/simon-pricing
```

Reinicie a sessão do agente depois de instalar.

## Usar

| Pergunta | O que acontece |
|---|---|
| `/simon-pricing` | carrega os 12 frameworks centrais |
| `/simon-pricing discounts` (ou `elasticity`, `bundling`, `freemium`, `price war`…) | lê o capítulo certo e responde a partir dele |
| `/simon-pricing ch07` | abre o capítulo 7 |
| `/simon-pricing audit <planilha, rate card ou proposta>` | roda o protocolo de auditoria: método, alavanca, descontos, pisos, estrutura, posicionamento, incentivos, erros catastróficos |

## Arquivos

| Arquivo | Conteúdo |
|---|---|
| `SKILL.md` | frameworks centrais, protocolo de auditoria, índice de capítulos e de tópicos |
| `chapters/ch01…ch10` | um arquivo por capítulo: frameworks, conceitos, números, exemplo trabalhado, anti-padrões |
| `cheatsheet.md` | regras "quando X, faça Y, porque Z", limiares e sinais de alerta — uma página |
| `patterns.md` | técnicas e estruturas de preço com quando usar, como e trade-offs |
| `glossary.md` | termos com referência ao capítulo |

Conteúdo em inglês (idioma do livro); esta documentação em português.

## Origem e limites

Gerado em 2026-09-08. Casos e cifras são os do autor (1990–2015, EUR/USD): ordens de grandeza, não benchmarks atuais. Para um mercado específico, combine com elasticidade medida e com os números do seu próprio caso.
