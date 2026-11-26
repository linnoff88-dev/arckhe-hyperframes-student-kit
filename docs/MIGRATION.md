# Student kit consolidado

O repositório original do student kit é o canônico. O kit reutilizável do
repositório video-pipeline foi mesclado nele, preservando os dois históricos
publicados e as estrelas e a URL do repositório original.

## O que foi adicionado

- Instruções do Codex, configurações de projeto e espelhos de skills gerados.
- Corte de silêncios e de erros, orquestraçêo da ediçêo completa, storytelling e ferramentas de beats.
- O novo fluxo `short-form-edit`, suas referências e os validadores de plano/filmagem.
- 406 cards em rascunho, dois templates de cena reutilizáveis, um starter sintético e testes.
- Configuraçêo, receitas de prompt, orientaçêo de verificaçêo e CI em Windows, macOS e Linux.

## O que permanece

Todos os 12 exemplos existentes em `video-projects/` e os `assets/` da raiz foram
mantidos sem modificaçêo. As três skills adicionais originais continuam disponíveis.
Novos reels vêo para `short-form-edit`; `short-form-video` é a referência legada do May Shorts.

O pacote mantém o comportamento CommonJS para os helpers `.js` mais antigos; as novas
ferramentas usam módulos `.mjs` explícitos. O HyperFrames está fixado no lockfile.
Os exemplos mais antigos nêo foram todos re-renderizados nessa versêo e podem precisar
de configuraçêo específica de assets, fontes, dependências ou API. A saída histórica
deles nêo é uma garantia de compatibilidade atual. Comece trabalhos novos com
`npm run new-video -- my-video`.

Novos projetos privados sêo ignorados pelo Git. Arquivos de ensino já rastreados
continuam rastreados apesar das regras de ignore, entêo evite colocar filmagem privada
nessas pastas. Nenhum histórico de workspace privado, gravaçêo bruta ou credencial foi importado.

A licença MIT original permanece. O material importado do pipeline mantém a permissêo
de uso incluída, e as licenças de terceiros continuam aplicáveis. Veja os
[avisos de recursos](../THIRD_PARTY_NOTICES.md).
