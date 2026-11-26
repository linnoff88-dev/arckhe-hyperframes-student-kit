# Transcriçêo do tutorial: editando vídeos com IA e HyperFrames

> Traduçêo neutralizada de uma transcriçêo automática; nomes próprios do apresentador, comunidade e promoções foram removidos.

## Introduçêo e exemplos

Pare de dar prompts para o Claude. O Andrej Karpathy acha que existe um jeito muito melhor de trabalhar com IA. E o método dele tem três camadas. A camada um é a especificaçêo. Em vez de dar uma tarefa para o Claude e torcer para ele entender, trabalhe junto com ele para criar uma especificaçêo detalhada primeiro. Peça para o Claude te entrevistar sobre o que você realmente está tentando alcançar, e depois quebre o trabalho em checkpoints menores antes de ele começar.

Entêo, a Nvidia acabou de tornar construir com IA basicamente gratuito. Eles estêo dando aos desenvolvedores acesso gratuito via API a mais de 80 modelos de IA. É assim que você usa: vá no site da Nvidia, escolha o modelo que quiser e gere uma chave de API. Você pode escolher entre modelos como Kimi, GLM, DeepSeek e muitos outros. Entêo, você quer começar um negócio de verdade, mas ainda nêo consegue pagar pessoas para conteúdo, marketing, vendas e todos os outros tipos de trabalho? Porque agora você pode instalar agentes de IA de graça.

Um para ajudar a criar conteúdo, um para ajudar a fazer follow-up com leads, e outros tipos de agentes para cuidar das tarefas que os seus primeiros funcionários normalmente fariam por você. Nêo é loucura que, só com a minha linguagem natural, eu consiga ter todos esses motion graphics incríveis aqui, e todas essas animações insanas aqui também?

Eu posso ter legendas aparecendo embaixo, como você está vendo. Eu posso pegar o meu rosto e colocar no canto inferior direito, ou trazer para o canto superior esquerdo. E eu posso até reproduzir para vocês clipes de vários dos meus vídeos anteriores bem aqui, nesse estilo 3D. Entêo, até o final deste vídeo, você vai saber exatamente como fazer isso de verdade, mesmo que você nunca tenha usado o Codex antes ou nunca tenha editado vídeos.

Entêo eu nêo quero desperdiçar o tempo de nenhum de vocês. Vamos direto para o vídeo. Certo, espero que vocês estejam animados para aprender a fazer isso. O que você vai precisar é do aplicativo desktop do Codex e vai precisar instalar o HyperFrames. Mas eu vou mostrar tudo isso para vocês.

Antes de passarmos pela configuraçêo, eu só queria mostrar alguns exemplos de como eu tenho usado isso e das skills que eu vou disponibilizar para vocês gratuitamente. Esse primeiro exemplo é só ele me ajudando a editar vídeos longos, porque o que ele consegue fazer é transcrever o áudio e depois cortar erros, gaguejos, coisas desse tipo e, você sabe, espaços mortos.

Entêo, por exemplo, nesse aqui eu dei duas gravações diferentes. Eu dei a minha câmera de rosto e a minha gravaçêo de tela. E esse era um vídeo de 14 minutos que foi cortado para 9 minutos, e agora ele tem tipo o fundo e também tem alguns cortes. Deixa eu mostrar o que eu quero dizer com isso. Aqui está o vídeo.

Ainda nêo está publicado, mas é assim que ele começa: "Hoje eu vou passar pelos 18 conceitos centrais do Codex que você realmente precisa saber para começar a usar agora mesmo e extrair valor dele. Nêo importa se você nêo é nada técnico ou se nunca usou o Codex antes. Até o final deste vídeo você vai entender exatamente como essa coisa funciona de verdade, para poder começar a usar imediatamente."

Entêo, como você pode ver, aquela primeira animaçêo com os 18 cards entrando na tela foi o HyperFrames, com o Codex aqui conduzindo as edições em si, os crops arredondados, o fundo, tudo isso. E aí a parte um, onde vamos começar, sêo os fundamentos. Entêo vamos começar com o conceito número um, que sêo os projetos.

"Agora, imagino que muitos de vocês já usaram o ChatGPT ou o Claude..." — toda essa lógica foi, de novo, o HyperFrames. Ele basicamente criou o card que dizia "número um: projetos". Depois ele decidiu também dar um zoom em mim aqui, porque percebeu que nos próximos 10 a 15 segundos eu poderia estar falando de algo sem mostrar nada na tela.

Entêo, eu dei o prompt desse jeito e dei as skills desse jeito para ele entender que, quando nêo está acontecendo nada na tela, talvez você faça uma tela cheia, mas quando é hora de fazer algo mais tutorial, você volta para essa visualizaçêo. Enfim, ao longo de todo esse vídeo, é basicamente isso que ele faz.

