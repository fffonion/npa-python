# NPA extractor
Extraction Utility for Nitroplus N2System-based games.

Reimplementation of https://github.com/Wilhansen/nipa.

## Usage

Needs Python 3.x.

```
usage: npa.py [-h] -x file [-g ID] [-d codec] [-o dir] [-t]

NPA extractor

optional arguments:
  -h, --help  show this help message and exit
  -x file     The file to extract
  -g ID       Game ID
  -d codec    String codec, use cp936 for Chinese translated and cp932 for
              original
  -o dir      Output path
  -t          Test only, list files and exit
```

Game ID is a choice of:

    ChaosHead
    ChaosHeadTr1
    ChaosHeadTr2
    MuramasaTr
    Muramasa
    Sumaga
    Django
    DjangoTr
    Lamento
    LamentoTr
    sweetpool
    SumagaSP
    Demonbane
    MuramasaAD
    Axanael
    Kikokugai
    SonicomiTr2
    Sumaga3P
    Sonicomi
    LostX
    LostXTrailer
    DRAMAticalMurder
    Totono
    DRAMAticalMurderRC

## TODO

- Repack
