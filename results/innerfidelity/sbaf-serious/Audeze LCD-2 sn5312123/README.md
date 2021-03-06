# Audeze LCD-2 sn5312123
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -2.9; 23 -2.9; 25 -2.9; 28 -2.9; 31 -2.8; 34 -2.7; 37 -2.6; 41 -2.7; 45 -3.2; 49 -3.7; 54 -3.7; 60 -3.9; 66 -4.2; 72 -4.4; 79 -4.6; 87 -5.0; 96 -5.4; 106 -5.6; 116 -5.9; 128 -6.2; 141 -6.5; 155 -6.7; 170 -6.8; 187 -6.8; 206 -7.0; 227 -7.1; 249 -7.4; 274 -7.4; 302 -7.3; 332 -7.2; 365 -7.1; 402 -7.0; 442 -6.6; 486 -6.6; 535 -6.2; 588 -5.8; 647 -6.1; 712 -6.4; 783 -5.9; 861 -6.0; 947 -5.0; 1042 -4.3; 1146 -3.4; 1261 -3.6; 1387 -3.9; 1526 -4.4; 1678 -3.9; 1846 -3.1; 2031 -3.0; 2234 -3.6; 2457 -2.9; 2703 -3.2; 2973 -2.5; 3270 -2.5; 3597 -1.5; 3957 -0.5; 4353 -0.8; 4788 -2.5; 5267 -3.8; 5793 -3.8; 6373 -2.6; 7010 -3.9; 7711 -4.4; 8482 -4.7; 9330 -4.7; 10263 -4.7; 11289 -4.7; 12418 -4.7; 13660 -4.7; 15026 -4.7; 16529 -5.4; 18182 -8.3; 20000 -10.1
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Audeze LCD-2 sn5312123 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Audeze LCD-2 sn5312123 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-4.4dB**.

| Type    | Fc       |     Q | Gain    |
|:--------|:---------|:------|:--------|
| Peaking | 32 Hz    |  0.61 | 2.2 dB  |
| Peaking | 302 Hz   |  0.43 | -3.3 dB |
| Peaking | 787 Hz   |  2.91 | -1.5 dB |
| Peaking | 1267 Hz  |  0.35 | 1.8 dB  |
| Peaking | 4039 Hz  |  2.76 | 3.5 dB  |
| Peaking | 1179 Hz  |  6.74 | 0.8 dB  |
| Peaking | 1546 Hz  |  7.84 | -1.0 dB |
| Peaking | 6259 Hz  | 11.76 | 1.7 dB  |
| Peaking | 19506 Hz |  1.09 | -5.5 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-4.0dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 2.3 dB  |
| Peaking | 62 Hz    | 1.41 | 0.6 dB  |
| Peaking | 125 Hz   | 1.41 | -1.3 dB |
| Peaking | 250 Hz   | 1.41 | -2.4 dB |
| Peaking | 500 Hz   | 1.41 | -1.7 dB |
| Peaking | 1000 Hz  | 1.41 | 0.1 dB  |
| Peaking | 2000 Hz  | 1.41 | 0.9 dB  |
| Peaking | 4000 Hz  | 1.41 | 3.4 dB  |
| Peaking | 8000 Hz  | 1.41 | -0.1 dB |
| Peaking | 16000 Hz | 1.41 | -1.1 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Audeze%20LCD-2%20sn5312123/Audeze%20LCD-2%20sn5312123.png)