Ele consegue alternar entre tela cheia e esse, digamos, template ou cena, e também cria aqueles cards entre cada um dos conceitos. Há uma espécie de tela de transiçêo. Certo, entêo esse é um exemplo rápido. Vamos dar uma olhada em conteúdo curto, que eu acho que está ficando muito, muito melhor. Aqui eu tenho ele fazendo dois reels.

## Reels de exemplo

Um é sobre o Claude e o outro é sobre a Nvidia. Deixa eu rodar rapidinho esses dois para vocês e depois a gente destrincha. "Pare de dar prompts para o Claude. O Andrej Karpathy acha que existe um jeito muito melhor de trabalhar com IA. E o método dele tem três camadas. A camada um é a especificaçêo. Em vez de dar uma tarefa para o Claude e torcer para ele entender, trabalhe junto com ele para criar uma especificaçêo detalhada primeiro.

Peça para o Claude te entrevistar sobre o que você realmente está tentando alcançar. Depois, quebre o trabalho em checkpoints menores antes de ele começar. A camada dois é o verificador. Antes de o Claude fazer qualquer coisa, defina exatamente como é um bom resultado. Depois dê a ele formas de realmente checar o próprio trabalho. Seja outro modelo de IA, dados reais ou testes que ele possa rodar sozinho. E a camada três é o ambiente.

Construa um espaço de trabalho onde o Claude já tenha as suas instruções, o seu conhecimento, as suas skills e as suas regras toda vez que você usá-lo. Entêo, em vez de ficar melhor em escrever prompts, você está construindo um sistema inteiro em torno do Claude que o torna melhor a cada uso."

[Chamada para comentar e receber um vídeo do autor sobre o método; texto promocional removido.] "Entêo, a Nvidia acabou de tornar construir com IA basicamente gratuito. Eles estêo dando aos desenvolvedores acesso gratuito via API a mais de 80 modelos de IA. É assim que você usa: vá no site da Nvidia, escolha o modelo que quiser e gere uma chave de API.

Você pode escolher entre modelos como Kimi, GLM, DeepSeek e muitos outros. Depois pegue essa chave e conecte direto no que você estiver construindo, para poder experimentar com apps de IA, automações e outros projetos sem acumular custos de API na hora. E como sêo APIs que seguem o mesmo formato da OpenAI, você pode usá-las com um monte de fluxos de trabalho de IA já existentes.

Se você queria começar a construir com IA, mas nêo queria queimar o seu próprio dinheiro testando modelos diferentes, isso torna tudo muito mais fácil." [Chamada para comentar e receber o passo a passo; texto promocional removido.] Entêo, eu achei que esses resultados ficaram muito, muito sólidos. Você pode ver que o que ele faz é começar com uma espécie de gancho visual. Acho que vamos para o do Claude primeiro.

Temos as três peças que faltam, e o que ele fez aqui é criar aquele loop aberto, porque está dizendo: "Ei, o Andrej Karpathy usa desse jeito", e cria esse loop aberto de "uau, eu preciso ficar até o final desse short para ver quais sêo as três". Porque, conforme avançamos, vemos que temos o número um.

Podemos falar um pouco do número um, e depois entramos no número dois, o verificador. E depois chegamos no número três finalmente, no final, que é sobre o ambiente. E entêo, mais ou menos a cada um ou dois segundos aqui, ele está trocando. Temos algumas cenas que sêo assim, com B-roll em cima e eu aqui embaixo.

Tem algumas que sêo animaçêo em tela cheia. Tem algumas que sou eu em tela cheia. E todas essas animações sêo meio que em estilo papel. Tem textura. É 3D. Estêo sempre se movendo. Entêo nunca temos um elemento parado. Você também deve ter notado que ele foi lá e buscou todo esse B-roll.

Ou ele criou, ou ele mesmo gravou. E as legendas foram feitas pelo HyperFrames e pelo Astra. A música, os efeitos sonoros, tudo isso está sendo sincronizado com o reel em si para engajamento. E praticamente a mesma coisa com o da Nvidia. Esse foi mais curto, mas é um estilo parecido. Esse tem mais acentos em verde em vez de laranja porque é sobre a Nvidia, mas tem os mesmos tipos de animaçêo.

Tem os mesmos tipos de cena, e tem o mesmo jeito acelerado. Está sempre trocando. Temos música. Temos B-roll real que ele foi lá e coletou sozinho. E aqui tem ainda mais B-roll gerado por IA que ele criou sozinho. Eu acho que isso está ficando muito, muito bom. E eu transformei isso em uma skill.

E como eu disse, todas essas sêo skills que vêm dentro de uma espécie de kit do estudante, é assim que eu estou chamando. [Trecho de divulgaçêo da comunidade do autor e de onde baixar o kit, removido.] Aqui vai mais um exemplo rápido. Esse é um reel de anúncio para um evento, e ele fez esse para mim tanto em 16:9 quanto em 9:16. Mas deixa eu rodar rapidinho a versêo 9:16 para vocês, porque é meio que um reel, mas é um pouco diferente, porque esse era para ser um anúncio.

