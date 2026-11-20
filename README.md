# HyperFrames Student Kit

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


**ðŸ‡§ðŸ‡· [PortuguÃªs](README.md) Â· ðŸ‡ºðŸ‡¸ [English](README.en.md) Â· ðŸ‡ªðŸ‡¸ [EspaÃ±ol](README.es.md)**

Kit reutilizÃ¡vel de ediÃ§Ã£o de vÃ­deo para **Codex e Claude Code**.
Traga sua prÃ³pria gravaÃ§Ã£o. Corte o ar morto, revise os erros, planeje a histÃ³ria e
construa motion graphics com HyperFrames e GSAP.

![Acabou. Ã‰ o fim de uma era: ediÃ§Ã£o complexa, horas de trabalho e softwares tradicionais dÃ£o lugar ao agente](docs/images/capa-acabou.jpg)

## ðŸ“– Guia de uso

Guia completo (landing + passo a passo): **https://inematds.github.io/hyperframes-student-kit/guia/**

**ComeÃ§ando agora?** Leia o [guia rÃ¡pido](docs/GUIA-RAPIDO.md): instalaÃ§Ã£o, abertura do
projeto no Codex ou no Claude Code, chave da ElevenLabs, o prompt do primeiro vÃ­deo,
loop de feedback e como transformar o resultado em skill. A
[transcriÃ§Ã£o do tutorial em vÃ­deo](docs/TRANSCRICAO-TUTORIAL.md) estÃ¡ traduzida.

**O mÃ©todo:** as cinco etapas (transcrever, cortar, planejar os beats, usar e criar skills,
verificar em ciclo), o prompt ancorado na fala, uma gravaÃ§Ã£o em trÃªs estilos, sizzle de
pasta, vÃ­deo de produto e o ciclo referÃªncia â†’ skill estÃ£o em [docs/METODO.md](docs/METODO.md)
e as receitas prontas em [docs/PROMPTS.md](docs/PROMPTS.md).

## Exemplos de vÃ­deo curto

Os quadros abaixo sÃ£o fotos simuladas de apresentador, usadas como referÃªncia de enquadramento 9:16.

### Reel de curiosidade: destrave seu projeto

![Reel de curiosidade: destrave seu projeto](docs/images/exemplo-1.jpg)

### Reel de curiosidade: construa um sistema de IA melhor

![Reel de curiosidade: construa um sistema de IA melhor](docs/images/exemplo-2.jpg)

### AnÃºncio ao vivo

![AnÃºncio ao vivo](docs/images/exemplo-3.jpg)

## O que estÃ¡ incluÃ­do

- **15 skills**, espelhadas para os dois assistentes, com seus scripts auxiliares e referÃªncias.
- **406 cards de motion graphics em rascunho** em dois estilos, com manifestos, tokens CSS e slots editÃ¡veis.
- **Dois templates de cena:** papel quadriculado escuro e um popout de vidro Ã  esquerda.
- Ferramentas de transcriÃ§Ã£o, corte de silÃªncios, detecÃ§Ã£o de erros, renderizaÃ§Ã£o dos cortes revisados,
  retemporizaÃ§Ã£o de transcriÃ§Ã£o, revisÃ£o de EDL, validaÃ§Ã£o de sincronia de beats e preflight.
- **EdiÃ§Ã£o de vÃ­deo curto:** reels, YouTube Shorts, planejamento de gancho e recompensa, legendas precisas, B-roll em movimento e revisÃ£o de Ã¡udio.
- **12 projetos de ensino existentes**, preservados do kit original (ficam sÃ³ na cÃ³pia local; `video-projects/` nÃ£o Ã© versionado neste repositÃ³rio).
- Uma composiÃ§Ã£o inicial sintÃ©tica e uma fixture de ediÃ§Ã£o que nÃ£o precisam de gravaÃ§Ã£o nem de chave de API.

## Ferramentas e serviÃ§os opcionais

**O kit usa ElevenLabs Scribe por padrÃ£o para transcrever e Kie.ai para gerar vÃ­deos e
imagens.** Traga suas prÃ³prias chaves de API e crÃ©ditos ao usar esses serviÃ§os.
VocÃª pode pedir ao assistente para usar OpenAI Whisper ou Whisper local, ou
fornecer uma transcriÃ§Ã£o existente com marcaÃ§Ã£o por palavra. Os assets gerados sÃ£o opcionais.

