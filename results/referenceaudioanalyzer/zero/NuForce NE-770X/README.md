# NuForce NE-770X
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -18.8; 23 -19.0; 25 -19.2; 28 -19.3; 31 -19.2; 34 -19.1; 37 -19.0; 41 -18.8; 45 -18.5; 49 -18.3; 54 -18.0; 60 -17.6; 66 -17.1; 72 -16.7; 79 -16.2; 87 -15.6; 96 -15.0; 106 -14.4; 116 -13.7; 128 -13.0; 141 -12.3; 155 -11.6; 170 -10.8; 187 -10.0; 206 -9.4; 227 -8.7; 249 -8.1; 274 -7.7; 302 -7.3; 332 -6.7; 365 -6.2; 402 -5.6; 442 -5.0; 486 -4.5; 535 -4.0; 588 -3.6; 647 -3.3; 712 -3.0; 783 -2.8; 861 -2.7; 947 -2.7; 1042 -2.7; 1146 -2.9; 1261 -3.4; 1387 -4.0; 1526 -4.9; 1678 -6.0; 1846 -7.5; 2031 -9.6; 2234 -11.5; 2457 -12.8; 2703 -13.1; 2973 -12.7; 3270 -11.9; 3597 -11.3; 3957 -11.0; 4353 -10.0; 4788 -7.5; 5267 -3.7; 5793 -0.5; 6373 -0.9; 7010 -3.9; 7711 -6.1; 8482 -6.4; 9330 -6.4; 10263 -6.4; 11289 -6.4; 12418 -6.4; 13660 -6.4; 15026 -6.4; 16529 -6.4; 18182 -6.4; 20000 -6.4
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`NuForce NE-770X GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `NuForce NE-770X ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.7dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 32 Hz    | 0.25 | -12.9 dB |
| Peaking | 1371 Hz  | 0.44 | 8.6 dB   |
| Peaking | 2668 Hz  | 0.73 | -12.9 dB |
| Peaking | 5972 Hz  | 2.9  | 9.3 dB   |
| Peaking | 22050 Hz | 0.94 | -0.4 dB  |
| Peaking | 1784 Hz  | 2.41 | 1.3 dB   |
| Peaking | 2273 Hz  | 1.14 | -1.9 dB  |
| Peaking | 3369 Hz  | 1.2  | 1.9 dB   |
| Peaking | 4216 Hz  | 3.71 | -2.0 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-5.4dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | -13.8 dB |
| Peaking | 62 Hz    | 1.41 | -8.1 dB  |
| Peaking | 125 Hz   | 1.41 | -5.1 dB  |
| Peaking | 250 Hz   | 1.41 | -1.0 dB  |
| Peaking | 500 Hz   | 1.41 | 1.8 dB   |
| Peaking | 1000 Hz  | 1.41 | 5.5 dB   |
| Peaking | 2000 Hz  | 1.41 | -4.3 dB  |
| Peaking | 4000 Hz  | 1.41 | -3.8 dB  |
| Peaking | 8000 Hz  | 1.41 | 3.3 dB   |
| Peaking | 16000 Hz | 1.41 | -0.5 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/referenceaudioanalyzer/zero/NuForce%20NE-770X/NuForce%20NE-770X.png)