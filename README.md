# AYA Activewear – loja online (demo)

Site estático: um `index.html` + pasta `img/`. Sem build, sem dependências.

## Publicar no GitHub + Vercel
1. Crie um repositório no GitHub e envie estes ficheiros (arraste a pasta para a página do repositório, ou `git init && git add . && git commit -m "AYA site" && git push`).
2. Em vercel.com → **Add New → Project** → escolha o repositório.
3. Framework Preset: **Other**. Deixe Build Command e Output Directory vazios. Clique **Deploy**.

## Onde editar
Tudo está em `index.html`, na secção `<script>`:
- `WA`, `PHONE`, `IG` – WhatsApp, número mostrado e Instagram.
- `SHIP_PROV` – taxa de envio para outras províncias.
- `SIZES` – tamanhos disponíveis.
- `PRODUCTS` – nome, preço, cores, fotos (`imgs`), descrição de cada peça.
- `POL` – textos das políticas (rascunhos a rever).
As fotos estão em `img/` com versões `-480` (telemóvel) e `-900` (ecrã grande).

## Notas
- A encomenda termina num link de WhatsApp com o resumo; não há pagamento online.
- O carrinho fica guardado no dispositivo da cliente (localStorage).