O starter local nÃ£o precisa de nenhuma API paga de transcriÃ§Ã£o ou geraÃ§Ã£o. Veja o
[guia de ferramentas, contas e chaves de API](docs/TOOLS-AND-API-KEYS.md) para as ferramentas obrigatÃ³rias,
serviÃ§os opcionais, detalhes de configuraÃ§Ã£o e prompts que vocÃª pode copiar.

## InstalaÃ§Ã£o

Instale Node.js **22 ou mais recente**, Git, FFmpeg (incluindo ffprobe) e Chrome ou
Chromium. Deixe `node`, `ffmpeg` e `ffprobe` disponÃ­veis no seu terminal.
Depois rode estes comandos no PowerShell, no Terminal do macOS ou em um shell Linux:

```sh
git clone https://github.com/inematds/hyperframes-student-kit.git
cd hyperframes-student-kit
npm ci
npm run setup
npm test
```

O setup verifica as ferramentas e cria o `.env` apenas se ele nÃ£o existir. Adicione sÃ³ as chaves
dos serviÃ§os que vocÃª escolher. O auxiliar de transcriÃ§Ã£o incluÃ­do usa ElevenLabs;
as integraÃ§Ãµes com Whisper e Kie.ai precisam da configuraÃ§Ã£o descrita no
[guia de ferramentas](docs/TOOLS-AND-API-KEYS.md). [ConfiguraÃ§Ã£o e soluÃ§Ã£o de problemas](docs/SETUP.md).

## Renderize seu primeiro exemplo

```sh
npm run demo
cd video-projects/demo
npx hyperframes lint
npx hyperframes preview
```

Percorra a animaÃ§Ã£o de oito segundos no Studio. Depois de revisÃ¡-la, interrompa o preview
com Ctrl+C e renderize:

```sh
npx hyperframes render --quality draft --output renders/demo.mp4
```

A demo usa GSAP local. O HyperFrames pode baixar e armazenar em cache suas substituiÃ§Ãµes de fontes na primeira renderizaÃ§Ã£o. Ela nÃ£o tem narraÃ§Ã£o. A
[transcriÃ§Ã£o sintÃ©tica](examples/editing/source.json) separada exercita as ferramentas de corte;
sÃ£o dados de teste fictÃ­cios, nÃ£o uma transcriÃ§Ã£o da animaÃ§Ã£o de tÃ­tulo.

## Edite sua gravaÃ§Ã£o

Abra a pasta deste repositÃ³rio no Codex ou no Claude Code e diga:

> Use edit-video para editar minha gravaÃ§Ã£o em [caminho local]. Mantenha meus exemplos e as
> liÃ§Ãµes centrais. Aperte o ar morto, me mostre os cortes de erro propostos e use o estilo de
> papel quadriculado escuro com cards de vidro ocasionais. Produza um rascunho revisado.

Codex: `$edit-video`. Claude Code: `/edit-video`. Para uma Ãºnica operaÃ§Ã£o use
`cut-silences`, `cut-mistakes`, `video-storytelling` ou `style-library`.
Veja o [fluxo passo a passo](docs/WORKFLOW.md), as [receitas de prompt](docs/PROMPTS.md)
e o [caderno de storytelling](docs/STORYTELLING-WORKBOOK.md).

## Crie um reel ou YouTube Short

> Use short-form-edit para transformar minha gravaÃ§Ã£o em [caminho local] em um reel 9:16.
> Construa um gancho e uma recompensa verdadeiros, preserve meu sentido, aperte os erros e
> adicione legendas precisas, imagens em movimento com propÃ³sito e design de som. Prepare
> um rascunho para revisÃ£o. Use minha gravaÃ§Ã£o existente antes de propor assets gerados.

Codex: `$short-form-edit`. Claude Code: `/short-form-edit`.
A skill inclui referÃªncias de planejamento e validadores para timing de legendas, mapeamento
de fontes, cobertura de cenas e reuso de imagens. Ã‰ um fluxo guiado por agente;
revise o movimento e o Ã¡udio reais antes de publicar.
[Passo a passo de vÃ­deo curto e comandos de validaÃ§Ã£o](docs/SHORT-FORM.md).

