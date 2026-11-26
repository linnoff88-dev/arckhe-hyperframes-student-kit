# Storyboard: Showreel <Marca> <duraçêo>s

Grade: tempos de <período>s (<bpm> BPM medido), <fps>fps. `B(n) = n * <período>`. Folha de quadros: `qa/beatsheet.txt` (de `scripts/beatgrid.mjs`).
Motivo: <o elemento mais reduzido da marca>. Cor guardada do clímax: <cor, só na rajada>.

| Tempos | Tempo (s) | Rótulo HUD | Valor | Quadro | Overlay de ferramenta | Transformaçêo de entrada | Transformaçêo de saída | SFX |
|---|---|---|---|---|---|---|---|---|
| 0-4 | | 01 · <física> | tinta | o motivo entra e obedece à física | leitura ao vivo | (abertura) | motivo vira <laser / linha / flash> | pops nos contatos |
| 4-12 | | 02 · <tipografia> | papel, inversêo em B10 | frase da marca como tipografia cinética, 3 vozes, papel de parede | input nativo da marca (barra de busca, chat) ou caixa de seleçêo | flash vira papel | letras viram cópias do motivo | digitaçêo, clique, batida da inversêo |
| 12-16 | | 03 · <grade> | tinta | cópias do motivo viram uma grade de imagens reais da marca, onda, câmera inclina | leitura da grade | pontos viram blocos | push num bloco; vêo antes do drop | swishes, whoosh |
| 16-20 | | 04 · <partículas> | tinta + brilho do acento | o drop: explosêo em partículas que formam uma estatística verificada | leitura das partículas | bloco vira explosêo | partículas viram a silhueta do herói | boom, pop, ticks |
| 20-24 | | 05 · <lookdev> | tinta | objeto herói fotorrealista, dois materiais | leitura do material, contador | silhueta vira o objeto | push pela lente, corte seco | shimmer, whoosh |
| 24-28 | | 06 · <rajada> | alternado, cor guardada chega | 5-6 momentos de interface característicos, 1 tempo e depois meios tempos | a interface de cada momento | cortes secos | ruído | cliques, glitch, tape stop |
| 28-fim | | 07 · <fim> | tinta | logo se resolve, linha desenha, subtítulos digitados, o motivo pousa como elemento do próprio logo, slogan por último | cursor de digitaçêo | ruído se resolve | segurar | batida final, pop |

Checagens antes de construir:
- [ ] Congele qualquer quadro: ele se lê como a marca sem a HUD.
- [ ] Toda transiçêo transforma o objeto (exceto cortes da rajada).
- [ ] O valor inverte em toda troca de capítulo.
- [ ] Todo fato na tela está verificado e datado no BRAND.md.
