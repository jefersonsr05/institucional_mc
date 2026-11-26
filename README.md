# institucional_mc

Site institucional da MC Sistemas: uma landing page estática, leve e sem build.

## Estrutura

- `index.html`: a página inteira (HTML, CSS e JS inline; imagens embutidas como WebP em base64).
- Página de suporte remoto: na mesma `index.html`, aberta pelo endereço `#suporte`.

## Como ver localmente

Abra `index.html` no navegador, ou sirva a pasta:

```bash
python3 -m http.server 8080
# http://localhost:8080
```

## Recursos

- Tema claro e escuro: segue o sistema por padrão; o botão no topo fixa a escolha no navegador.
- SEO: meta description, Open Graph e dados estruturados (`Organization`, schema.org).
- Responsivo, de 375 px a desktop.

## Pendências antes de publicar

- O formulário de contato ainda não envia mensagens (falta definir o destino: e-mail, API ou WhatsApp).
- O exemplo da API de classificação tributária no card de Reforma Tributária é ilustrativo.
- Nunca versionar `.env`, certificados ou chaves (ver `.gitignore`).
