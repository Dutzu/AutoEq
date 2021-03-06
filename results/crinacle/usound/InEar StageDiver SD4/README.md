# InEar StageDiver SD4
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -6.1; 23 -6.2; 25 -6.3; 28 -6.5; 31 -6.6; 34 -6.6; 37 -6.7; 41 -6.9; 45 -7.0; 49 -7.2; 54 -7.4; 60 -7.6; 66 -7.9; 72 -8.3; 79 -8.7; 87 -9.1; 96 -9.5; 106 -9.9; 116 -10.3; 128 -10.6; 141 -10.9; 155 -11.1; 170 -11.3; 187 -11.4; 206 -11.4; 227 -11.4; 249 -11.3; 274 -11.2; 302 -11.0; 332 -10.8; 365 -10.5; 402 -10.2; 442 -9.9; 486 -9.5; 535 -9.0; 588 -8.5; 647 -7.9; 712 -7.2; 783 -6.4; 861 -5.7; 947 -5.1; 1042 -4.9; 1146 -5.0; 1261 -5.2; 1387 -5.0; 1526 -4.3; 1678 -3.3; 1846 -2.3; 2031 -1.5; 2234 -0.5; 2457 -0.5; 2703 -0.5; 2973 -0.5; 3270 -0.5; 3597 -0.5; 3957 -0.5; 4353 -0.5; 4788 -3.0; 5267 -5.7; 5793 -6.9; 6373 -6.8; 7010 -7.6; 7711 -11.4; 8482 -11.9; 9330 -7.0; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -9.2; 18182 -10.4; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`InEar StageDiver SD4 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `InEar StageDiver SD4 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.6dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 215 Hz   | 0.51 | -5.2 dB |
| Peaking | 2518 Hz  | 0.94 | 6.2 dB  |
| Peaking | 4123 Hz  | 3.84 | 3.6 dB  |
| Peaking | 8081 Hz  | 4.08 | -6.9 dB |
| Peaking | 17704 Hz | 2.19 | -4.8 dB |
| Peaking | 22 Hz    | 0.85 | 0.5 dB  |
| Peaking | 915 Hz   | 1.56 | 3.7 dB  |
| Peaking | 946 Hz   | 0.7  | -3.1 dB |
| Peaking | 2297 Hz  | 0.12 | 0.7 dB  |
| Peaking | 5657 Hz  | 4.22 | -2.3 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-6.8dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 0.3 dB  |
| Peaking | 62 Hz    | 1.41 | -0.6 dB |
| Peaking | 125 Hz   | 1.41 | -3.5 dB |
| Peaking | 250 Hz   | 1.41 | -4.4 dB |
| Peaking | 500 Hz   | 1.41 | -2.4 dB |
| Peaking | 1000 Hz  | 1.41 | 0.7 dB  |
| Peaking | 2000 Hz  | 1.41 | 4.2 dB  |
| Peaking | 4000 Hz  | 1.41 | 6.2 dB  |
| Peaking | 8000 Hz  | 1.41 | -4.5 dB |
| Peaking | 16000 Hz | 1.41 | -1.3 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/usound/InEar%20StageDiver%20SD4/InEar%20StageDiver%20SD4.png)