## Crie um showreel de motion design

> Use motion-showreel para criar um showreel de 15 segundos para [marca]. Estude meu reel
> de referÃªncia em [caminho local], se eu der um. Escolha um motivo que se transforme em
> todos os capÃ­tulos, corte na grade de tempos da mÃºsica e termine no logo. Me mostre o
> storyboard e a folha de tempos antes de construir, e confirme antes de qualquer geraÃ§Ã£o paga.

Codex: `$motion-showreel`. Claude Code: `/motion-showreel`.
A skill inclui a anÃ¡lise medida do reel que a originou, uma biblioteca de tÃ©cnicas por
capÃ­tulo, um template de HUD e ferramentas Node para analisar um vÃ­deo de referÃªncia,
medir a grade de tempos de uma mÃºsica, emendÃ¡-la na grade de cortes e prÃ©-mixar efeitos
sonoros. MÃºsica e SFX podem ser gratuitos; para o objeto herÃ³i, prefira sua assinatura
Kling AI (CLI `kling`). Kie.ai e ElevenLabs ficam como alternativas pagas opcionais.

## Exemplos existentes e migraÃ§Ã£o

Este Ã© o repositÃ³rio principal do student kit. O kit de pipeline de vÃ­deo mais novo foi
mesclado aqui com os dois histÃ³ricos Git preservados. Os 12 projetos originais continuam
em `video-projects/`, junto com os exemplos de marca compartilhados originais e as
skills `make-a-video`, `short-form-video` e `website-to-hyperframes`.
Use `short-form-edit` para reels novos; `short-form-video` documenta as composiÃ§Ãµes mais antigas
dos Shorts de maio. [Notas de migraÃ§Ã£o e compatibilidade](docs/MIGRATION.md).

## Explore e personalize

| Recurso | Comece aqui |
| --- | --- |
| Guia rÃ¡pido passo a passo | [docs/GUIA-RAPIDO.md](docs/GUIA-RAPIDO.md) |
| TranscriÃ§Ã£o do tutorial em vÃ­deo | [docs/TRANSCRICAO-TUTORIAL.md](docs/TRANSCRICAO-TUTORIAL.md) |
| InstruÃ§Ãµes compartilhadas dos agentes | [AGENTS.md](AGENTS.md) |
| VocabulÃ¡rio de movimento e transiÃ§Ã£o | [MOTION_PHILOSOPHY.md](MOTION_PHILOSOPHY.md) |
| Biblioteca de cards e tokens de design | [Guia da biblioteca](style-library/GUIDE.md) |
| Metadados pesquisÃ¡veis dos cards | [registry.json](style-library/registry.json) |
| Templates de cena completa | [Guia de templates](style-templates/README.md) |
| ConfiguraÃ§Ã£o e espelhamento do Codex | [.codex/README.md](.codex/README.md) |
| VerificaÃ§Ãµes de release e limites | [VerificaÃ§Ã£o](docs/VERIFICATION.md) |
| Recursos de terceiros | [Avisos](THIRD_PARTY_NOTICES.md) |

Os cards sÃ£o **assets de rascunho** reutilizÃ¡veis. Teste os cards escolhidos com o seu texto
e a sua gravaÃ§Ã£o. Os templates da biblioteca podem carregar GSAP e Google Fonts de suas
CDNs pÃºblicas; localize essas dependÃªncias ao montar um projeto final.

As imagens de exemplo sÃ£o fotos simuladas; nenhuma gravaÃ§Ã£o privada, transcriÃ§Ã£o, credencial
ou configuraÃ§Ã£o pessoal foi incluÃ­da. Os exemplos jÃ¡ pÃºblicos anteriormente continuam no
repositÃ³rio. Pastas novas em `video-projects/` e `raw-media/` sÃ£o ignoradas automaticamente;
arquivos jÃ¡ rastreados pelo Git continuam rastreados. Crie um projeto novo para a sua prÃ³pria gravaÃ§Ã£o.

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>