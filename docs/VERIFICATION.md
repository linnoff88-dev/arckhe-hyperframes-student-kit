# Verificaçêo de release

## Student kit consolidado, versêo 2

- Todas as 14 skills canônicas passaram na validaçêo de frontmatter, e todos os 94
  recursos de skill batem com os espelhos do Codex. A verificaçêo de distribuiçêo
  reporta zero erros nos 406 cards e nas duas árvores de skills.
- Um `npm ci` limpo foi bem-sucedido. Todos os 11 testes de comportamento passaram,
  incluindo as novas verificações de drift de legenda, mapeamento de origem incorreto,
  cobertura de cena, reutilizaçêo de filmagem, linhas ausentes no ledger e hashes de
  filmagem alterados.
- O starter passou no preflight e no lint do HyperFrames com zero erros ou avisos.
- A verificaçêo de fumaça com mídia sintética passou de novo: saída de silêncios com
  3,960 segundos, saída limpa com 3,673 segundos contra um transcript de 3,660 segundos.
- Todos os arquivos originais de `video-projects/` e dos `assets/` da raiz foram mantidos
  sem alteraçêo. Nêo foram todos re-renderizados. Nenhum reel real ou geraçêo paga foi
  executado para esta migraçêo; a verificaçêo de short-form cobre seus validadores e o
  pacote de recursos.

## Evidência de release do pipeline original

A evidência de renderizaçêo a seguir vem do release do pipeline anterior a esta
mesclagem. Seu starter e sua implementaçêo de ediçêo foram mantidos.


Verificado localmente no Windows, em 8 de setembro de 2026, usando Node 24.15.0,
FFmpeg 8.1.1 e HyperFrames 0.7.109.

- A instalaçêo limpa de dependências foi bem-sucedida; o npm reportou zero vulnerabilidades conhecidas.
- `AGENTS.md` e `CLAUDE.md` da raiz batem. Dez pacotes de skills e todos os recursos
  de apoio batem com seus espelhos gerados para o Codex.
- A verificaçêo do kit valida a sintaxe JavaScript, o frontmatter das skills e os recursos
  vinculados, as contagens do registry, IDs únicos, slots declarados e dependências locais
  dos cards. Todos os 406 arquivos de card resolvem. Dois cards constroem alguns slots em
  JavaScript; as declarações no código-fonte deles sêo verificadas, nêo o DOM executado.
- Cinco testes de comportamento passam: retemporizaçêo de silêncios, remoçêo revisada de
  gagueira, comportamento de identidade com corte vazio, limites de corte inválidos e
  timing de beat adiantado/atrasado. A CLI aceita caminhos de projeto explícitos e ordem
  de atributos independente dos exemplos antigos.
- `npm run test:media` gerou um padrêo de teste de oito segundos com um tom senoidal,
  renderizou as duas etapas de ediçêo e montou o HTML de revisêo da EDL. A saída de
  silêncios teve 3,960 segundos; a saída limpa teve 3,673 segundos contra um transcript
  de 3,660 segundos. As durações de A/V diferem em menos de 0,04 segundo.
- O starter passou no preflight e no lint do HyperFrames com zero erros/avisos.
  O Studio carregou e reproduziu até oito segundos. A renderizaçêo de rascunho produziu
  240 quadros H.264 em 1920x1080 a 30fps. Os quadros extraídos foram inspecionados
  visualmente ao longo da sequência de oito segundos. Nenhum intervalo preto de 0,1
  segundo ou mais foi detectado.

## Escopo e limites

Este é um toolkit funcional, nêo uma promessa de julgamento editorial totalmente automático.
Os 406 cards da biblioteca mantêm status de rascunho; este release nêo renderizou nem
aprovou visualmente cada um deles individualmente. Teste cada card escolhido com a sua cópia.
O starter é só motion graphics, sem fala. O exercício de fumaça com mídia verifica timing
e integridade de stream com um tom, nêo a qualidade subjetiva do corte de fala.
A transcriçêo paga do Scribe nêo foi chamada durante o QA do release. Os templates exigem
adaptaçêo; o glass popout precisa da filmagem do aluno. O HyperFrames pode baixar
substituições de fonte na primeira renderizaçêo. As verificações multiplataforma rodam
no CI do GitHub; o QA local de mídia e renderizaçêo foi feito no Windows.

Repita: `npm ci`, `npm run check`, `npm test`, `npm run test:media`, depois crie um
novo projeto starter e faça lint, preview, renderizaçêo e inspeçêo da saída dele.