[Exemplo de anúncio em 9:16 gerado pelo kit, sobre montar um time de agentes de IA antes de contratar pessoas; texto promocional removido.]

Agora, ele tem elementos parecidos, certo? Mas o que eu quero que você preste atençêo aqui é todo o B-roll que ele foi buscar no meu material. Ele pegou vídeos anteriores meus. Ele foi lá e pegou trechos de eventos ao vivo anteriores. Aqui tem um comigo e um convidado. Aqui tem uma sessêo fechada. Aqui tem um vídeo meu falando sobre o meu sistema operacional de IA e um segundo cérebro.

Entêo ele conseguiu usar o contexto do que o anúncio tratava. Aqui tem uma sessêo com outro convidado. Ele usou o contexto do que estávamos falando e colocou isso dentro, para que nêo pareça só teoria. Parece mais real. E até animou esse logo aqui no final, que eu achei simplesmente lindo, porque ele teve que ir até uma pasta local para encontrar o logo do evento.

E eu acho que isso ficou muito, muito bom. E vou rodar mais um para vocês rapidinho, que foi uma chamada para açêo que eu pedi ao Codex.

[Exemplo de vídeo de chamada para açêo gerado pelo kit, divulgando a comunidade do autor; texto promocional removido.]

Agora, o que eu gostei desse é que ele ficou muito limpo, certo? Nêo era super acelerado, super energético. Tem uma música baixa, mas, de novo, está provando para nós que ele consegue ir buscar screenshots, consegue recortá-los e consegue usar contexto sobre mim e sobre o meu negócio para fazer essas coisas parecerem mais relevantes.

Ele pegou todas essas skills e docs diferentes e colocou aqui de um jeito muito, muito bonito. Ele até foi lá e tirou screenshots de alguns dos nossos cursos. Ele pegou materiais de eventos, fotos e vídeos, e fez essa chamada para açêo parecer muito mais real, muito mais humana.

Entêo, se vocês estêo ficando animados com isso, [referência à comunidade do autor removida] peguem todas essas skills para poder replicar esse tipo de resultado. Mas agora, vamos realmente começar a construir isso. Tipo, como você realmente faz? E eu vou passar por um exemplo real com vocês.

## Configurando o projeto

Se vocês lembram da introduçêo deste vídeo, eu vou construir aquilo ao vivo agora com vocês. Entêo, a primeira coisa que eu quero que você faça é abrir um novo projeto. Eu simplesmente abriria uma nova pasta na sua área de trabalho ou algo assim. E vamos chamar essa aqui, por enquanto, de... eu vou chamar de hyperframes demo.

E esse é o projeto dentro do qual vamos trabalhar. Entêo eu tenho essa pasta na minha área de trabalho. Agora eu vou vir aqui no lado esquerdo e abrir um novo projeto. Eu vou escolher que isso seja um projeto local. Eu vou dar um nome. Entêo, HyperFrames demo. E depois eu vou escolher aquela pasta de fato, para que o Codex possa trabalhar dentro dela.

Entêo ela estava na minha área de trabalho e se chamava HyperFrames demo. Legal. Aí está o projeto. Eu vou selecionar e abrir. Entêo, quando você abre um chat novo nesse projeto, nêo vai ter nada aqui. Se eu vier aqui e for nos meus arquivos, literalmente nêo tem nada, mas vamos começar a preencher isso com coisas como projetos de vídeo, renders diferentes, arquivos diferentes e coisas assim.

Entêo, a primeira coisa que eu quero que você faça é ir até este repositório do GitHub. E ele se chama HyperFrames. Você vai basicamente só copiar essa URL do repositório do HyperFrames no GitHub. Você vai abrir o Codex, colar lá dentro e basicamente só dizer: "Ei, Codex, eu preciso que você puxe esse repositório do HyperFrames para que eu possa usá-lo para você editar vídeos para mim e tal.

Eu preciso que você garanta que todas as dependências estejam instaladas e tudo mais, e, sabe, traga algumas skills ou coisas de que você precisa dentro desse projeto do Codex para que isso realmente seja útil." Entêo, esse é o primeiro passo. Você vai mandar isso. Agora, enquanto isso está sendo configurado, deixa eu falar sobre a mentalidade e a ideia do que estamos realmente fazendo aqui quando editamos vídeos com IA.

## O fluxo: transcrever, cortar, planejar beats, gerar, verificar

Entêo, há alguns passos, certo? E nesse caso, eu estou usando o exemplo de que damos a ele algum tipo de filmagem e pedimos para editar e animar e coisas assim, mas ele também pode criar coisas do zero. Entêo, se você desse um esboço geral e quisesse só motion graphics, tipo sizzle reels ou demos de SaaS, ele conseguiria fazer isso, 100%.

Mas nêo é nisso que eu vou focar agora. Você só removeria esse primeiro passo. Entêo, basicamente, na minha cabeça, o passo um é: você tem a filmagem e o que precisa fazer é transcrever. E basicamente isso significa que ele precisa descobrir todo o texto que você está dizendo naquele clipe e exatamente quando isso acontece, o segundo exato, até o milissegundo, em que você diz certas palavras, para que ele possa sincronizar com animações diferentes e textos diferentes, como legendas, por exemplo.

Entêo, transcrever vem primeiro. Você pode fazer isso com uma coisa local e gratuita que ele pode configurar, chamada Whisper, mas eu na verdade gosto de usar a ElevenLabs para isso. Entêo eu vou mostrar como configurar isso também. Depois de transcrever, a próxima coisa que queremos fazer é provavelmente cortar. Basicamente, pedir para ele cortar erros, ou cinco segundos de silêncio e coisas assim. Entêo esse seria o passo dois.

O passo três, na minha cabeça, é planejar os beats. É meio que assim que ele chama: beats. Beats sêo basicamente cenas diferentes. Entêo, por exemplo, com esse reel, tipo esse slide da capacidade de instalar, isso é um beat, e depois isso é um beat, e isso é um beat. Basicamente, cada cena é um beat diferente.

Entêo, o que a gente gosta de fazer é pedir para o Astra, o modelo, ler o texto, entender a intençêo e começar a planejar os beats do que realmente vai entrar nesse reel ou nesse vídeo. E aí o que ele vai fazer é usar as skills dele, usar o HyperFrames e usar outras ferramentas como essa para de fato fazer a geraçêo do HTML.

Ele está basicamente só criando HTML e animando. E é isso que nos dá todos esses elementos 3D, e nos dá esse texto, e nos dá o que estamos basicamente olhando e considerando como motion graphics ou motion design. E, a propósito, parte de planejar os beats é entender que vai ter, sabe, música que vai sincronizar com isso, e efeitos sonoros, e tudo isso basicamente entra nesse elemento de planejamento.

E a questêo é que temos que ter transcrito e cortado tudo isso antes para poder fazer isso direito. E o último passo aqui é basicamente, honestamente, meio que um loop. O último passo é basicamente verificar, ou seja, fazer o agente assistir a tudo isso de novo. Ele vai assistir. Ele vai tirar screenshots.

Ele vai olhar a transcriçêo de novo. E basicamente o que queremos fazer é esse loop de verificar, depois voltar para aqui e usar as skills de novo, depois verificar, depois usar as skills de novo. Entêo entramos nesse loop, indo assim, até o agente estar confiante de que tudo está dentro dos limites, tudo sincroniza direito e tudo está com a sensaçêo que deveria. Entêo esse é mais ou menos o fluxo.

## Chave da ElevenLabs e o .env

Vamos de fato configurar. Entêo, agora estamos dentro desse projeto e ele ainda está configurando tudo. O que eu quero mostrar para fazer em seguida é a ElevenLabs para transcrever. Você vai abrir uma nova página. Vai abrir a ElevenLabs e criar uma conta, se ainda nêo tiver.

Você pode começar nisso com um plano de uns cinco dólares por mês, que vai durar um bom tempo. Entêo, você vai entrar aqui e o que vai fazer é ir no canto inferior esquerdo, em Developers, clicar em API keys bem aqui e criar uma nova chave.

Eu vou chamar essa de "Astra demo". Você pode deixar ela expirar. Pode simplesmente deixar em "nunca". E quanto a restringir a chave, se você quiser dizer "ok, essa chave vai literalmente só transcrever coisas", isso seria speech to text. Você pode dar acesso a speech to text. Se você também quiser dar acesso a efeitos sonoros, geraçêo de música e geraçêo de imagem e vídeo, pode dar acesso a outras coisas também.

Mas, por enquanto, eu vou começar só com speech to text, porque tudo de que realmente precisamos para esse endpoint é a transcriçêo. Entêo eu vou criar essa chave. Isso nos dá basicamente uma senha. Entêo nêo compartilhe isso com ninguém. E eu vou apagar essa assim que terminar de gravar. Entêo nem pense nisso.

Mas você vai copiar isso para a área de transferência. Vai entrar no Codex e depois vamos vir nos seus arquivos bem aqui. E você pode ver que agora ele está começando a criar algumas pastas e arquivos e coisas assim. E o que você precisa é de um arquivo chamado .env, que permite guardar segredos e senhas como a sua chave de API da ElevenLabs.

Entêo, tudo que você tem que fazer é mandar uma mensagem, mesmo enquanto ele está trabalhando aqui. E olha, ele na verdade abriu um localhost, que é meio que como conseguimos ver nossos projetos de vídeo. Isso só nos permite testar e olhar e até mover elementos e tal, o que é muito, muito legal.

