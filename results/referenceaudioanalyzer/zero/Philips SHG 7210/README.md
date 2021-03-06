# Philips SHG 7210
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -0.5; 37 -0.5; 41 -0.5; 45 -0.5; 49 -0.5; 54 -0.6; 60 -1.1; 66 -1.6; 72 -2.1; 79 -2.6; 87 -3.1; 96 -3.5; 106 -3.8; 116 -4.0; 128 -4.3; 141 -4.5; 155 -4.7; 170 -4.9; 187 -5.1; 206 -5.3; 227 -5.4; 249 -5.6; 274 -5.7; 302 -5.7; 332 -5.7; 365 -5.8; 402 -6.0; 442 -6.0; 486 -6.2; 535 -6.3; 588 -6.3; 647 -6.3; 712 -6.3; 783 -6.3; 861 -6.3; 947 -6.1; 1042 -6.0; 1146 -5.6; 1261 -5.0; 1387 -4.8; 1526 -5.7; 1678 -7.3; 1846 -9.0; 2031 -10.2; 2234 -10.2; 2457 -9.0; 2703 -6.3; 2973 -2.7; 3270 -0.5; 3597 -0.5; 3957 -4.4; 4353 -9.9; 4788 -13.1; 5267 -13.3; 5793 -11.9; 6373 -11.1; 7010 -11.5; 7711 -11.7; 8482 -9.9; 9330 -6.6; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.9; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Philips SHG 7210 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Philips SHG 7210 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.4dB**.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 33 Hz   | 0.38 | 6.3 dB   |
| Peaking | 2295 Hz | 1.72 | -10.7 dB |
| Peaking | 3508 Hz | 0.99 | 18.3 dB  |
| Peaking | 4790 Hz | 1.47 | -17.2 dB |
| Peaking | 7518 Hz | 3.25 | -4.6 dB  |
| Peaking | 856 Hz  | 1.55 | -0.7 dB  |
| Peaking | 1381 Hz | 3.32 | 1.5 dB   |
| Peaking | 1822 Hz | 6.38 | -1.1 dB  |
| Peaking | 9530 Hz | 7.94 | 1.2 dB   |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-8.0dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 6.6 dB  |
| Peaking | 62 Hz    | 1.41 | 4.0 dB  |
| Peaking | 125 Hz   | 1.41 | 1.3 dB  |
| Peaking | 250 Hz   | 1.41 | 0.7 dB  |
| Peaking | 500 Hz   | 1.41 | -0.2 dB |
| Peaking | 1000 Hz  | 1.41 | 1.4 dB  |
| Peaking | 2000 Hz  | 1.41 | -2.0 dB |
| Peaking | 4000 Hz  | 1.41 | 1.4 dB  |
| Peaking | 8000 Hz  | 1.41 | -5.3 dB |
| Peaking | 16000 Hz | 1.41 | 0.9 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/referenceaudioanalyzer/zero/Philips%20SHG%207210/Philips%20SHG%207210.png)