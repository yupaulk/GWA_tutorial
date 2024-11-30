Download PRSice-2 executable here: [https://choishingwan.github.io/PRSice/](https://choishingwan.github.io/PRSice/)

To run PRSice:
```
Rscript PRSice.R --dir . \
--prsice ./PRSice_linux \
--base TOY_BASE_GWAS.assoc  \
--target TOY_TARGET_DATA \
--thread 1  \
--stat OR \
--binary-target T
```