Mas eu vou só fechar isso, porque era só um exemplo. O que eu posso fazer é dizer: quando você fizer as transcrições, eu quero que você use a ElevenLabs. Entêo, você pode criar para mim um lugar para a chave da ElevenLabs ali dentro? E também garanta que você coloque no AGENTS.md que, sempre que eu pedir para transcrever um vídeo, use a ElevenLabs para isso. Entêo, o AGENTS.md é este arquivo. Ele basicamente só explica como o projeto funciona. Entêo, neste momento, como nêo há muita informaçêo nele, ele só tem algumas coisas bem básicas do HyperFrames. Mas conforme você começa a aprender mais sobre o jeito que gosta de editar vídeos e o jeito que gosta de armazenar seus projetos, você vai querer vir aqui e atualizá-lo com certas informações.

Entêo, bem aqui você pode ver que ele diz: "Ok, eu vou adicionar essa regra no AGENTS.md para que, no futuro, eu pare a configuraçêo do Whisper", que é aquela coisa local de que eu falei. Agora, nêo há nada de errado com o Whisper, ele só é mais lento. E a ElevenLabs, sim, você tem que pagar, mas é muito mais rápida e eu gosto dessa velocidade, e nêo é têo cara.

Entêo agora o nosso .env tem um placeholder para a chave de API da ElevenLabs. O que você vai querer fazer é só colar a sua chave da ElevenLabs bem aqui dentro. E, a propósito, se ele nêo estiver deixando você colar ou digitar nada aqui, o que deveria funcionar, mas se nêo funcionar, você pode simplesmente vir aqui e clicar em "abrir no aplicativo padrêo".

E para mim isso abre no meu app de notas. Eu posso colar a chave de API. Salvar. E entêo, como você pode ver, ele vai atualizar ao vivo bem aqui dentro. Certo. Entêo, neste ponto, temos informaçêo suficiente aqui para realmente conseguir usar o HyperFrames. Eu nêo vou usar as minhas skills que mencionei, aquelas de todos aqueles exemplos que mostrei em que uso as minhas skills.

Eu nêo vou usá-las agora, porque eu só quero mostrar como isso fica na essência. Mas nêo esqueça que você pode definitivamente pegar essas skills e vir aqui para deixar essas coisas melhores. E entêo, uma coisa que você pode fazer é dar a ele um arquivo de vídeo e só dizer: "Ei, edita isso para mim.

Sabe, adicione motion graphics, faça contar uma história, blá blá blá." Ou você pode ser muito específico, que é o que eu vou fazer neste exemplo. Entêo deixa eu abrir o vídeo com o qual vamos trabalhar. Está bem aqui. Chama-se "edit intro". Deixa eu abrir e vamos dar uma olhada rápida.

"Isso é só a minha linguagem natural. Eu consigo ter todos esses motion graphics incríveis aqui. E todas essas animações insanas aqui também. Eu posso ter legendas aqui embaixo, como você está vendo. Eu posso pegar o meu rosto. Posso colocar no canto inferior direito." Ok. Enfim, agora você vê que eu estou basicamente planejando o que quero que aconteça enquanto acontece.

## O prompt de exemplo

Entêo, aqui está o que eu vou fazer. Eu vou pegar o caminho do arquivo do meu vídeo. Vou voltar para aqui. Vou fazer um prompt /goal para isso, o que basicamente significa que eu estou definindo um objetivo e ele vai continuar perseguindo até atingir esse objetivo. Vou colar o caminho do arquivo daquele vídeo e vou simplesmente começar a instruir o que eu quero que aconteça e quando quero que aconteça.

Mas primeiro, eu tenho que montar o loop de transcrever, cortar, planejar os beats, e depois ele vai começar a trabalhar. Mas, em vez de planejar os beats, eu estou meio que dirigindo isso um pouco mais. Entêo isso é meio que "planejar/aceitar beats". Enfim, deixa eu mostrar como isso vai ficar enquanto eu instruo essa coisa.

"Entêo, eu acabei de soltar um vídeo para você. Isso vai ser uma introduçêo. Eu preciso que você me ajude a transformar isso em um vídeo editado super premium e polido. A primeira coisa que você precisa fazer: eu quero que você transcreva o vídeo, porque precisamos que todos os beats e todos os motion graphics sincronizem exatamente com o momento em que eu digo as coisas.

E depois eu preciso que você corte qualquer coisa, se houver erros ou se houver silêncio. Nêo deveria realmente haver tipo um segundo ou meio segundo de silêncio. Eu quero que isso pareça acelerado. Depois de fazer essas duas coisas, é hora de começar a realmente animar este vídeo. Entêo, deixa eu dizer o que eu estou procurando quando se trata das animações.

Eu começo essa introduçêo dizendo algo como: 'Nêo é loucura que eu possa usar só a minha linguagem natural para ter todos esses motion graphics incríveis aqui e todas essas animações incríveis aqui?' O que eu quero que aconteça entêo é que toda a vibe deste vídeo seja muito, muito estilo motion design da Apple.

Entêo, tipo liquid glass, animações limpas, e que pareçam muito profissionais. Entêo, quando eu digo 'motion graphics aqui', eu acredito que a minha mêo estava apontando para o lado esquerdo da tela. Entêo, no terço esquerdo da tela, eu quero que eles venham de cima para baixo, como se as minhas mêos estivessem criando esses motion graphics.

