# Meze 99 Classic with New Pads
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -1.5; 25 -2.4; 28 -3.5; 31 -4.6; 34 -5.5; 37 -6.2; 41 -6.8; 45 -7.3; 49 -7.8; 54 -8.1; 60 -8.4; 66 -8.8; 72 -9.0; 79 -9.1; 87 -9.0; 96 -8.8; 106 -8.4; 116 -8.3; 128 -9.1; 141 -9.6; 155 -9.9; 170 -8.8; 187 -9.4; 206 -9.4; 227 -9.2; 249 -8.9; 274 -8.3; 302 -7.8; 332 -7.6; 365 -7.5; 402 -7.7; 442 -7.8; 486 -8.1; 535 -8.2; 588 -7.8; 647 -7.6; 712 -7.3; 783 -6.7; 861 -6.4; 947 -5.7; 1042 -5.0; 1146 -5.5; 1261 -5.6; 1387 -6.6; 1526 -8.1; 1678 -9.6; 1846 -9.7; 2031 -8.9; 2234 -8.2; 2457 -7.5; 2703 -6.7; 2973 -5.9; 3270 -5.1; 3597 -3.7; 3957 -1.8; 4353 -4.8; 4788 -4.8; 5267 -1.9; 5793 -2.3; 6373 -3.1; 7010 -4.5; 7711 -6.7; 8482 -7.0; 9330 -8.2; 10263 -8.8; 11289 -7.6; 12418 -7.0; 13660 -7.0; 15026 -7.0; 16529 -7.0; 18182 -7.0; 20000 -7.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Meze 99 Classic with New Pads GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Meze 99 Classic with New Pads ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.7dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 20 Hz    | 1.36 | 6.9 dB  |
| Peaking | 113 Hz   | 0.42 | -2.4 dB |
| Peaking | 1843 Hz  | 4.47 | -3.3 dB |
| Peaking | 3828 Hz  | 4.56 | 4.4 dB  |
| Peaking | 5701 Hz  | 3.24 | 5.1 dB  |
| Peaking | 113 Hz   | 3.25 | 2.2 dB  |
| Peaking | 126 Hz   | 1.37 | -1.2 dB |
| Peaking | 545 Hz   | 4.32 | -0.8 dB |
| Peaking | 1065 Hz  | 3.01 | 2.3 dB  |
| Peaking | 10012 Hz | 4.24 | -2.3 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-5.0dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 3.8 dB  |
| Peaking | 62 Hz    | 1.41 | -2.4 dB |
| Peaking | 125 Hz   | 1.41 | -1.8 dB |
| Peaking | 250 Hz   | 1.41 | -1.3 dB |
| Peaking | 500 Hz   | 1.41 | -1.1 dB |
| Peaking | 1000 Hz  | 1.41 | 2.3 dB  |
| Peaking | 2000 Hz  | 1.41 | -3.6 dB |
| Peaking | 4000 Hz  | 1.41 | 5.0 dB  |
| Peaking | 8000 Hz  | 1.41 | 0.2 dB  |
| Peaking | 16000 Hz | 1.41 | -0.3 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Meze%2099%20Classic%20with%20New%20Pads/Meze%2099%20Classic%20with%20New%20Pads.png)