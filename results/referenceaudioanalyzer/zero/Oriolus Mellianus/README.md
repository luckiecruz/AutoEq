# Oriolus Mellianus
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -12.0; 23 -12.2; 25 -12.4; 28 -12.6; 31 -12.8; 34 -12.8; 37 -12.8; 41 -12.8; 45 -12.8; 49 -12.8; 54 -12.8; 60 -12.8; 66 -12.6; 72 -12.5; 79 -12.4; 87 -12.2; 96 -12.1; 106 -11.8; 116 -11.5; 128 -11.1; 141 -10.7; 155 -10.2; 170 -9.7; 187 -9.2; 206 -8.6; 227 -8.0; 249 -7.5; 274 -7.0; 302 -6.5; 332 -6.2; 365 -5.8; 402 -5.6; 442 -5.2; 486 -4.9; 535 -4.7; 588 -4.5; 647 -4.3; 712 -4.6; 783 -4.7; 861 -4.9; 947 -5.3; 1042 -5.8; 1146 -6.4; 1261 -7.2; 1387 -8.1; 1526 -9.0; 1678 -9.8; 1846 -10.2; 2031 -10.0; 2234 -9.5; 2457 -8.7; 2703 -8.2; 2973 -8.3; 3270 -8.8; 3597 -8.8; 3957 -7.4; 4353 -4.7; 4788 -2.1; 5267 -0.6; 5793 -0.5; 6373 -1.0; 7010 -3.9; 7711 -6.2; 8482 -6.4; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Oriolus Mellianus GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Oriolus Mellianus ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.8dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 35 Hz   | 0.51 | -6.4 dB |
| Peaking | 109 Hz  | 1.18 | -3.4 dB |
| Peaking | 1899 Hz | 2.64 | -4.1 dB |
| Peaking | 3491 Hz | 2.56 | -3.5 dB |
| Peaking | 5489 Hz | 2.31 | 7.2 dB  |
| Peaking | 187 Hz  | 2.14 | -1.0 dB |
| Peaking | 638 Hz  | 0.86 | 2.4 dB  |
| Peaking | 1445 Hz | 2.85 | -1.5 dB |
| Peaking | 6588 Hz | 6.36 | 2.6 dB  |
| Peaking | 7536 Hz | 2.01 | -1.6 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-2.8dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -6.3 dB |
| Peaking | 62 Hz    | 1.41 | -4.9 dB |
| Peaking | 125 Hz   | 1.41 | -4.1 dB |
| Peaking | 250 Hz   | 1.41 | -0.6 dB |
| Peaking | 500 Hz   | 1.41 | 2.2 dB  |
| Peaking | 1000 Hz  | 1.41 | 1.5 dB  |
| Peaking | 2000 Hz  | 1.41 | -5.0 dB |
| Peaking | 4000 Hz  | 1.41 | 2.0 dB  |
| Peaking | 8000 Hz  | 1.41 | 2.1 dB  |
| Peaking | 16000 Hz | 1.41 | -0.4 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/referenceaudioanalyzer/zero/Oriolus%20Mellianus/Oriolus%20Mellianus.png)