# Datasets for eSkip2

## Datasets 
The datasets will be uploaded after publication of the manuscript.

This repository contains a `datasets` directory with the following subfolders:

- **`train/{positive,negative}`**  
  Contains the training data used in the study, specifically ASO-related sequences.  
  Positive (exon skipping occurs) and negative (exon skipping does not occur) sequences are stored in separate directories.  
  For single nucleotide variants (SNVs), the raw data can be obtained from  
  [KosuriLab/MFASS](https://github.com/KosuriLab/MFASS/) at  
  `processed_data/snv/snv_data_clean.txt`.  
  Variant positions should be replaced with **N** according to the procedure described in the Methods section of the paper.  

- **`val/`**  
  Contains the labeled validation set used for model selection.  
  Labels are defined as:  
  - `1`: positive (exon skipping occurs)
  - `0`: negative (exon skipping does not occur) 

- **`test/`**  
  Contains the labeled test set used for model evaluation in the study.  
  Label definitions are the same as in the validation set.

## Gene-adaptation refinement example
This repository also provides example-ga-data.zip, which contains example training and test data for gene-adaptation refinement targeting DMD exon 46.

## License
- `datasets.zip` is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0).
- `example-ga-data.zip` is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

## Citation

```text
```bibtex
@article{chiba2026,
  title   = {eSkip2 prioritizes exon-skipping antisense oligonucleotide target regions across exon–intron contexts},
  author  = {Shuntaro Chiba, Katsuhiko Kunitake, Satomi Shirakaki, Umme Sabrina Haque, Harry Wilton-Clark, Md Nur Ahad Shah, Jamie Leckie, Kosuke Matsui, Fumie Uno-Ono, Toshifumi Yokota, Yoshitsugu Aoki, Yasushi Okuno},
  journal = {Preprint},
  year    = {2026}
}
```
