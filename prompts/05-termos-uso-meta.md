# Prompt para Terms of Service e Privacy Policy (Meta App)

Ao criar um app no Facebook Developers, voce precisa de URLs de Terms of Service e Privacy Policy. Use este prompt para gerar as paginas rapidamente.

---

## Gerar ambos os documentos

```
Preciso criar duas paginas simples para configurar meu app no Facebook Developers:

1. Terms of Service (Termos de Uso)
2. Privacy Policy (Politica de Privacidade)

O app se chama "[NOME DO SEU APP]" e e usado para:
- Acessar dados de campanhas de anuncios do Facebook/Instagram via Marketing API
- Gerar relatorios de performance de marketing
- Uso interno / para clientes de gestao de trafego

Gera dois arquivos HTML simples, profissionais e em ingles (requisito do Meta):
- terms-of-service.html
- privacy-policy.html

Cada arquivo deve:
- Ser standalone (abrir direto no navegador)
- Ter layout limpo e profissional
- Incluir as clausulas padrao necessarias para aprovacao do Meta
- Ter placeholders para [NOME DA EMPRESA] e [EMAIL DE CONTATO]
- Incluir data de "last updated"

Salva os dois arquivos neste projeto.
```

**Apos gerar:**
1. Substitua os placeholders pelo nome da sua empresa e email
2. Hospede as paginas em algum lugar publico:
   - **GitHub Pages** (gratis) — crie um repo, suba os HTMLs, ative Pages
   - **Google Sites** — crie uma pagina e cole o conteudo
   - **Notion** — crie uma pagina publica
   - **Qualquer hospedagem** — suba os arquivos
3. Cole as URLs no app do Meta (Settings > Basic > Terms of Service URL / Privacy Policy URL)

---

## Alternativa: pagina unica

```
Gera uma unica pagina HTML que contenha tanto os Terms of Service
quanto a Privacy Policy (em secoes separadas) para meu app do Meta.
App: "[NOME DO APP]". Uso: acessar Marketing API para relatorios.
Salva como legal.html.
```
