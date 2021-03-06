# Westone UM Pro 50
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -8.8; 23 -9.0; 25 -9.2; 28 -9.5; 31 -9.7; 34 -9.8; 37 -9.9; 41 -10.0; 45 -10.1; 49 -10.3; 54 -10.4; 60 -10.7; 66 -11.0; 72 -11.3; 79 -11.6; 87 -12.0; 96 -12.5; 106 -12.8; 116 -13.1; 128 -13.4; 141 -13.6; 155 -13.8; 170 -13.9; 187 -13.9; 206 -13.9; 227 -13.7; 249 -13.6; 274 -13.4; 302 -13.1; 332 -12.8; 365 -12.4; 402 -11.9; 442 -11.5; 486 -10.9; 535 -10.3; 588 -9.7; 647 -9.0; 712 -8.1; 783 -7.3; 861 -6.6; 947 -6.2; 1042 -6.3; 1146 -7.1; 1261 -8.2; 1387 -9.1; 1526 -9.3; 1678 -9.0; 1846 -7.9; 2031 -5.9; 2234 -3.2; 2457 -1.0; 2703 -0.9; 2973 -1.7; 3270 -1.7; 3597 -0.6; 3957 -0.5; 4353 -0.5; 4788 -0.5; 5267 -0.5; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -11.2
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Westone UM Pro 50 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Westone UM Pro 50 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.7dB**.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 73 Hz   | 0.17 | -2.7 dB  |
| Peaking | 226 Hz  | 0.43 | -5.4 dB  |
| Peaking | 1674 Hz | 1.68 | -10.3 dB |
| Peaking | 2161 Hz | 0.67 | 8.9 dB   |
| Peaking | 5287 Hz | 2.18 | 4.2 dB   |
| Peaking | 936 Hz  | 3.91 | 1.0 dB   |
| Peaking | 1301 Hz | 6.35 | -1.1 dB  |
| Peaking | 6354 Hz | 5.39 | 1.4 dB   |
| Peaking | 6649 Hz | 5.93 | 1.5 dB   |
| Peaking | 7906 Hz | 1.83 | -2.1 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-8.4dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -2.7 dB |
| Peaking | 62 Hz    | 1.41 | -2.9 dB |
| Peaking | 125 Hz   | 1.41 | -5.6 dB |
| Peaking | 250 Hz   | 1.41 | -6.3 dB |
| Peaking | 500 Hz   | 1.41 | -3.1 dB |
| Peaking | 1000 Hz  | 1.41 | -0.0 dB |
| Peaking | 2000 Hz  | 1.41 | -0.9 dB |
| Peaking | 4000 Hz  | 1.41 | 8.1 dB  |
| Peaking | 8000 Hz  | 1.41 | 0.1 dB  |
| Peaking | 16000 Hz | 1.41 | -0.4 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/usound/Westone%20UM%20Pro%2050/Westone%20UM%20Pro%2050.png)