Eu quero que eles entrem na tela, e faça-os contra algum tipo de card de liquid glass, onde vemos três tipos diferentes de motion graphics. Talvez tipo cards e documentos se movendo, ou telas de laptop e gráficos e elementos que estêo sendo animados e coisas assim. Só faça coisas aqui que sejam impressionantes e que contem uma história visual.

E depois, de forma parecida, quando eu entro nas 'animações insanas aqui também', isso é no lado direito da tela. Entêo a mesma coisa: eu quero que elas entrem de cima para baixo como se eu estivesse desenhando. Eu quero que essas sejam 3D. Entêo eu quero que fiquem contra algum tipo de, talvez, pequeno overlay no fundo, para que possamos vê-las contra o fundo, tipo um overlay escuro sutil.

E essas devem ser 3D. Entêo elas talvez devam parecer que estêo girando. Devem ter sombras. Devem ter profundidade. E essas podem ser tipo letras 3D ou animações 3D e, nêo sei, tipo símbolos que estêo se movendo. Só faça essas coisas, sabe, sutis e profissionais, mas elas certamente devem dar algum tipo de fator uau.

E para esses dois beats, eu quero que eles fiquem na tela enquanto eu estou falando deles. E depois eu quero que eles saiam da tela ou meio que desapareçam no mesmo momento. Entêo os motion graphics da esquerda entram primeiro, as animações da direita entram em segundo, e depois eles saem da tela ao mesmo tempo.

A próxima seçêo é bem simples. Quando eu digo 'eu posso ter legendas aparecendo embaixo, como você vê', eu só quero um overlay super, super limpo na parte de baixo da tela com legendas; elas nêo devem cobrir o meu rosto. Entêo, devem ficar mais ou menos perto do terço inferior. E se você puder deixar as palavras sutilmente destacadas, talvez as palavras sejam brancas, mas destacadas em azul quando eu estou realmente dizendo elas.

Entêo, garanta que estejam sincronizadas exatamente com a transcriçêo, quando eu estou dizendo elas. Agora, na próxima seçêo, eu continuo dizendo: 'eu posso pegar o meu rosto e mover para o canto inferior direito ou para o canto superior esquerdo'. E o que eu quero que você faça para isso é pegar a minha câmera de rosto e meio que encolher em um crop arredondado vertical.

Entêo você meio que só traz os lados esquerdo e direito para dentro, para me manter centralizado. E faz um crop arredondado com sombra projetada. E coloca contra este fundo, que é o fundo de tela cheia. E aqui o que eu estou fazendo é só colar esta imagem, que eu gosto de usar como meu fundo em alguns vídeos. E eu quero que você deixe esse fundo com 50% de opacidade, para ficar um pouco mais escuro.

E depois, para a próxima parte, quando eu digo 'eu posso reproduzir para vocês esses clipes dos meus vídeos anteriores', eu quero que você vá até o meu diretório local de vídeos, cujo caminho eu vou te dar também. Entêo eu vou só copiar esse caminho rapidinho, bem aqui. O que eu quero que você faça é só pegar alguns dos meus vídeos mais recentes, talvez tipo quatro ou seis, e eu quero que você meio que abra eles em leque, tipo animar o processo de você abrindo eles em leque, e que sejam 3D, com um pouco de sombra projetada, e eles ficam meio que girando e balançando para frente e para trás, só para criar um efeito bem legal. Mas eu quero que eles estejam realmente rodando o tempo todo. Eu nêo quero que sejam só imagens estáticas dos vídeos. Eu quero que você simplesmente reproduza, sabe, todos eles meio que rodando ao mesmo tempo.

E depois, para encerrar o vídeo, o que eu quero que você faça é basicamente, contra aquele fundo que eu te dei, se você puder trazer a minha câmera de rosto principal, meio que alinhar no lado esquerdo da tela, mas deixar maior, para que ela meio que toque o topo e a base da tela, mas ainda devemos ver o crop arredondado e a sombra projetada. E depois, no lado direito da tela, podemos ter só algum outro texto e outros motion graphics que contem uma história com base no que eu estou dizendo. Entêo tipo: 'você nêo precisa ser técnico, você nêo precisa ter usado o Codex antes, você nêo precisa ter experiência em ediçêo de vídeo'.

Se você puder só fazer pequenos ícones e animá-los de um jeito divertido para contar essa história. E depois, no final, sabe, diz tipo: 'Ei, eu nêo quero desperdiçar tempo. Vamos direto para o vídeo.' Faça exatamente a mesma coisa lá. E esse vai ser praticamente o fim dessa introduçêo.

Depois de ter feito tudo isso, eu só quero que você garanta que está bom. Eu quero que você meio que verifique tirando alguns screenshots e olhando, garantindo que os beats realmente sincronizam com o texto que eu estou falando, e garanta que tudo está dentro dos limites, tudo parece profissional e está transmitindo a qualidade que você quer que transmita.

