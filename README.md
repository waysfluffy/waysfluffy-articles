# WAYSFLUFFY — Artigos & Skills AI

Este repositório guarda os artigos e skills de IA voltados para **segurança ofensiva** que aparecem na página **Skills AI** da plataforma WAYSFLUFFY. Qualquer pessoa pode contribuir.

> Os artigos da pasta `SkillsAI/` são lidos automaticamente pelo app web (nome, categoria, conteúdo e imagens). Publicar = enviar um Pull Request.

---

## Como submeter um artigo

1. Faça um **fork** deste repositório
2. Crie seu arquivo `.md` dentro da pasta **`SkillsAI/`** seguindo a convenção de nome (abaixo)
3. Se tiver imagens, coloque em **`SkillsAI/images/`** e referencie com caminho relativo
4. Abra um **Pull Request** descrevendo a skill/artigo
5. O time WAYSFLUFFY revisa e, se aprovado, faz o merge — aí aparece no site

---

## Convenção de nome do arquivo

```
categoria_titulo-com-hifens.md
```

- Antes do `_` = **categoria** (usada no filtro do site)
- Depois do `_` = **título** (os hífens viram espaços)

**Exemplos:**

| Arquivo | Categoria | Título no site |
|---|---|---|
| `xss_bypass-de-waf-com-svg.md` | XSS | bypass de waf com svg |
| `ad_kerberoasting-na-pratica.md` | Active Directory | kerberoasting na pratica |
| `mcp_servidor-recon-automatizado.md` | MCP | servidor recon automatizado |
| `skill_enumeracao-de-subdominios.md` | Skill | enumeracao de subdominios |

Categorias sugeridas: `xss`, `sqli`, `ad`, `ssrf`, `lfi`, `rce`, `recon`, `priv`, `redteam`, `mcp`, `skill`, `insight`, `geral`.

---

## Estrutura recomendada do artigo (aumenta a chance de aceite)

Quanto mais completo, maior a chance de ser aceito. Recomendamos cobrir:

```markdown
# Título da skill

## Caso de uso
Um cenário real onde essa skill ajuda num pentest. Por que ela importa.

## O que é
Explicação do que a skill faz e como funciona por baixo.

## Instalação
Passo a passo para instalar/configurar (comandos, dependências).

## Como usar
Uso detalhado, passo a passo, com exemplos de input e output esperado.

## IA recomendada
Qual modelo de IA usar e **qual se sai melhor** na sua experiência
(ex: Claude Opus 4.x para raciocínio, modelo X para velocidade...).
Compare se testou mais de um.

## Dicas / pegadinhas
Limitações, erros comuns, como evitar problemas.
```

Não é obrigatório seguir exatamente, mas **artigos com caso de uso, instalação, uso detalhado e recomendação de IA têm prioridade no aceite.**

---

## Imagens

- Coloque os arquivos em **`SkillsAI/images/`**
- Referencie com **caminho relativo**:

```markdown
![descrição da imagem](images/minha-screenshot.png)
```

O app web carrega e exibe a imagem direto do repositório. Use imagens para mostrar telas, fluxos e resultados — ajuda muito a entender a skill.

Formatos: `.png`, `.jpg`, `.gif`, `.webp`.

---

## Markdown suportado pelo app

O app renderiza:
- Títulos (`#`, `##`, `###`...)
- **negrito**, *itálico*, `código inline`
- Blocos de código com ``` ``` ```
- Listas (`-`, `*`, `1.`)
- Links `[texto](https://...)`
- Imagens `![alt](images/...)`

**Importante (segurança):** HTML cru no artigo é **escapado** (não renderiza) e **JavaScript não executa**. Escreva em Markdown puro.

---

## Critérios de aceite

✅ Conteúdo original e técnico, voltado a segurança ofensiva
✅ Caso de uso real apresentado
✅ Instalação e uso detalhados
✅ Recomendação de IA (qual usar / qual se sai melhor)
✅ Nome do arquivo segue a convenção `categoria_titulo.md`
✅ Imagens (quando houver) em `images/` com caminho relativo

❌ Conteúdo sem contexto de uso, plágio, ou material ilegal/sem autorização

---

*Mantido pelo **team WAYSFLUFFY**. Dúvidas? Abra uma issue ou entre no [Discord](https://discord.gg/qREYjuwxgB).*
