# Coloud NHL Chicago Blackhawks
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -0.5; 37 -0.5; 41 -0.5; 45 -0.5; 49 -0.5; 54 -0.5; 60 -1.1; 66 -1.8; 72 -2.3; 79 -2.9; 87 -3.5; 96 -4.1; 106 -4.6; 116 -5.0; 128 -5.5; 141 -5.9; 155 -6.2; 170 -6.6; 187 -6.9; 206 -7.1; 227 -7.4; 249 -7.7; 274 -8.0; 302 -8.2; 332 -8.3; 365 -8.4; 402 -8.6; 442 -8.6; 486 -8.8; 535 -9.0; 588 -9.2; 647 -9.7; 712 -10.0; 783 -10.2; 861 -10.5; 947 -11.1; 1042 -12.0; 1146 -13.1; 1261 -13.5; 1387 -13.5; 1526 -13.2; 1678 -12.1; 1846 -9.5; 2031 -6.0; 2234 -2.9; 2457 -0.8; 2703 -0.5; 2973 -0.5; 3270 -0.5; 3597 -0.5; 3957 -0.5; 4353 -3.8; 4788 -6.1; 5267 -6.2; 5793 -5.4; 6373 -5.8; 7010 -7.7; 7711 -8.5; 8482 -6.8; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Coloud NHL Chicago Blackhawks GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Coloud NHL Chicago Blackhawks ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.9dB**.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 36 Hz   | 0.6  | 6.8 dB   |
| Peaking | 1794 Hz | 0.62 | -12.4 dB |
| Peaking | 2337 Hz | 1.66 | 12.2 dB  |
| Peaking | 3442 Hz | 1.46 | 8.9 dB   |
| Peaking | 7570 Hz | 8.08 | -2.1 dB  |
| Peaking | 27 Hz   | 0.44 | 2.5 dB   |
| Peaking | 34 Hz   | 1.38 | -3.3 dB  |
| Peaking | 235 Hz  | 0.79 | -1.1 dB  |
| Peaking | 846 Hz  | 3    | 1.1 dB   |
| Peaking | 4805 Hz | 9.91 | -1.7 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-8.0dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 6.6 dB  |
| Peaking | 62 Hz    | 1.41 | 4.3 dB  |
| Peaking | 125 Hz   | 1.41 | 0.5 dB  |
| Peaking | 250 Hz   | 1.41 | -1.4 dB |
| Peaking | 500 Hz   | 1.41 | -0.7 dB |
| Peaking | 1000 Hz  | 1.41 | -7.2 dB |
| Peaking | 2000 Hz  | 1.41 | 0.2 dB  |
| Peaking | 4000 Hz  | 1.41 | 6.3 dB  |
| Peaking | 8000 Hz  | 1.41 | -2.4 dB |
| Peaking | 16000 Hz | 1.41 | 0.3 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/referenceaudioanalyzer/zero/Coloud%20NHL%20Chicago%20Blackhawks/Coloud%20NHL%20Chicago%20Blackhawks.png)