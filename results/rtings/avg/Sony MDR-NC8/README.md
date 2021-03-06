# Sony MDR-NC8
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -0.5; 37 -0.5; 41 -0.6; 45 -1.2; 49 -2.2; 54 -3.4; 60 -4.5; 66 -5.6; 72 -6.4; 79 -7.2; 87 -8.0; 96 -8.7; 106 -9.5; 116 -9.9; 128 -9.7; 141 -8.9; 155 -7.8; 170 -6.8; 187 -7.2; 206 -8.0; 227 -7.8; 249 -7.5; 274 -6.9; 302 -6.1; 332 -5.6; 365 -5.1; 402 -4.7; 442 -4.5; 486 -4.9; 535 -5.8; 588 -6.3; 647 -6.0; 712 -7.3; 783 -8.6; 861 -7.8; 947 -9.8; 1042 -10.4; 1146 -8.8; 1261 -7.2; 1387 -6.5; 1526 -6.3; 1678 -5.9; 1846 -5.7; 2031 -5.4; 2234 -4.7; 2457 -5.3; 2703 -5.7; 2973 -6.3; 3270 -6.2; 3597 -5.0; 3957 -4.3; 4353 -2.1; 4788 -0.5; 5267 -0.5; 5793 -0.5; 6373 -1.0; 7010 -4.4; 7711 -11.8; 8482 -15.1; 9330 -13.0; 10263 -10.0; 11289 -10.2; 12418 -11.1; 13660 -9.7; 15026 -9.7; 16529 -8.8; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sony MDR-NC8 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-NC8 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-8.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.5dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 30 Hz    | 1.43 | 7.3 dB   |
| Peaking | 1013 Hz  | 4.19 | -4.4 dB  |
| Peaking | 6038 Hz  | 1.37 | 9.5 dB   |
| Peaking | 8319 Hz  | 2.72 | -12.2 dB |
| Peaking | 13130 Hz | 0.93 | -4.0 dB  |
| Peaking | 48 Hz    | 3.08 | 2.5 dB   |
| Peaking | 113 Hz   | 1.89 | -3.9 dB  |
| Peaking | 229 Hz   | 4.32 | -1.3 dB  |
| Peaking | 419 Hz   | 2.55 | 2.3 dB   |
| Peaking | 3229 Hz  | 6.52 | -1.6 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-8.3dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 7.9 dB  |
| Peaking | 62 Hz    | 1.41 | 0.5 dB  |
| Peaking | 125 Hz   | 1.41 | -3.6 dB |
| Peaking | 250 Hz   | 1.41 | -0.1 dB |
| Peaking | 500 Hz   | 1.41 | 2.3 dB  |
| Peaking | 1000 Hz  | 1.41 | -3.5 dB |
| Peaking | 2000 Hz  | 1.41 | 0.5 dB  |
| Peaking | 4000 Hz  | 1.41 | 5.4 dB  |
| Peaking | 8000 Hz  | 1.41 | -4.2 dB |
| Peaking | 16000 Hz | 1.41 | -3.9 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Sony%20MDR-NC8/Sony%20MDR-NC8.png)