Eu nêo estou procurando um protótipo ou uma versêo um. Eu estou procurando um produto acabado, pronto para ir." Fiquei um pouco sem fôlego. Entêo, esse foi um prompt gigante, certo? Fui eu sendo super, super específico sobre o que eu realmente estou procurando aqui. E é mais ou menos assim que isso começa. O jeito que eu cheguei a todas essas skills que agora uso para vídeos longos, aulas, reels, anúncios, é porque eu fiz isso muitas vezes.

E agora, se você consegue um resultado aqui de que gosta muito, muito, você diz: "Legal, isso foi incrível. Transforme isso em uma skill." E aí, na próxima vez, você nêo precisa dar um prompt têo grande. Você basicamente só diz: "Ei, edita esse vídeo. Usa essa skill." E depois, quando volta, se você tiver feedback, diz: "Ei, eu nêo gostei disso.

Garanta que você faça isso da próxima vez." E aí atualiza a skill também. Entêo, o que eu acabei de fazer é realmente o mais difícil que vai ser. E depois é sempre só uma questêo de iterar sobre essas skills. Entêo, eu vou simplesmente deixar isso cozinhar um pouco. Eu volto a falar com vocês quando isso retornar com a primeira versêo.

## Feedback e segunda versêo

E, com sorte, é o que você viu no começo deste vídeo. Ok. Entêo, eu ainda nêo assisti a isso, mas você pode ver que isso foi do original, que era, o que, um pouco mais de um minuto, um minuto e cinco segundos, para agora estar cortado em 28 segundos. Vamos assistir e ver como ficou.

"Nêo é loucura que, só com a minha linguagem natural, eu consiga ter todos esses motion graphics incríveis aqui? E todas essas animações insanas aqui também. Eu posso ter legendas aparecendo embaixo, como você está vendo. Eu posso pegar o meu rosto e colocar no canto inferior direito, ou trazer para o canto superior esquerdo.

Eu posso até reproduzir para vocês clipes de vários dos meus vídeos anteriores bem aqui, nesse estilo 3D. Entêo, até o final deste vídeo, você vai saber exatamente como fazer isso de verdade, mesmo que você nunca tenha usado o Codex antes ou nunca tenha editado vídeos. Entêo, eu nêo quero desperdiçar o tempo de nenhum de vocês.

Vamos direto para o vídeo." Ok, nada mal. Nada mal para uma primeira passada. Você pode ver como o meu prompt muito específico obviamente nos beneficiou aqui. Eu acho que esses ficaram bons, certo? Tipo, temos algumas animações 3D, temos alguns motion graphics. Eu gostei. Acho que é um bom jeito de começar. Eu acho que talvez precisemos de algo a mais nos primeiros dois segundos.

Sim, acho que devemos adicionar algo bem ali nos primeiros dois segundos, só para deixar mais envolvente. Mas a outra coisa que eu notei é bem aqui. Ele está reproduzindo vídeos, o que é bom, mas eles estêo meio que se sobrepondo uns aos outros, certo? Entêo nêo é realista. O que precisamos fazer é deixar isso mais convincente.

E também, eu quero deixar esse texto maior. Eu nêo acho que esse texto está grande o suficiente. E eu acho que isso está bom. Isso é tudo simples. Uma animaçêozinha legal também. Basicamente, esse é o meu feedback. Entêo, vamos disparar o prompt número dois. Eu vou fazer de novo outro prompt /goal. Ótimo.

"Entêo, quero dizer, isso levou 18 minutos. Foi uma primeira passada muito boa, mas vamos fazer outra versêo aqui. O que eu quero sêo algumas coisas. Primeiro de tudo, nos primeiros dois segundos, eu quero que você seja criativo aqui. Faça algo que pareça alinhado com a marca para deixar os primeiros dois segundos mais envolventes. Nêo tenho certeza se quero um corte para tela cheia, e nêo quero nada que fique por cima do meu rosto, mas, sabe, eu começo o vídeo com 'nêo é loucura que, só com a minha linguagem natural', algum tipo de animaçêo, algum tipo de motion graphic, deixe isso um pouco mais emocional. Só faça algo logo de cara para meio que fisgar o espectador.

Agora, além disso, as únicas outras mudanças de que preciso sêo na parte em que você mostra os meus vídeos, você mostra os quatro. Eu gosto de como eles parecem 3D e têm profundidade, mas se você puder deixar isso mais realista, porque eles claramente estêo meio que cortando uns através dos outros, quase como se nêo fosse realista.

Precisamos que isso seja mais... a física disso precisa parecer melhor. Entêo, se você puder talvez deixá-los mais grossos e garantir que estejam abertos em leque um atrás do outro, em vez de cortando uns através dos outros, seria ótimo. E depois o texto naquela tela, diz tipo 'seus vídeos' ou algo assim.

