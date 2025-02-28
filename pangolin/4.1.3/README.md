# pangolin container

Main tool : [pangolin](https://github.com/cov-lineages/pangolin)

Full documentation: [https://cov-lineages.org/resources/pangolin.html](https://cov-lineages.org/resources/pangolin.html)

Phylogenetic Assignment of Named Global Outbreak LINeages

Additional tools:

- [pangolin-data](https://github.com/cov-lineages/pangolin-data) 1.15.1
- [pangolin-assignment](https://github.com/cov-lineages/pangolin-assignment)  1.15.1
- [minimap2](https://github.com/lh3/minimap2) 2.24-r1122
- [usher](https://github.com/yatisht/usher) 0.5.6
- [faToVcf](https://github.com/yatisht/usher) 426
- [scorpio](https://github.com/cov-lineages/scorpio) 0.3.17
- [constellations](https://github.com/cov-lineages/constellations) 0.1.10
- [gofasta](https://github.com/virus-evolution/gofasta) 1.1.0
- [mafft](https://mafft.cbrc.jp/alignment/software/) 7.508
- python 3.8.13

## Example Usage

```bash
# run Pangolin in the default mode (usher). Can optionally supply --analysis-mode usher
pangolin /pangolin/pangolin/test/test_seqs.fasta  -o /data/test_seqs-output-pusher

# run Pangolin in the fast/pangolearn mode. Can use either --analysis-mode fast or --analysis-mode pangolearn
pangolin /pangolin/pangolin/test/test_seqs.fasta --analysis-mode pangolearn -o /data/test_seqs-output-plearn
```
