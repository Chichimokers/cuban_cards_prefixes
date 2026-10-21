# Registro de cambios

Qué cambia en cada versión de los datos. Para fijar una versión, usa `@vX.Y.Z` en lugar de `@main` en la URL (ver [Versiones y compatibilidad](README.md#-versiones-y-compatibilidad)).

## 0.3.0 · 2026-10-21

### Novedades

- **Variantes por los dígitos 5–6**: campo opcional `variants` en `prefixes.json` para los productos que comparten los 4 primeros dígitos. En `validators.json` llegan el mapa `variants` y el patrón `patterns.clasica_empresarial`. Es el primer pull request de la comunidad que se integra: gracias a [@Chichimokers](https://github.com/Chichimokers) ([#7](https://github.com/qvapay/cuban_cards_prefixes/pull/7)).
- `976004`: Clásica Empresarial de FINCIMEX. CIMEX confirma el producto (fuente nueva **CE**). El prefijo sale de la lógica de Transfermóvil que analizó [@livegnik97](https://github.com/livegnik97) ([#5](https://github.com/qvapay/cuban_cards_prefixes/issues/5)) y falta confirmarlo con una tarjeta.
- `976003`: la Clásica, reportada en el [#5](https://github.com/qvapay/cuban_cards_prefixes/issues/5) y por [@drlorente97](https://github.com/drlorente97) ([#6](https://github.com/qvapay/cuban_cards_prefixes/pull/6)).
- FINCIMEX (Clásica) en el formulario de issues.

### Compatibilidad

- Los patrones que ya existían no cambian: `patterns.clasica` sigue aceptando todas las `9760`, incluida la `976004`.

## 0.2.0 · 2026-10-21

### Cambia lo que aceptan los patrones

- **Banco Metropolitano**: su código pasa de `95··` (parcial) a `9598`. `patterns.any`, `red`, `cup`, `usd`, `usd_mlc` e `issuers.METROPOLITANO` ya no aceptan otros dígitos 7–8 después del `95`. Gracias a [@armandofcom](https://github.com/armandofcom) ([#3](https://github.com/qvapay/cuban_cards_prefixes/issues/3)) y a [@Y4S3L23](https://github.com/Y4S3L23) ([#4](https://github.com/qvapay/cuban_cards_prefixes/issues/4)).

### Datos nuevos

- `9234`: Nómina, confirmada en BANDEC y en Banco Metropolitano ([#1](https://github.com/qvapay/cuban_cards_prefixes/issues/1), [#4](https://github.com/qvapay/cuban_cards_prefixes/issues/4)).
- `9238`: Ahorro, confirmada en BPA ([#2](https://github.com/qvapay/cuban_cards_prefixes/issues/2)).
- Fuente nueva **F**: un hilo de Kubaforum con los códigos de BANDEC, BPA y Banco Metropolitano ([#3](https://github.com/qvapay/cuban_cards_prefixes/issues/3)).

## 0.1.0 · 2026-10-20

- Primera versión: 27 prefijos, 5 emisores y validadores generados.
