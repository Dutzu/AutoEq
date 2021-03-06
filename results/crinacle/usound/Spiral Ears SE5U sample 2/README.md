# Spiral Ears SE5U sample 2
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -4.3; 23 -4.9; 25 -5.5; 28 -6.1; 31 -6.6; 34 -7.0; 37 -7.3; 41 -7.7; 45 -8.1; 49 -8.4; 54 -8.8; 60 -9.1; 66 -9.5; 72 -9.9; 79 -10.3; 87 -10.7; 96 -11.1; 106 -11.5; 116 -11.8; 128 -12.0; 141 -12.2; 155 -12.2; 170 -12.2; 187 -12.2; 206 -12.1; 227 -11.9; 249 -11.6; 274 -11.3; 302 -11.0; 332 -10.6; 365 -10.2; 402 -9.8; 442 -9.4; 486 -8.9; 535 -8.4; 588 -8.0; 647 -7.5; 712 -7.0; 783 -6.6; 861 -6.4; 947 -6.4; 1042 -7.1; 1146 -8.3; 1261 -9.8; 1387 -11.3; 1526 -13.0; 1678 -14.6; 1846 -13.5; 2031 -12.0; 2234 -10.3; 2457 -8.0; 2703 -7.4; 2973 -8.2; 3270 -1.6; 3597 -0.5; 3957 -1.6; 4353 -0.5; 4788 -0.5; 5267 -0.5; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -7.3; 15026 -9.2; 16529 -9.1; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Spiral Ears SE5U sample 2 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Spiral Ears SE5U sample 2 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.0dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 21 Hz    | 2    | 2.6 dB  |
| Peaking | 129 Hz   | 0.61 | -5.1 dB |
| Peaking | 281 Hz   | 1.17 | -2.5 dB |
| Peaking | 1768 Hz  | 2.03 | -8.8 dB |
| Peaking | 4605 Hz  | 1.37 | 7.4 dB  |
| Peaking | 896 Hz   | 3.68 | 1.7 dB  |
| Peaking | 6140 Hz  | 4.39 | 2.9 dB  |
| Peaking | 6651 Hz  | 4.49 | 2.3 dB  |
| Peaking | 7135 Hz  | 1.84 | -3.0 dB |
| Peaking | 15711 Hz | 2.31 | -3.5 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.8dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 0.8 dB  |
| Peaking | 62 Hz    | 1.41 | -2.3 dB |
| Peaking | 125 Hz   | 1.41 | -4.7 dB |
| Peaking | 250 Hz   | 1.41 | -4.6 dB |
| Peaking | 500 Hz   | 1.41 | -1.1 dB |
| Peaking | 1000 Hz  | 1.41 | 1.0 dB  |
| Peaking | 2000 Hz  | 1.41 | -8.9 dB |
| Peaking | 4000 Hz  | 1.41 | 8.9 dB  |
| Peaking | 8000 Hz  | 1.41 | 0.6 dB  |
| Peaking | 16000 Hz | 1.41 | -2.9 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/usound/Spiral%20Ears%20SE5U%20sample%202/Spiral%20Ears%20SE5U%20sample%202.png)