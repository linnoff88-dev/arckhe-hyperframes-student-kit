# Reels e YouTube Shorts

Use `short-form-edit` para uma gravaçêo bruta de apresentador, reel, YouTube Short ou
anúncio curto. O padrêo é 1080x1920. Peça uma versêo 1920x1080 composta separadamente
quando necessário; um recorte central nêo é uma segunda composiçêo.

## Início

Rode `npm run new-video -- my-reel` e entêo peça ao Codex (`$short-form-edit`) ou ao Claude
Code (`/short-form-edit`) para editar sua gravaçêo local dentro desse projeto. Informe
o público, a açêo pretendida, a duraçêo alvo e as preferências de marca.
O starter é horizontal; a skill precisa definir as dimensões da composiçêo, o layout
e os metadados do reel para 1080x1920 antes de escrever. Mantenha toda a gravaçêo de origem e
as saídas dentro do novo projeto.

1. Transcreva com ElevenLabs Scribe, com a alternativa que você escolher, ou reutilize marcações por palavra verificadas.
2. Revise os erros em contexto e estabeleça uma única lista de decisões de ediçêo alinhada a quadros.
3. Explore três direções de abertura e escolha uma promessa e uma recompensa verdadeiras.
4. Planeje cenas, legendas exatas, imagens em movimento e pistas sonoras em relaçêo às palavras mantidas.
5. Construa a composiçêo com as skills HyperFrames e GSAP. Use um livro-razêo de imagens
   para registrar a procedência e evitar o reuso nêo intencional da mesma cena de origem.
6. Valide, visualize, renderize um rascunho, inspecione quadros e ouça a ediçêo completa.
7. Resolva problemas de timing, áudio e composiçêo antes de exportar o vídeo final.

O kit usa ElevenLabs Scribe por padrêo para transcriçêo e Kie.ai para vídeos e imagens
gerados; traga suas próprias chaves e créditos para esses serviços. O Whisper
é uma alternativa de transcriçêo, e imagens existentes podem substituir assets gerados.
Veja [ferramentas, contas e chaves de API](TOOLS-AND-API-KEYS.md) para configuraçêo e prompts
copiáveis. Respeite a autorizaçêo já existente ao propor assets pagos. O exemplo sintético
de validaçêo nêo precisa de nenhum serviço pago.

## Valide a partir da raiz do repositório

```sh
npm run validate:short-form -- video-projects/my-reel
npm run validate:footage -- video-projects/my-reel
node scripts/preflight.mjs video-projects/my-reel
```

O primeiro validador lê `assets/plan.json`, `assets/transcript.json` e
`assets/edit-decisions.json`. O segundo lê o plano e, para imagens em movimento,
`assets/footage-ledger.json`, verifica hashes e confirma que os arquivos referenciados existem.
Siga o [esquema do plano](../.claude/skills/short-form-edit/references/plan-schema.md).
Use a [planilha de referência](../.claude/skills/short-form-edit/references/reference-analysis.md)
ao analisar um vídeo de referência fornecido.

Experimente a fixture sintética sem gravaçêo nem chave de API:

```sh
npm run validate:short-form -- examples/short-form
npm run validate:footage -- examples/short-form
npm test
```

A fixture contém palavras e dados de timing inventados, nêo um reel renderizado.
Os validadores verificam a estrutura e o timing declarado. Eles nêo provam um gancho
convincente, afirmações factuais, direitos sobre as imagens, recorte visual correto ou sincronia audível.
Os portões de qualidade da skill exigem assistir e ouvir a saída real.
