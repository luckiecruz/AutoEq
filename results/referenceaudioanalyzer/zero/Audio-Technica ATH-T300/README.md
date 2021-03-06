# Audio-Technica ATH-T300
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -1.0; 37 -2.0; 41 -3.5; 45 -4.9; 49 -6.0; 54 -7.1; 60 -8.2; 66 -9.0; 72 -9.2; 79 -9.3; 87 -9.8; 96 -10.4; 106 -10.9; 116 -11.7; 128 -12.4; 141 -12.8; 155 -13.0; 170 -13.1; 187 -12.8; 206 -12.5; 227 -12.0; 249 -11.5; 274 -11.2; 302 -10.9; 332 -10.5; 365 -10.2; 402 -10.0; 442 -9.9; 486 -9.9; 535 -10.2; 588 -10.5; 647 -10.9; 712 -11.4; 783 -12.0; 861 -12.1; 947 -11.2; 1042 -10.3; 1146 -10.8; 1261 -11.2; 1387 -10.1; 1526 -7.9; 1678 -5.4; 1846 -3.2; 2031 -1.8; 2234 -1.0; 2457 -0.5; 2703 -0.5; 2973 -0.5; 3270 -0.5; 3597 -0.5; 3957 -0.5; 4353 -0.5; 4788 -0.5; 5267 -0.5; 5793 -2.5; 6373 -6.9; 7010 -8.0; 7711 -6.7; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Audio-Technica ATH-T300 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Audio-Technica ATH-T300 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.0dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 27 Hz   | 1.06 | 7.5 dB  |
| Peaking | 158 Hz  | 0.53 | -6.5 dB |
| Peaking | 820 Hz  | 1.46 | -5.2 dB |
| Peaking | 1322 Hz | 3.06 | -5.1 dB |
| Peaking | 2932 Hz | 0.79 | 7.3 dB  |
| Peaking | 61 Hz   | 4.97 | -0.9 dB |
| Peaking | 2072 Hz | 4.74 | 0.9 dB  |
| Peaking | 3037 Hz | 3.19 | -1.2 dB |
| Peaking | 5459 Hz | 2.52 | 6.2 dB  |
| Peaking | 6531 Hz | 2.26 | -6.3 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.9dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 7.6 dB  |
| Peaking | 62 Hz    | 1.41 | -2.2 dB |
| Peaking | 125 Hz   | 1.41 | -5.4 dB |
| Peaking | 250 Hz   | 1.41 | -4.2 dB |
| Peaking | 500 Hz   | 1.41 | -1.7 dB |
| Peaking | 1000 Hz  | 1.41 | -6.7 dB |
| Peaking | 2000 Hz  | 1.41 | 4.3 dB  |
| Peaking | 4000 Hz  | 1.41 | 7.1 dB  |
| Peaking | 8000 Hz  | 1.41 | -1.7 dB |
| Peaking | 16000 Hz | 1.41 | 0.1 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/referenceaudioanalyzer/zero/Audio-Technica%20ATH-T300/Audio-Technica%20ATH-T300.png)