# Corpus Roda Viva

[![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/LeGOS-UFSCar/Roda-Viva/blob/main/README.md)
[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/LeGOS-UFSCar/Roda-Viva/blob/main/README.en.md)

## Sobre

The **corpus Roda Viva** consists of transcriptions of interviews conducted on the Roda Viva program from TV Cultura.

The interview transcriptions were extracted from the [Memória Roda Viva](https://rodaviva.fapesp.br/) and contain, in addition to the pure transcription, various journalistic insertions and rewritings. The **corpus Roda Viva** offers different versions of the transcriptions, each processed for distinct purposes. Although our ultimate goal is to establish a multimodal corpus with two subcorpora (one for speech and another for the transcription), at this moment, we are providing only the textual corpus. The textual corpus is available in three versions, described below.

### Version 0.1

Version 0.1 includes texts extracted directly from the Memória Roda Viva portal. These texts underwent a cleaning process where elements like links and icons present in the interviews were removed. The main objective was to meticulously preserve the textual content of the interviews, ensuring the closest retention of the original transcription.

### Version 0.2

In version 0.2, all textual insertions that were not present in the speakers' dialogue and had been added by the journalists transcribing the interviews were removed. The texts may still contain normalized speech, but the transcription format is closer to the program's audio.

### Version 0.2-String

For version 0.2-String, version 0.2 was processed by the Xerox Incremental Parser (XIP), adding lexical, syntactic (including dependency relations), and semantic information to the transcriptions. The resulting files can be processed as XML files.

### More information

[Roda Viva boundaries: an overview of an audio-transcription corpus](https://aclanthology.org/2024.propor-2.22/)

#### Citing

```bibtex
@inproceedings{de-miranda-jr-etal-2024-roda,
    title = "Roda Viva boundaries: an overview of an audio-transcription corpus",
    author = "de Miranda Jr., Isaac Souza and Wick-Pedro, Gabriela and de Barros, Cl{'a}udia Dias and Vale, Oto",
    editor = "Gamallo, Pablo and Claro, Daniela and Teixeira, Ant{'o}nio and Real, Livy and Garcia, Marcos and Oliveira, Hugo Gon{\c{c}}alo and Amaro, Raquel",
    booktitle = "Proceedings of the 16th International Conference on Computational Processing of Portuguese - Vol. 2",
    month = mar,
    year = "2024",
    address = "Santiago de Compostela, Galicia/Spain",
    publisher = "Association for Computational Lingustics",
    url = "https://aclanthology.org/2024.propor-2.22",
    pages = "165--169",
}
```
