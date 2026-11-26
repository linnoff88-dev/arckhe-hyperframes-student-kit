# HyperFrames Student Kit

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


**ê°Å¸â¡Â§ê°Å¸â¡Â· [PortuguêÂªs](README.md) êÂ· ê°Å¸â¡Âºê°Å¸â¡Â¸ [English](README.en.md) êÂ· ê°Å¸â¡Âªê°Å¸â¡Â¸ [EspaêÂ±ol](README.es.md)**

Kit reutilizêÂ¡vel de ediêÂ§êÂ£o de vêÂ­deo para **Codex e Claude Code**.
Traga sua prêÂ³pria gravaêÂ§êÂ£o. Corte o ar morto, revise os erros, planeje a histêÂ³ria e
construa motion graphics com HyperFrames e GSAP.

![Acabou. êâ° o fim de uma era: ediêÂ§êÂ£o complexa, horas de trabalho e softwares tradicionais dêÂ£o lugar ao agente](docs/images/capa-acabou.jpg)

## ê°Å¸ââ Guia de uso

Guia completo (landing + passo a passo): **https://linnoff88-dev.github.io/

**ComeêÂ§ando agora?** Leia o [guia rêÂ¡pido](docs/GUIA-RAPIDO.md): instalaêÂ§êÂ£o, abertura do
projeto no Codex ou no Claude Code, chave da ElevenLabs, o prompt do primeiro vêÂ­deo,
loop de feedback e como transformar o resultado em skill. A
[transcriêÂ§êÂ£o do tutorial em vêÂ­deo](docs/TRANSCRICAO-TUTORIAL.md) estêÂ¡ traduzida.

**O mêÂ©todo:** as cinco etapas (transcrever, cortar, planejar os beats, usar e criar skills,
verificar em ciclo), o prompt ancorado na fala, uma gravaêÂ§êÂ£o em trêÂªs estilos, sizzle de
pasta, vêÂ­deo de produto e o ciclo referêÂªncia ê¢â â skill estêÂ£o em [docs/METODO.md](docs/METODO.md)
e as receitas prontas em [docs/PROMPTS.md](docs/PROMPTS.md).

## Exemplos de vêÂ­deo curto

Os quadros abaixo sêÂ£o fotos simuladas de apresentador, usadas como referêÂªncia de enquadramento 9:16.

### Reel de curiosidade: destrave seu projeto

![Reel de curiosidade: destrave seu projeto](docs/images/exemplo-1.jpg)

### Reel de curiosidade: construa um sistema de IA melhor

![Reel de curiosidade: construa um sistema de IA melhor](docs/images/exemplo-2.jpg)

### AnêÂºncio ao vivo

![AnêÂºncio ao vivo](docs/images/exemplo-3.jpg)

## O que estêÂ¡ incluêÂ­do

- **15 skills**, espelhadas para os dois assistentes, com seus scripts auxiliares e referêÂªncias.
- **406 cards de motion graphics em rascunho** em dois estilos, com manifestos, tokens CSS e slots editêÂ¡veis.
- **Dois templates de cena:** papel quadriculado escuro e um popout de vidro êÂ  esquerda.
- Ferramentas de transcriêÂ§êÂ£o, corte de silêÂªncios, detecêÂ§êÂ£o de erros, renderizaêÂ§êÂ£o dos cortes revisados,
  retemporizaêÂ§êÂ£o de transcriêÂ§êÂ£o, revisêÂ£o de EDL, validaêÂ§êÂ£o de sincronia de beats e preflight.
- **EdiêÂ§êÂ£o de vêÂ­deo curto:** reels, YouTube Shorts, planejamento de gancho e recompensa, legendas precisas, B-roll em movimento e revisêÂ£o de êÂ¡udio.
- **12 projetos de ensino existentes**, preservados do kit original (ficam sêÂ³ na cêÂ³pia local; `video-projects/` nêÂ£o êÂ© versionado neste repositêÂ³rio).
- Uma composiêÂ§êÂ£o inicial sintêÂ©tica e uma fixture de ediêÂ§êÂ£o que nêÂ£o precisam de gravaêÂ§êÂ£o nem de chave de API.

## Ferramentas e serviêÂ§os opcionais

**O kit usa ElevenLabs Scribe por padrêÂ£o para transcrever e Kie.ai para gerar vêÂ­deos e
imagens.** Traga suas prêÂ³prias chaves de API e crêÂ©ditos ao usar esses serviêÂ§os.
VocêÂª pode pedir ao assistente para usar OpenAI Whisper ou Whisper local, ou
fornecer uma transcriêÂ§êÂ£o existente com marcaêÂ§êÂ£o por palavra. Os assets gerados sêÂ£o opcionais.

O starter local nêÂ£o precisa de nenhuma API paga de transcriêÂ§êÂ£o ou geraêÂ§êÂ£o. Veja o
[guia de ferramentas, contas e chaves de API](docs/TOOLS-AND-API-KEYS.md) para as ferramentas obrigatêÂ³rias,
serviêÂ§os opcionais, detalhes de configuraêÂ§êÂ£o e prompts que vocêÂª pode copiar.

## InstalaêÂ§êÂ£o

Instale Node.js **22 ou mais recente**, Git, FFmpeg (incluindo ffprobe) e Chrome ou
Chromium. Deixe `node`, `ffmpeg` e `ffprobe` disponêÂ­veis no seu terminal.
Depois rode estes comandos no PowerShell, no Terminal do macOS ou em um shell Linux:

```sh
git clone https://github.com/linnoff88-dev/hyperframes-student-kit.git
cd hyperframes-student-kit
npm ci
npm run setup
npm test
```

O setup verifica as ferramentas e cria o `.env` apenas se ele nêÂ£o existir. Adicione sêÂ³ as chaves
dos serviêÂ§os que vocêÂª escolher. O auxiliar de transcriêÂ§êÂ£o incluêÂ­do usa ElevenLabs;
as integraêÂ§êÂµes com Whisper e Kie.ai precisam da configuraêÂ§êÂ£o descrita no
[guia de ferramentas](docs/TOOLS-AND-API-KEYS.md). [ConfiguraêÂ§êÂ£o e soluêÂ§êÂ£o de problemas](docs/SETUP.md).

## Renderize seu primeiro exemplo

```sh
npm run demo
cd video-projects/demo
npx hyperframes lint
npx hyperframes preview
```

Percorra a animaêÂ§êÂ£o de oito segundos no Studio. Depois de revisêÂ¡-la, interrompa o preview
com Ctrl+C e renderize:

```sh
npx hyperframes render --quality draft --output renders/demo.mp4
```

A demo usa GSAP local. O HyperFrames pode baixar e armazenar em cache suas substituiêÂ§êÂµes de fontes na primeira renderizaêÂ§êÂ£o. Ela nêÂ£o tem narraêÂ§êÂ£o. A
[transcriêÂ§êÂ£o sintêÂ©tica](examples/editing/source.json) separada exercita as ferramentas de corte;
sêÂ£o dados de teste fictêÂ­cios, nêÂ£o uma transcriêÂ§êÂ£o da animaêÂ§êÂ£o de têÂ­tulo.

## Edite sua gravaêÂ§êÂ£o

Abra a pasta deste repositêÂ³rio no Codex ou no Claude Code e diga:

> Use edit-video para editar minha gravaêÂ§êÂ£o em [caminho local]. Mantenha meus exemplos e as
> liêÂ§êÂµes centrais. Aperte o ar morto, me mostre os cortes de erro propostos e use o estilo de
> papel quadriculado escuro com cards de vidro ocasionais. Produza um rascunho revisado.

Codex: `$edit-video`. Claude Code: `/edit-video`. Para uma êÂºnica operaêÂ§êÂ£o use
`cut-silences`, `cut-mistakes`, `video-storytelling` ou `style-library`.
Veja o [fluxo passo a passo](docs/WORKFLOW.md), as [receitas de prompt](docs/PROMPTS.md)
e o [caderno de storytelling](docs/STORYTELLING-WORKBOOK.md).

## Crie um reel ou YouTube Short

> Use short-form-edit para transformar minha gravaêÂ§êÂ£o em [caminho local] em um reel 9:16.
> Construa um gancho e uma recompensa verdadeiros, preserve meu sentido, aperte os erros e
> adicione legendas precisas, imagens em movimento com propêÂ³sito e design de som. Prepare
> um rascunho para revisêÂ£o. Use minha gravaêÂ§êÂ£o existente antes de propor assets gerados.

