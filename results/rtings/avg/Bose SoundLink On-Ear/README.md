# Bose SoundLink On-Ear
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -7.8; 23 -7.9; 25 -7.9; 28 -7.9; 31 -7.9; 34 -7.9; 37 -7.8; 41 -7.7; 45 -7.6; 49 -7.5; 54 -7.4; 60 -7.3; 66 -7.4; 72 -7.4; 79 -7.4; 87 -7.5; 96 -7.4; 106 -7.4; 116 -7.4; 128 -7.3; 141 -7.4; 155 -7.4; 170 -7.1; 187 -6.6; 206 -6.2; 227 -6.0; 249 -5.9; 274 -6.0; 302 -5.9; 332 -5.6; 365 -5.2; 402 -4.7; 442 -4.2; 486 -3.7; 535 -3.2; 588 -2.6; 647 -2.1; 712 -1.7; 783 -1.4; 861 -1.2; 947 -0.8; 1042 -0.7; 1146 -0.7; 1261 -0.6; 1387 -0.6; 1526 -0.8; 1678 -1.2; 1846 -1.7; 2031 -2.5; 2234 -2.4; 2457 -1.8; 2703 -2.8; 2973 -3.6; 3270 -3.7; 3597 -4.4; 3957 -5.2; 4353 -4.8; 4788 -3.4; 5267 -1.3; 5793 -0.5; 6373 -1.6; 7010 -4.1; 7711 -5.8; 8482 -7.0; 9330 -7.1; 10263 -6.3; 11289 -4.8; 12418 -4.1; 13660 -4.3; 15026 -6.2; 16529 -11.2; 18182 -14.2; 20000 -11.7
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Bose SoundLink On-Ear GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Bose SoundLink On-Ear ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-3.5dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 23 Hz    | 0.68 | -3.2 dB |
| Peaking | 124 Hz   | 0.33 | -3.3 dB |
| Peaking | 1063 Hz  | 0.72 | 3.8 dB  |
| Peaking | 17357 Hz | 2.39 | -4.6 dB |
| Peaking | 19150 Hz | 0.83 | -9.6 dB |
| Peaking | 335 Hz   | 5.82 | -0.4 dB |
| Peaking | 4134 Hz  | 3.23 | -2.5 dB |
| Peaking | 5829 Hz  | 2.53 | 4.9 dB  |
| Peaking | 8741 Hz  | 1.56 | -3.9 dB |
| Peaking | 12975 Hz | 1.95 | 2.2 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-4.2dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -4.3 dB |
| Peaking | 62 Hz    | 1.41 | -2.4 dB |
| Peaking | 125 Hz   | 1.41 | -3.0 dB |
| Peaking | 250 Hz   | 1.41 | -2.0 dB |
| Peaking | 500 Hz   | 1.41 | 0.1 dB  |
| Peaking | 1000 Hz  | 1.41 | 3.5 dB  |
| Peaking | 2000 Hz  | 1.41 | 1.6 dB  |
| Peaking | 4000 Hz  | 1.41 | 0.1 dB  |
| Peaking | 8000 Hz  | 1.41 | -0.7 dB |
| Peaking | 16000 Hz | 1.41 | -7.0 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Bose%20SoundLink%20On-Ear/Bose%20SoundLink%20On-Ear.png)