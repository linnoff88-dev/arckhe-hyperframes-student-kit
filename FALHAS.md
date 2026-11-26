# FALHAS

| data | o que quebrou | menor correçêo | prompt \| infra |
| --- | --- | --- | --- |
| 2026-09-13 | flux2-klein com `-n 3 --seed 11` gerou 3 imagens idênticas (seed fixo repete a variaçêo) | omitir `--seed` ou passar seeds distintos por variaçêo; conferir md5 antes de usar | prompt |
