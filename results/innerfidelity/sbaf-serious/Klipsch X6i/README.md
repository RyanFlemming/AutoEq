# Klipsch X6i
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -3.8; 23 -3.9; 25 -4.1; 28 -4.3; 31 -4.4; 34 -4.6; 37 -4.8; 41 -4.9; 45 -5.1; 49 -5.4; 54 -5.6; 60 -5.9; 66 -6.2; 72 -6.5; 79 -6.9; 87 -7.3; 96 -7.8; 106 -8.1; 116 -8.2; 128 -8.6; 141 -8.8; 155 -9.0; 170 -9.0; 187 -9.1; 206 -9.1; 227 -8.9; 249 -8.9; 274 -8.7; 302 -8.5; 332 -8.2; 365 -7.9; 402 -7.6; 442 -7.2; 486 -7.0; 535 -6.8; 588 -6.2; 647 -5.9; 712 -5.6; 783 -5.3; 861 -5.3; 947 -5.5; 1042 -5.8; 1146 -6.1; 1261 -6.3; 1387 -6.8; 1526 -7.3; 1678 -7.5; 1846 -7.4; 2031 -7.1; 2234 -7.0; 2457 -6.4; 2703 -5.7; 2973 -4.1; 3270 -1.9; 3597 -0.5; 3957 -0.8; 4353 -2.9; 4788 -4.3; 5267 -4.5; 5793 -3.9; 6373 -2.0; 7010 -3.5; 7711 -5.7; 8482 -6.0; 9330 -6.0; 10263 -6.0; 11289 -6.0; 12418 -6.0; 13660 -6.0; 15026 -6.0; 16529 -6.0; 18182 -6.0; 20000 -6.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Klipsch X6i GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Klipsch X6i ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.1dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 21 Hz   | 0.56 | 2.3 dB  |
| Peaking | 179 Hz  | 0.7  | -3.4 dB |
| Peaking | 1984 Hz | 1.99 | -1.9 dB |
| Peaking | 3683 Hz | 2.84 | 6.1 dB  |
| Peaking | 6501 Hz | 5.81 | 4.1 dB  |
| Peaking | 356 Hz  | 2.11 | -0.5 dB |
| Peaking | 807 Hz  | 1.96 | 1.2 dB  |
| Peaking | 1523 Hz | 5.01 | -0.7 dB |
| Peaking | 8200 Hz | 4.67 | -0.5 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-5.2dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 2.1 dB  |
| Peaking | 62 Hz    | 1.41 | 0.1 dB  |
| Peaking | 125 Hz   | 1.41 | -2.3 dB |
| Peaking | 250 Hz   | 1.41 | -2.8 dB |
| Peaking | 500 Hz   | 1.41 | -0.3 dB |
| Peaking | 1000 Hz  | 1.41 | 0.9 dB  |
| Peaking | 2000 Hz  | 1.41 | -2.6 dB |
| Peaking | 4000 Hz  | 1.41 | 5.1 dB  |
| Peaking | 8000 Hz  | 1.41 | 0.1 dB  |
| Peaking | 16000 Hz | 1.41 | -0.2 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Klipsch%20X6i/Klipsch%20X6i.png)