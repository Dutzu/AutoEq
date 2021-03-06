# Fender FXA9
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -7.0; 23 -7.1; 25 -7.3; 28 -7.5; 31 -7.8; 34 -8.0; 37 -8.2; 41 -8.5; 45 -8.7; 49 -8.9; 54 -9.1; 60 -9.5; 66 -9.8; 72 -10.2; 79 -10.6; 87 -11.0; 96 -11.5; 106 -11.9; 116 -12.3; 128 -12.6; 141 -13.0; 155 -13.2; 170 -13.4; 187 -13.5; 206 -13.6; 227 -13.7; 249 -13.7; 274 -13.5; 302 -13.3; 332 -13.0; 365 -12.6; 402 -12.3; 442 -12.0; 486 -11.6; 535 -11.2; 588 -10.8; 647 -10.4; 712 -10.0; 783 -9.5; 861 -9.1; 947 -9.0; 1042 -9.0; 1146 -9.3; 1261 -9.3; 1387 -8.7; 1526 -7.4; 1678 -5.7; 1846 -3.9; 2031 -1.9; 2234 -0.5; 2457 -0.5; 2703 -0.5; 2973 -1.9; 3270 -4.3; 3597 -3.6; 3957 -0.5; 4353 -0.5; 4788 -0.5; 5267 -0.5; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -9.3; 15026 -13.9; 16529 -13.7; 18182 -16.2; 20000 -20.1
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Fender FXA9 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Fender FXA9 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.1dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 120 Hz   | 0.36 | -1.4 dB |
| Peaking | 247 Hz   | 0.38 | -6.1 dB |
| Peaking | 1324 Hz  | 2.29 | -2.6 dB |
| Peaking | 2330 Hz  | 1.84 | 6.7 dB  |
| Peaking | 5084 Hz  | 1.87 | 6.5 dB  |
| Peaking | 2784 Hz  | 9.82 | 1.2 dB  |
| Peaking | 6345 Hz  | 3.92 | 2.9 dB  |
| Peaking | 12004 Hz | 1.81 | 5.0 dB  |
| Peaking | 18919 Hz | 0.24 | -8.3 dB |
| Peaking | 20607 Hz | 0.62 | -6.7 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-6.9dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | -0.8 dB  |
| Peaking | 62 Hz    | 1.41 | -2.1 dB  |
| Peaking | 125 Hz   | 1.41 | -5.0 dB  |
| Peaking | 250 Hz   | 1.41 | -6.3 dB  |
| Peaking | 500 Hz   | 1.41 | -3.4 dB  |
| Peaking | 1000 Hz  | 1.41 | -3.4 dB  |
| Peaking | 2000 Hz  | 1.41 | 3.5 dB   |
| Peaking | 4000 Hz  | 1.41 | 5.8 dB   |
| Peaking | 8000 Hz  | 1.41 | 1.8 dB   |
| Peaking | 16000 Hz | 1.41 | -10.1 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/harman_in-ear_2017-1/Fender%20FXA9/Fender%20FXA9.png)