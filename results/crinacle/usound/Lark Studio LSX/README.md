# Lark Studio LSX
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -7.5; 23 -8.0; 25 -8.3; 28 -8.7; 31 -9.0; 34 -9.2; 37 -9.4; 41 -9.6; 45 -9.8; 49 -10.0; 54 -10.2; 60 -10.4; 66 -10.6; 72 -10.9; 79 -11.2; 87 -11.4; 96 -11.7; 106 -12.0; 116 -12.2; 128 -12.3; 141 -12.4; 155 -12.3; 170 -12.3; 187 -12.2; 206 -12.0; 227 -11.7; 249 -11.4; 274 -11.0; 302 -10.6; 332 -10.2; 365 -9.7; 402 -9.2; 442 -8.7; 486 -8.2; 535 -7.7; 588 -7.2; 647 -6.6; 712 -6.1; 783 -5.6; 861 -5.2; 947 -5.1; 1042 -5.3; 1146 -5.8; 1261 -6.5; 1387 -7.3; 1526 -7.4; 1678 -6.9; 1846 -6.1; 2031 -5.5; 2234 -4.8; 2457 -3.4; 2703 -1.5; 2973 -1.1; 3270 -0.5; 3597 -0.5; 3957 -0.5; 4353 -0.5; 4788 -1.5; 5267 -3.6; 5793 -6.9; 6373 -7.2; 7010 -7.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Lark Studio LSX GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Lark Studio LSX ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.1dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 41 Hz   | 0.63 | -1.6 dB |
| Peaking | 159 Hz  | 0.46 | -5.7 dB |
| Peaking | 831 Hz  | 2.34 | 2.2 dB  |
| Peaking | 3577 Hz | 1.66 | 7.0 dB  |
| Peaking | 1551 Hz | 3.93 | -1.7 dB |
| Peaking | 2771 Hz | 5.25 | 1.7 dB  |
| Peaking | 3737 Hz | 3.18 | -1.9 dB |
| Peaking | 4760 Hz | 2.49 | 3.5 dB  |
| Peaking | 5939 Hz | 2.76 | -3.5 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.3dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -1.9 dB |
| Peaking | 62 Hz    | 1.41 | -3.0 dB |
| Peaking | 125 Hz   | 1.41 | -5.0 dB |
| Peaking | 250 Hz   | 1.41 | -4.4 dB |
| Peaking | 500 Hz   | 1.41 | -0.7 dB |
| Peaking | 1000 Hz  | 1.41 | 1.1 dB  |
| Peaking | 2000 Hz  | 1.41 | -0.4 dB |
| Peaking | 4000 Hz  | 1.41 | 7.1 dB  |
| Peaking | 8000 Hz  | 1.41 | -1.9 dB |
| Peaking | 16000 Hz | 1.41 | 0.1 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/usound/Lark%20Studio%20LSX/Lark%20Studio%20LSX.png)