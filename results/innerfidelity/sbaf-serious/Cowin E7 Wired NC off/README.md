# Cowin E7 Wired NC off
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.7; 34 -1.5; 37 -2.6; 41 -3.8; 45 -4.9; 49 -5.7; 54 -6.3; 60 -6.4; 66 -6.6; 72 -7.5; 79 -8.9; 87 -10.4; 96 -11.9; 106 -13.1; 116 -13.5; 128 -14.4; 141 -15.4; 155 -15.7; 170 -15.5; 187 -16.4; 206 -16.0; 227 -15.2; 249 -14.3; 274 -12.9; 302 -11.5; 332 -10.3; 365 -9.3; 402 -8.6; 442 -7.1; 486 -6.3; 535 -5.4; 588 -4.4; 647 -4.0; 712 -4.0; 783 -3.6; 861 -3.8; 947 -3.6; 1042 -3.7; 1146 -4.2; 1261 -3.8; 1387 -3.4; 1526 -2.7; 1678 -2.6; 1846 -1.8; 2031 -1.1; 2234 -0.5; 2457 -0.5; 2703 -0.5; 2973 -0.5; 3270 -0.5; 3597 -0.5; 3957 -0.5; 4353 -3.7; 4788 -7.7; 5267 -7.8; 5793 -7.4; 6373 -8.4; 7010 -8.6; 7711 -6.5; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -7.4; 20000 -7.9
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Cowin E7 Wired NC off GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Cowin E7 Wired NC off ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.8dB**.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 23 Hz   | 0.52 | 6.8 dB   |
| Peaking | 178 Hz  | 0.61 | -10.8 dB |
| Peaking | 595 Hz  | 0.86 | 4.0 dB   |
| Peaking | 3766 Hz | 0.7  | 12.7 dB  |
| Peaking | 5194 Hz | 1.01 | -11.1 dB |
| Peaking | 71 Hz   | 5.61 | 1.1 dB   |
| Peaking | 98 Hz   | 4.78 | -0.8 dB  |
| Peaking | 2142 Hz | 5.41 | 0.9 dB   |
| Peaking | 4033 Hz | 6.99 | 3.6 dB   |
| Peaking | 4054 Hz | 2.35 | -1.8 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-6.7dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 6.6 dB  |
| Peaking | 62 Hz    | 1.41 | 0.2 dB  |
| Peaking | 125 Hz   | 1.41 | -7.9 dB |
| Peaking | 250 Hz   | 1.41 | -7.9 dB |
| Peaking | 500 Hz   | 1.41 | 2.4 dB  |
| Peaking | 1000 Hz  | 1.41 | 1.7 dB  |
| Peaking | 2000 Hz  | 1.41 | 5.2 dB  |
| Peaking | 4000 Hz  | 1.41 | 3.5 dB  |
| Peaking | 8000 Hz  | 1.41 | -2.2 dB |
| Peaking | 16000 Hz | 1.41 | 0.1 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Cowin%20E7%20Wired%20NC%20off/Cowin%20E7%20Wired%20NC%20off.png)