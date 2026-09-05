# Portfólio — Caroline Gonçalves

Site estático, sem build e sem dependência. São oito páginas HTML com o CSS embutido em cada uma.

- `index.html` / `index-en.html` — home em português e inglês
- `case-payments.html` / `-en` — central de operações de pagamento (Tempo)
- `case-lovable.html` / `-en` — construtor de templates (Tempo)
- `case-churn.html` / `-en` — estudo de churn (Qulture.Rocks)

## Identidade visual

| Papel | Hex | Uso |
|---|---|---|
| Creme | `#FBF3E4` | fundo base |
| Tinta | `#241E21` | texto |
| Cinza | `#4E4247` | texto secundário |
| Magenta | `#98145A` | acento (7,37:1 sobre creme, passa AAA) |
| Rosa | `#F7A8CD` | preenchimento apenas, nunca texto |

Tipografia: Anton nos títulos, Poppins no corpo, via Google Fonts.

**Rosa nunca é texto sobre creme.** O contraste é 1,66:1 e fica ilegível. Rosa só como fundo, etiqueta ou forma decorativa.

## Acessibilidade

Corpo em 18px, coluna de leitura em torno de 66 caracteres, foco de teclado visível, `prefers-reduced-motion` respeitado, link de pular para o conteúdo, e todo par de cor usado em texto passa WCAG AA.

Elementos decorativos (estrelas) ficam só no hero, na seção pessoal e no rodapé de contato. As seções de conteúdo não têm decoração de propósito.

## Rodar local

Não precisa de servidor. Abra o `index.html` no navegador. Se quiser servir por HTTP:

```bash
python3 -m http.server 8000
```

## Deploy

Vercel, importando este repositório. Sem framework, sem comando de build, diretório raiz.