Codex: `$short-form-edit`. Claude Code: `/short-form-edit`.
A skill inclui referêÂªncias de planejamento e validadores para timing de legendas, mapeamento
de fontes, cobertura de cenas e reuso de imagens. êâ° um fluxo guiado por agente;
revise o movimento e o êÂ¡udio reais antes de publicar.
[Passo a passo de vêÂ­deo curto e comandos de validaêÂ§êÂ£o](docs/SHORT-FORM.md).

## Crie um showreel de motion design

> Use motion-showreel para criar um showreel de 15 segundos para [marca]. Estude meu reel
> de referêÂªncia em [caminho local], se eu der um. Escolha um motivo que se transforme em
> todos os capêÂ­tulos, corte na grade de tempos da mêÂºsica e termine no logo. Me mostre o
> storyboard e a folha de tempos antes de construir, e confirme antes de qualquer geraêÂ§êÂ£o paga.

Codex: `$motion-showreel`. Claude Code: `/motion-showreel`.
A skill inclui a anêÂ¡lise medida do reel que a originou, uma biblioteca de têÂ©cnicas por
capêÂ­tulo, um template de HUD e ferramentas Node para analisar um vêÂ­deo de referêÂªncia,
medir a grade de tempos de uma mêÂºsica, emendêÂ¡-la na grade de cortes e prêÂ©-mixar efeitos
sonoros. MêÂºsica e SFX podem ser gratuitos; para o objeto herêÂ³i, prefira sua assinatura
Kling AI (CLI `kling`). Kie.ai e ElevenLabs ficam como alternativas pagas opcionais.

## Exemplos existentes e migraêÂ§êÂ£o

Este êÂ© o repositêÂ³rio principal do student kit. O kit de pipeline de vêÂ­deo mais novo foi
mesclado aqui com os dois histêÂ³ricos Git preservados. Os 12 projetos originais continuam
em `video-projects/`, junto com os exemplos de marca compartilhados originais e as
skills `make-a-video`, `short-form-video` e `website-to-hyperframes`.
Use `short-form-edit` para reels novos; `short-form-video` documenta as composiêÂ§êÂµes mais antigas
dos Shorts de maio. [Notas de migraêÂ§êÂ£o e compatibilidade](docs/MIGRATION.md).

## Explore e personalize

| Recurso | Comece aqui |
| --- | --- |
| Guia rêÂ¡pido passo a passo | [docs/GUIA-RAPIDO.md](docs/GUIA-RAPIDO.md) |
| TranscriêÂ§êÂ£o do tutorial em vêÂ­deo | [docs/TRANSCRICAO-TUTORIAL.md](docs/TRANSCRICAO-TUTORIAL.md) |
| InstruêÂ§êÂµes compartilhadas dos agentes | [AGENTS.md](AGENTS.md) |
| VocabulêÂ¡rio de movimento e transiêÂ§êÂ£o | [MOTION_PHILOSOPHY.md](MOTION_PHILOSOPHY.md) |
| Biblioteca de cards e tokens de design | [Guia da biblioteca](style-library/GUIDE.md) |
| Metadados pesquisêÂ¡veis dos cards | [registry.json](style-library/registry.json) |
| Templates de cena completa | [Guia de templates](style-templates/README.md) |
| ConfiguraêÂ§êÂ£o e espelhamento do Codex | [.codex/README.md](.codex/README.md) |
| VerificaêÂ§êÂµes de release e limites | [VerificaêÂ§êÂ£o](docs/VERIFICATION.md) |
| Recursos de terceiros | [Avisos](THIRD_PARTY_NOTICES.md) |

Os cards sêÂ£o **assets de rascunho** reutilizêÂ¡veis. Teste os cards escolhidos com o seu texto
e a sua gravaêÂ§êÂ£o. Os templates da biblioteca podem carregar GSAP e Google Fonts de suas
CDNs pêÂºblicas; localize essas dependêÂªncias ao montar um projeto final.

As imagens de exemplo sêÂ£o fotos simuladas; nenhuma gravaêÂ§êÂ£o privada, transcriêÂ§êÂ£o, credencial
ou configuraêÂ§êÂ£o pessoal foi incluêÂ­da. Os exemplos jêÂ¡ pêÂºblicos anteriormente continuam no
repositêÂ³rio. Pastas novas em `video-projects/` e `raw-media/` sêÂ£o ignoradas automaticamente;
arquivos jêÂ¡ rastreados pelo Git continuam rastreados. Crie um projeto novo para a sua prêÂ³pria gravaêÂ§êÂ£o.

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>