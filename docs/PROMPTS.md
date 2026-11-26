# Receitas de prompt

**Ediçêo completa:** Use edit-video em [caminho]. Preserve os exemplos e as lições
centrais. Aperte as pausas, proponha cortes de erro, planeje o arco visual e construa um
rascunho HyperFrames em video-projects/[slug].

**Só erros:** Use cut-mistakes com [transcriçêo editada] e o [vídeo editado]
correspondente. Explique cada remoçêo proposta e preserve a ênfase intencional.

**Passada de história:** Use video-storytelling para planejar um mundo visual persistente para
[roteiro]. Marque o gancho, os loops abertos, o enquadramento de câmera, os callbacks e a recompensa.

**Motion graphics:** Use style-library e hyperframes-video-beats para selecionar
três overlays úteis para esta transcriçêo. Dê a cada um uma âncora literal e mantenha
quem fala legível. Siga o DESIGN.md do projeto.

**Showreel:** Use motion-showreel para construir um showreel de 15 segundos para [marca] a partir de
[música ou referência]. Meça a grade de tempos primeiro, mapeie seis ou sete capítulos para os
objetos da própria marca e me mostre o storyboard e a folha de tempos antes de construir.
Use música e SFX gratuitos ou meus; para o objeto herói, prefira minha assinatura Kling (CLI `kling`).

**Verificar:** Inspecione o MP4 renderizado de fato, seus quadros de transiçêo e suas junções
de áudio. Corrija os defeitos visíveis e escreva o VERIFY.md com evidências e limitações.

## Um reel com recompensa clara

> Use short-form-edit para criar um reel 9:16 a partir de [gravaçêo local]. Explore três
> direções de abertura e depois construa a promessa e a recompensa verdadeiras mais fortes. Mantenha
> as legendas palavra por palavra e escolha imagens em movimento para beats específicos da história. Me mostre
> a ediçêo bruta antes de polir. Salve o projeto e as evidências de revisêo juntos.

Veja [o passo a passo de vídeo curto](SHORT-FORM.md) para os arquivos de plano esperados e
os comandos dos validadores.

## Prompt ancorado na fala

> Edite [gravaçêo] com HyperFrames, limpo e envolvente. Transcreva primeiro para que cada
> elemento entre na palavra certa. Quando eu citar [A] e [B], mostre [A] onde eu aponto à
> esquerda e [B] à direita, com os logos animados e um card de vidro atrás para dar leitura.
> Quando eu disser "[frase da tese]", mostre as palavras embaixo, destacadas. Quando eu falar
> de B-roll, screenshots ou geraçêo de imagem, busque o material de verdade (grave a tela,
> tire o screenshot, gere a imagem) e mostre nas laterais. Verifique o render antes de entregar.

O método por trás desta receita está em [METODO.md](METODO.md).

## Uma gravaçêo, três estilos

**Quadro branco:** Edite [gravaçêo] com HyperFrames num estilo de quadro branco desenhado à
mêo, simples e amigável, como se explicasse para uma criança. Algumas cenas com o quadro em
tela cheia; outras com o quadro à esquerda e meu rosto à direita.

**Estilo curso:** Edite [gravaçêo] como aula. A câmera começa em tela cheia e depois fica
num recorte circular. Fundo minimalista, poucos tópicos grandes com as ideias principais, e
imagens geradas por IA muito simples para ilustrar os conceitos.

**Short dinâmico:** Transforme [gravaçêo] num short rápido e fácil de entender, com B-roll
variado ao fundo. Gere os assets que faltarem, respeitando a ordem de ferramentas do
[TOOLS-AND-API-KEYS.md](TOOLS-AND-API-KEYS.md).

## Sizzle reel de uma pasta de gravações

> Veja tudo em [pasta], transcreva as falas e monte um sizzle reel de [duraçêo] que conte a
> história do evento. Escolha momentos que mostrem a energia do público. Termine com a
> chamada para [próximo evento]. Me mostre a seleçêo de falas antes de montar.

## Vídeo de produto

> Faça um vídeo de [duraçêo] para [produto/marca] com imagens reais do catálogo. Onde faltar
> movimento, gere uma foto a partir do produto e um vídeo curto dessa foto (Kling pela minha
> assinatura). Energia alta, cortes no tempo da música, efeitos sonoros. Confirme antes de
> qualquer geraçêo que consuma créditos.

## Da referência à skill

> Analise [vídeo de referência] com `analyze-reference.mjs` e me diga por que ele funciona.
> Depois transforme essa análise numa skill em `.claude/skills/[nome]` e rode
> `npm run sync:skills`.

Depois de cada uso: "Nesta versêo gostei de [X] e nêo gostei de [Y]. Atualize a skill com
isso e rode de novo."
