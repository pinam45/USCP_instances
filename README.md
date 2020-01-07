# USCP_instances

This repository contain benchmark instances for the **Unicost Set Cover Problem**, some contains cost information for the **Set Cover Problem** and some are unicost.

These instances were gathered to be used with the solver from [USCP](https://github.com/pinam45/USCP). For each instances group, a comma separated list of instances names is given. This list can be used with the [USCP](https://github.com/pinam45/USCP) solver as command line parameter to solve the instances with the implemented algorithms.

All the instances are available online on a *source website*, this repository was created as a backup.

Information about (2018) state of the art problem preprocessing and solving approaches with the best know solutions for these instances can be found in [Kritter2019].

Comma separated list of instances names:
```
4.1,4.2,4.3,4.4,4.5,4.6,4.7,4.8,4.9,4.10,5.1,5.2,5.3,5.4,5.5,5.6,5.7,5.8,5.9,5.10,6.1,6.2,6.3,6.4,6.5,A.1,A.2,A.3,A.4,A.5,B.1,B.2,B.3,B.4,B.5,C.1,C.2,C.3,C.4,C.5,D.1,D.2,D.3,D.4,D.5,E.1,E.2,E.3,E.4,E.5,NRE.1,NRE.2,NRE.3,NRE.4,NRE.5,NRF.1,NRF.2,NRF.3,NRF.4,NRF.5,NRG.1,NRG.2,NRG.3,NRG.4,NRG.5,NRH.1,NRH.2,NRH.3,NRH.4,NRH.5,CLR10,CLR11,CLR12,CLR13,CYC6,CYC7,CYC8,CYC9,CYC10,CYC11,RAIL507,RAIL516,RAIL582,RAIL2536,RAIL2586,RAIL4284,RAIL4872,STS9,STS15,STS27,STS45,STS81,STS135,STS243,STS405,STS729,STS1215,STS2187
```

## OR-Library (87)

For more information about the instances and the files format, see the [source website](http://people.brunel.ac.uk/~mastjjb/jeb/orlib/scpinfo.html) and the related [README](OR-Library/README).

### base instances (70)

| Set | Instances | Rows | Columns | Density | Cost range |
|:----|:----------|:-----|:--------|:--------|:-----------|
| 4   | 10        | 200  | 1000    | 2%      | [1;100]    |
| 5   | 10        | 200  | 2000    | 2%      | [1;100]    |
| 6   | 5         | 200  | 1000    | 5%      | [1;100]    |
| A   | 5         | 300  | 3000    | 2%      | [1;100]    |
| B   | 5         | 300  | 3000    | 5%      | [1;100]    |
| C   | 5         | 400  | 4000    | 2%      | [1;100]    |
| D   | 5         | 400  | 4000    | 5%      | [1;100]    |
| E   | 5         | 50   | 500     | 20%     | [1;1]      |
| NRE | 5         | 500  | 5000    | 10%     | [1;100]    |
| NRF | 5         | 500  | 5000    | 20%     | [1;100]    |
| NRG | 5         | 1000 | 10000   | 2%      | [1;100]    |
| NRH | 5         | 1000 | 10000   | 5%      | [1;100]    |

Comma separated list of instances names:
```
4.1,4.2,4.3,4.4,4.5,4.6,4.7,4.8,4.9,4.10,5.1,5.2,5.3,5.4,5.5,5.6,5.7,5.8,5.9,5.10,6.1,6.2,6.3,6.4,6.5,A.1,A.2,A.3,A.4,A.5,B.1,B.2,B.3,B.4,B.5,C.1,C.2,C.3,C.4,C.5,D.1,D.2,D.3,D.4,D.5,E.1,E.2,E.3,E.4,E.5,NRE.1,NRE.2,NRE.3,NRE.4,NRE.5,NRF.1,NRF.2,NRF.3,NRF.4,NRF.5,NRG.1,NRG.2,NRG.3,NRG.4,NRG.5,NRH.1,NRH.2,NRH.3,NRH.4,NRH.5
```

### CYC CLR instances (10)

| Instance | Rows  | Columns | Density | Cost range |
|:---------|:------|:--------|:--------|:-----------|
| CYC6     | 240   | 192     | 2.1%    | [1;1]      |
| CYC7     | 672   | 448     | 0.9%    | [1;1]      |
| CYC8     | 1792  | 1024    | 0.4%    | [1;1]      |
| CYC9     | 4608  | 2304    | 0.2%    | [1;1]      |
| CYC10    | 11520 | 5120    | 0.1%    | [1;1]      |
| CYC11    | 28160 | 11264   | 0.04%   | [1;1]      |
| CLR10    | 511   | 210     | 12%     | [1;1]      |
| CLR11    | 1023  | 330     | 12%     | [1;1]      |
| CLR12    | 2047  | 495     | 12%     | [1;1]      |
| CLR13    | 4095  | 715     | 12%     | [1;1]      |

Comma separated list of instances names:
```
CLR10,CLR11,CLR12,CLR13,CYC6,CYC7,CYC8,CYC9,CYC10,CYC11
```

### RAIL instances (7)

| Instance | Rows | Columns | Density | Cost range |
|:---------|:-----|:--------|:--------|:-----------|
| RAIL507  | 507  | 63009   | 1.3%    | [1;2]      |
| RAIL516  | 516  | 47311   | 1.3%    | [1;2]      |
| RAIL582  | 582  | 55515   | 1.2%    | [1;2]      |
| RAIL2536 | 2536 | 1081841 | 0.4%    | [1;2]      |
| RAIL2586 | 2586 | 920683  | 0.3%    | [1;2]      |
| RAIL4284 | 4284 | 1092610 | 0.2%    | [1;2]      |
| RAIL4872 | 4872 | 968672  | 0.2%    | [1;2]      |

Comma separated list of instances names:
```
RAIL507,RAIL516,RAIL582,RAIL2536,RAIL2586,RAIL4284,RAIL4872
```

## Steiner triple covering problem (11)

For more information about the instances and the files format, see the [source website](http://mauricio.resende.info/data/index.html) (and [this website](http://www.co.mi.i.nagoya-u.ac.jp/~yagiura/scp/stcp/) for the 2 last instances) and the related [README](steiner-triple-covering/README).

### Instances (11)

| Instance | Rows   | Columns | Density | Cost range |
|:---------|:-------|:--------|:--------|:-----------|
| STS9     | 12     | 9       | 33.3%   | [1;1]      |
| STS15    | 35     | 15      | 20%     | [1;1]      |
| STS27    | 117    | 27      | 11.1%   | [1;1]      |
| STS45    | 330    | 45      | 6.7%    | [1;1]      |
| STS81    | 1080   | 81      | 3.7%    | [1;1]      |
| STS135   | 3015   | 135     | 2.2%    | [1;1]      |
| STS243   | 9801   | 243     | 1.2%    | [1;1]      |
| STS405   | 27270  | 405     | 0.7%    | [1;1]      |
| STS729   | 88452  | 729     | 0.4%    | [1;1]      |
| STS1215  | 245835 | 1215    | 0.2%    | [1;1]      |
| STS2187  | 796797 | 2187    | 0.1%    | [1;1]      |

Comma separated list of instances names:
```
STS9,STS15,STS27,STS45,STS81,STS135,STS243,STS405,STS729,STS1215,STS2187
```

# References

```BibTeX
@Article{Kritter2019,
  author       = {Julien Kritter and Mathieu Br{\'e}villiers and Julien Lepagnot and Lhassane Idoumghar},
  title        = {On the optimal placement of cameras for surveillance and the underlying set cover problem},
  journaltitle = {Applied Soft Computing},
  date         = {2019},
  volume       = {74},
  pages        = {133-153},
  doi          = {10.1016/j.asoc.2018.10.025},
}
```
