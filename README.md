# french-asr-coreference
Data for the publication "[Impact of ASR Transcriptions on French Spoken Coreference Resolution](https://aclanthology.org/2025.crac-1.8/)"

This data is not a part of the official CorefUD releases.

If you use this data in your research, please cite the following publication:

```bibtex
@inproceedings{milintsevich-2025-impact,
    title = "Impact of {ASR} Transcriptions on {F}rench Spoken Coreference Resolution",
    author = "Milintsevich, Kirill",
    editor = "Ogrodniczuk, Maciej  and
      Novak, Michal  and
      Poesio, Massimo  and
      Pradhan, Sameer  and
      Ng, Vincent",
    booktitle = "Proceedings of the Eighth Workshop on Computational Models of Reference, Anaphora and Coreference",
    month = nov,
    year = "2025",
    address = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.crac-1.8/",
    doi = "10.18653/v1/2025.crac-1.8",
    pages = "85--94",
    abstract = "This study introduces a new ASR-transcribed coreference corpus for French and explores the transferability of coreference resolution models from human-transcribed to ASR-transcribed data. Given the challenges posed by differences in text characteristics and errors introduced by ASR systems, we evaluate model performance using newly constructed parallel human-ASR silver training and gold validation datasets. Our findings show a decline in performance on ASR data for models trained on manual transcriptions. However, combining silver ASR data with gold manual data enhances model robustness. Through detailed error analysis, we observe that models emphasizing recall are more resilient to ASR-induced errors compared to those focusing on precision. The resulting ASR corpus, along with all related materials, is freely available under the CC BY-NC-SA 4.0 license at: https://github.com/ina-foss/french-asr-coreference."
}
```

## License

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg