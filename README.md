# Tech Daniels — site institucional

Site estático em HTML, CSS e JavaScript, sem dependências externas.

## Publicar no Cloudflare Pages via GitHub

1. Envie `index.html` para a raiz do repositório GitHub.
2. No Cloudflare, abra **Workers & Pages** → **Create application** → **Pages** → **Connect to Git**.
3. Selecione o repositório.
4. Configure:
   - Production branch: `main`
   - Framework preset: `None` (ou equivalente)
   - Build command: `exit 0` (ou deixe vazio se o painel permitir)
   - Build output directory: `/` (raiz do repositório)
5. Clique em **Save and Deploy**.

## Configurar o WhatsApp

Abra `index.html` e procure por:

`const WHATSAPP_NUMBER = "55DDDNÚMERO";`

Substitua pelo número oficial no formato internacional, somente números, incluindo 55 e DDD.
Exemplo fictício de formato: `5511999999999`. Não use esse exemplo como seu número.

## Antes de divulgar

- Teste o site em celular e computador.
- Configure o WhatsApp oficial.
- Substitua as imagens ilustrativas por fotos reais da empresa, se desejar.
- Atualize os textos de serviços, região de atendimento, Instagram e outras informações.
- Não publique informações de contato ou promessas que não correspondam à empresa.
