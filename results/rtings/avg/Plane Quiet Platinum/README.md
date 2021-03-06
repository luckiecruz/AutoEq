# Plane Quiet Platinum
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -12.5; 23 -14.3; 25 -15.6; 28 -16.5; 31 -16.7; 34 -16.4; 37 -16.0; 41 -15.4; 45 -14.9; 49 -14.5; 54 -14.2; 60 -14.1; 66 -14.1; 72 -14.0; 79 -13.9; 87 -14.0; 96 -14.0; 106 -14.2; 116 -14.4; 128 -14.5; 141 -14.5; 155 -14.4; 170 -14.4; 187 -14.0; 206 -13.8; 227 -13.8; 249 -13.5; 274 -12.8; 302 -12.6; 332 -12.2; 365 -11.7; 402 -11.5; 442 -11.2; 486 -11.0; 535 -10.9; 588 -11.0; 647 -11.2; 712 -11.6; 783 -11.7; 861 -11.3; 947 -12.2; 1042 -12.1; 1146 -12.4; 1261 -12.9; 1387 -12.6; 1526 -9.8; 1678 -5.8; 1846 -2.3; 2031 -0.5; 2234 -0.5; 2457 -0.5; 2703 -0.5; 2973 -0.5; 3270 -0.5; 3597 -0.5; 3957 -0.5; 4353 -0.5; 4788 -0.8; 5267 -0.5; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -7.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Plane Quiet Platinum GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Plane Quiet Platinum ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.0dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 29 Hz    | 1.12 | -7.6 dB  |
| Peaking | 141 Hz   | 0.29 | -7.5 dB  |
| Peaking | 1311 Hz  | 0.91 | -16.8 dB |
| Peaking | 2035 Hz  | 0.56 | 15.2 dB  |
| Peaking | 1949 Hz  | 5.19 | 2.6 dB   |
| Peaking | 2346 Hz  | 1.32 | -1.4 dB  |
| Peaking | 6260 Hz  | 1.72 | 4.5 dB   |
| Peaking | 7694 Hz  | 2.27 | -4.4 dB  |
| Peaking | 11808 Hz | 1.28 | -1.3 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-8.2dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | -10.1 dB |
| Peaking | 62 Hz    | 1.41 | -4.6 dB  |
| Peaking | 125 Hz   | 1.41 | -6.4 dB  |
| Peaking | 250 Hz   | 1.41 | -5.5 dB  |
| Peaking | 500 Hz   | 1.41 | -1.9 dB  |
| Peaking | 1000 Hz  | 1.41 | -7.9 dB  |
| Peaking | 2000 Hz  | 1.41 | 4.6 dB   |
| Peaking | 4000 Hz  | 1.41 | 7.1 dB   |
| Peaking | 8000 Hz  | 1.41 | 0.2 dB   |
| Peaking | 16000 Hz | 1.41 | -0.4 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Plane%20Quiet%20Platinum/Plane%20Quiet%20Platinum.png)