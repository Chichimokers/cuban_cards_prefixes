# Registro de cambios

Qué cambia en cada versión de los datos. Para fijar una versión, usa `@vX.Y.Z` en lugar de `@main` en la URL (ver [Versiones y compatibilidad](README.md#-versiones-y-compatibilidad)).

## 0.2.0 · 2026-10-21

### Cambia lo que aceptan los patrones

- **Banco Metropolitano**: su código pasa de `95··` (parcial) a `9598`. `patterns.any`, `red`, `cup`, `usd`, `usd_mlc` e `issuers.METROPOLITANO` ya no aceptan otros dígitos 7–8 después del `95`. Gracias a [@armandofcom](https://github.com/armandofcom) ([#3](https://github.com/qvapay/cuban_cards_prefixes/issues/3)) y a [@Y4S3L23](https://github.com/Y4S3L23) ([#4](https://github.com/qvapay/cuban_cards_prefixes/issues/4)).

### Datos nuevos

- `9234`: Nómina, confirmada en BANDEC y en Banco Metropolitano ([#1](https://github.com/qvapay/cuban_cards_prefixes/issues/1), [#4](https://github.com/qvapay/cuban_cards_prefixes/issues/4)).
- `9238`: Ahorro, confirmada en BPA ([#2](https://github.com/qvapay/cuban_cards_prefixes/issues/2)).
- Fuente nueva **F**: un hilo de Kubaforum con los códigos de BANDEC, BPA y Banco Metropolitano ([#3](https://github.com/qvapay/cuban_cards_prefixes/issues/3)).

## 0.1.0 · 2026-10-20

- Primera versión: 27 prefijos, 5 emisores y validadores generados.
