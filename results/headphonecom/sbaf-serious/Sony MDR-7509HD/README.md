# Sony MDR-7509HD
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -0.5; 37 -0.5; 41 -0.5; 45 -0.5; 49 -0.5; 54 -0.5; 60 -0.5; 66 -0.5; 72 -0.5; 79 -0.5; 87 -0.5; 96 -0.5; 106 -0.8; 116 -1.5; 128 -2.4; 141 -3.3; 155 -4.2; 170 -4.3; 187 -5.0; 206 -5.3; 227 -5.4; 249 -4.5; 274 -3.9; 302 -4.6; 332 -5.3; 365 -7.5; 402 -9.6; 442 -10.7; 486 -10.7; 535 -11.1; 588 -10.6; 647 -9.0; 712 -8.8; 783 -9.4; 861 -9.7; 947 -8.8; 1042 -8.1; 1146 -8.1; 1261 -8.0; 1387 -9.6; 1526 -11.5; 1678 -13.3; 1846 -13.0; 2031 -14.3; 2234 -13.0; 2457 -10.4; 2703 -6.9; 2973 -5.4; 3270 -3.9; 3597 -1.3; 3957 -0.5; 4353 -0.5; 4788 -0.5; 5267 -2.8; 5793 -3.4; 6373 -1.0; 7010 -4.0; 7711 -6.6; 8482 -13.2; 9330 -15.7; 10263 -9.1; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sony MDR-7509HD GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-7509HD ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.5dB**.

| Type    | Fc      |     Q | Gain     |
|:--------|:--------|:------|:---------|
| Peaking | 44 Hz   |  0.27 | 6.4 dB   |
| Peaking | 514 Hz  |  1.78 | -5.2 dB  |
| Peaking | 2067 Hz |  1.27 | -12.9 dB |
| Peaking | 3788 Hz |  0.62 | 9.1 dB   |
| Peaking | 9069 Hz |  3.83 | -13.0 dB |
| Peaking | 212 Hz  |  2.05 | -3.0 dB  |
| Peaking | 273 Hz  |  1.55 | 3.1 dB   |
| Peaking | 407 Hz  |  4.91 | -2.0 dB  |
| Peaking | 5589 Hz | 10.71 | -7.6 dB  |
| Peaking | 5876 Hz |  3.38 | 3.1 dB   |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.8dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 5.8 dB  |
| Peaking | 62 Hz    | 1.41 | 5.3 dB  |
| Peaking | 125 Hz   | 1.41 | 3.1 dB  |
| Peaking | 250 Hz   | 1.41 | 2.0 dB  |
| Peaking | 500 Hz   | 1.41 | -4.8 dB |
| Peaking | 1000 Hz  | 1.41 | 0.4 dB  |
| Peaking | 2000 Hz  | 1.41 | -9.2 dB |
| Peaking | 4000 Hz  | 1.41 | 9.7 dB  |
| Peaking | 8000 Hz  | 1.41 | -4.0 dB |
| Peaking | 16000 Hz | 1.41 | 0.1 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sony%20MDR-7509HD/Sony%20MDR-7509HD.png)