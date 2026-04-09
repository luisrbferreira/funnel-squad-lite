# Funnel Squad Lite

5 skills de IA para Claude Code que criam funis de vendas completos. Gratuito.

Cada skill executa um framework real da metodologia PSS (Perpétuo Sem Segredo), testada em +500 negócios com +R$24M em resultados.

---

## Os 5 Skills

| Comando | Skill | O que faz |
|---------|-------|-----------|
| `/fs-cliente` | Cliente Perfeito | Mapeia Dores, Dúvidas e Desejos do público |
| `/fs-oferta` | Oferta Mestra | Estrutura oferta completa (4 dimensões de valor) |
| `/fs-pagina` | Página de Vendas | Gera copy completa (17 seções) |
| `/fs-criativo` | Creative Strategist | Cria 5-10 copies de anúncio (22 ângulos) |
| `/fs-genesis` | Funil Gênesis | Monta perfil Instagram (bio + destaques + posts) |

## Pipeline

```
/fs-cliente → /fs-oferta → /fs-pagina → /fs-criativo → /fs-genesis
```

---

## Instalação

**Pré-requisito:** [Claude Code](https://docs.anthropic.com/en/docs/claude-code) instalado (CLI ou Desktop).

### Opção 1 — Claude Code Desktop (mais fácil)

Abra o Claude Code Desktop e cole esta mensagem:

> Clona o repositório https://github.com/luisrbferreira/funnel-squad-lite.git e copia as 5 pastas de skills (fs-cliente, fs-oferta, fs-pagina, fs-criativo, fs-genesis) para ~/.claude/skills/ — cada pasta tem um arquivo SKILL.md dentro. Depois confirma que instalou mostrando as 5 skills.

O Claude faz tudo sozinho. Só apertar Enter.

### Opção 2 — Terminal

```bash
# 1. Clone o repositório
git clone https://github.com/luisrbferreira/funnel-squad-lite.git

# 2. Copie as skills para o Claude Code
cp -r funnel-squad-lite/fs-* ~/.claude/skills/

# 3. Pronto. Use em qualquer projeto:
claude
/fs-cliente
```

### Opção 3 — Download direto

Baixe o ZIP: [funnel-squad-lite-main.zip](https://github.com/luisrbferreira/funnel-squad-lite/archive/refs/heads/main.zip)

Depois extraia e copie as 5 pastas `fs-*` para `~/.claude/skills/`.

---

## O sistema completo

Isso é uma amostra. O sistema completo tem **53 agentes em 10 squads**.

Na **Imersão Claude Funnels** você aprende a usar tudo ao vivo: [ia.outsiderschool.com.br](https://ia.outsiderschool.com.br/claude/v4)

---

Feito com Claude por Luis Ferreira e Bruno Gomes.
