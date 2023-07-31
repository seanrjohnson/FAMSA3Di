# FAMSA3Di

This is a modified version of FAMSA [https://github.com/refresh-bio/FAMSA](https://github.com/refresh-bio/FAMSA) where the only change is to replace the amino acid substitution matrix with the 3Di substitution matrix.

You can use it with the the `foldseek2fasta.py` script from esmologs (https://github.com/seanrjohnson/esmologs/tree/main/src/esmologs)[https://github.com/seanrjohnson/esmologs/tree/main/src/esmologs] to make 3Di MSAs.

# downloading and compiling

```bash
git clone git@github.com:seanrjohnson/FAMSA3Di.git
cd FAMSA3Di
make
```

This will create an executable called famsa3Di, which you can call directly, or copy into your $PATH.




## Citing
- FAMSA
[Deorowicz, S., Debudaj-Grabysz, A., Gudyś, A. (2016) FAMSA: Fast and accurate multiple sequence alignment of huge protein families. 
Scientific Reports, 6, 33964](https://www.nature.com/articles/srep33964)

- 3Di alphabet and subtitution matrix
[Kempen, Michel van, Stephanie S. Kim, Charlotte Tumescheit, Milot Mirdita, Jeongjae Lee, Cameron L. M. Gilchrist, Johannes Söding, and Martin Steinegger. “Fast and Accurate Protein Structure Search with Foldseek.” Nature Biotechnology, 2023, 1–4.](https://doi.org/10.1038/s41587-023-01773-0.)