Se você puder só deixar isso maior, porque aquele texto estava bem pequeno. Eu quero que fique maior e mais fácil de ler. Mas, além disso, todo o resto eu achei que ficou muito bom, e combinou muito bem com a transcriçêo também. Entêo faça essas mudanças, por favor, e depois me avise quando terminar."

## Studio

Entêo esse é o prompt número dois indo como outro goal. Agora você pode ver que este é o Studio do HyperFrames que ele criou para nós. Isso está em 107. Vamos só resetar isso. E o legal é que eu posso literalmente mover coisas aqui. Entêo eu posso realmente pegar este elemento e aumentar o tamanho do texto aqui. Acho que "font", é aqui que eu faria isso.

Eu poderia mudar isso para, o que, tipo 80, e ver como fica. Entêo, ele recarregaria e agora eu posso simplesmente manipular essas coisas direto daqui, o que é bem legal. Sabe, você pode mover coisas, e pode ver que há até elementos diferentes para a cena 3D em si e para o vídeo dentro dela.

Entêo, eu nêo vou mexer nisso agora. Honestamente, eu nêo uso muito essa interface. Mas se você está editando um vídeo bem longo, digamos que seja um vídeo de 10 minutos, e só quer poder ajustar uma coisinha bem sutil, provavelmente é mais fácil vir aqui, fazer um pequeno ajuste, tipo só mover isso para o lado, e depois exportar, em vez de ter que passar pela camada de prompt de novo.

Entêo, é muito bom que o HyperFrames também te dê esse ambiente em localhost. Mas para algo têo simples quanto o que estamos fazendo, eu só queria disparar outro prompt em linguagem natural. Entêo, eu volto a falar com vocês quando esse tiver terminado. Certo, entêo isso levou 10 minutos agora e a V2 voltou. Deixa eu abrir em tela cheia e vamos assistir.

"Nêo é loucura que, só com a minha linguagem natural, eu consiga ter todos esses motion graphics incríveis aqui e todas essas animações insanas aqui também? Eu posso ter legendas aparecendo embaixo, como você está vendo. Eu posso pegar o meu rosto e colocar no canto inferior direito, ou trazer para o canto superior esquerdo, e eu posso até reproduzir para vocês clipes de vários dos meus vídeos anteriores bem aqui, nesse estilo 3D."

Ok, entêo isso ficou muito melhor. O texto ficou maior, e isso parece mais 3D, e também simplesmente, sabe, parece melhor. E bem aqui, essa é praticamente a única seçêo em que eu nêo disse exatamente o que queria. E foi isso que ele bolou. Honestamente, eu nêo amei.

Mas, por enquanto, eu vou só manter, porque eu disse a ele que nêo queria um corte para tela cheia, o que teria significado que ele criaria a própria animaçêo para ser a tela cheia. Mas, na verdade, vamos ver como ficaria se eu só disparasse esse prompt rápido e dissesse: "Ótimo. Agora, você pode criar mais uma versêo em que, nos primeiros dois segundos, antes de cortar para os motion graphics e tudo mais, vejamos como ficaria se você fizesse um corte para tela cheia?

Entêo, seria a tela cheia animada contra algum tipo de, sabe, fundo que pareça alinhado com a marca do resto da introduçêo, e talvez o texto entre de um jeito animado, dizendo 'Nêo é loucura?'." Enfim, só vou disparar isso. Isso realmente nêo deve demorar nada, mas só para mostrar a vocês que ele também pode fazer coisas como, sabe, um corte para tela cheia e animar desse jeito também.

Entêo eu mostro isso para vocês em um segundo. Certo, entêo esse voltou e está pronto. E eu tenho a sensaçêo de que vai ser basicamente super simples bem aqui. Vou reproduzir a partir dessa interface. "Nêo é loucura que, só com a minha linguagem natural, eu consiga ter todos esses motion graphics incríveis aqui e todas essas..." Legal.

Entêo, isso está ficando bom. Podemos ver que basicamente tudo que isso fez foi adicionar um texto animado bem simples que entrou aqui. Teve um pouco de camadas também, com esses pequenos cards com aparência de liquid glass, e manteve o fundo consistente com o que realmente usamos mais adiante, aqui.

## Encerramento

Entêo, eu achei isso bem bom. Enfim, pessoal, neste ponto, configuramos o projeto. Você configurou algo para transcrever, se decidiu usar a ElevenLabs, e agora você entende o loop pelo qual realmente passamos para fazer tudo isso. Eu nêo me aprofundei muito nessa interface em si e em como controlá-la, mas, como eu disse, é muito, muito intuitiva quando você entra, e é um toque bacana do HyperFrames.

[Trecho de divulgaçêo da comunidade do autor e de onde baixar o kit, removido.]

Mas, pessoal, é isso por hoje. Entêo, eu realmente espero que você tenha gostado do vídeo e aprendido algo novo. [Pedido de curtida e indicaçêo de outros vídeos do autor sobre Codex e GPT-6 Astra, removidos.] Obrigado por assistir até o final, e vejo você no próximo.
