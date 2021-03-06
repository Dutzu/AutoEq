# Lime Ears Aether Bass
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -11.9; 23 -11.9; 25 -11.9; 28 -11.9; 31 -11.8; 34 -11.8; 37 -11.7; 41 -11.6; 45 -11.5; 49 -11.4; 54 -11.2; 60 -11.1; 66 -11.0; 72 -11.0; 79 -11.0; 87 -10.9; 96 -11.0; 106 -10.9; 116 -10.8; 128 -10.7; 141 -10.6; 155 -10.4; 170 -10.1; 187 -9.9; 206 -9.6; 227 -9.2; 249 -8.9; 274 -8.5; 302 -8.1; 332 -7.8; 365 -7.4; 402 -7.0; 442 -6.7; 486 -6.4; 535 -6.2; 588 -6.1; 647 -6.1; 712 -6.1; 783 -6.1; 861 -6.2; 947 -6.4; 1042 -6.9; 1146 -7.6; 1261 -8.3; 1387 -8.5; 1526 -8.1; 1678 -7.3; 1846 -6.5; 2031 -5.8; 2234 -5.5; 2457 -5.5; 2703 -5.4; 2973 -4.7; 3270 -3.1; 3597 -1.1; 3957 -0.5; 4353 -0.5; 4788 -1.9; 5267 -4.6; 5793 -2.5; 6373 -1.0; 7010 -4.0; 7711 -6.3; 8482 -9.0; 9330 -8.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Lime Ears Aether Bass GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Lime Ears Aether Bass ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.6dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 33 Hz   | 0.17 | -5.3 dB |
| Peaking | 1392 Hz | 3.97 | -2.4 dB |
| Peaking | 4010 Hz | 2.24 | 6.4 dB  |
| Peaking | 6371 Hz | 5.32 | 5.1 dB  |
| Peaking | 8753 Hz | 4.72 | -3.6 dB |
| Peaking | 64 Hz   | 1.77 | 0.6 dB  |
| Peaking | 181 Hz  | 1.09 | -0.7 dB |
| Peaking | 560 Hz  | 1.34 | 1.1 dB  |
| Peaking | 2847 Hz | 7.41 | -0.4 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-6.6dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -5.7 dB |
| Peaking | 62 Hz    | 1.41 | -3.2 dB |
| Peaking | 125 Hz   | 1.41 | -3.6 dB |
| Peaking | 250 Hz   | 1.41 | -2.0 dB |
| Peaking | 500 Hz   | 1.41 | 1.0 dB  |
| Peaking | 1000 Hz  | 1.41 | -0.6 dB |
| Peaking | 2000 Hz  | 1.41 | -1.5 dB |
| Peaking | 4000 Hz  | 1.41 | 6.5 dB  |
| Peaking | 8000 Hz  | 1.41 | -0.8 dB |
| Peaking | 16000 Hz | 1.41 | -0.1 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/usound/Lime%20Ears%20Aether%20Bass/Lime%20Ears%20Aether%20Bass.png)