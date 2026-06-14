# VRC / HRV RRi Analyzer Pro v8.5

## Cambios v8.5
- Corrige la llamada incompatible `mse_metrics(..., max_scale=20)`.
- `mse_metrics` acepta ahora `scales` y `max_scale`.
- `SampEn` y `MSE` usan la misma señal de entrada y la misma tolerancia.
- `MSE1 = SampEn`.
- Entropías calculadas con smoothness priors λ=500.
- Resto de parámetros no lineales sin suavizado.
- `domain_values` sólo usa columnas numéricas.
- Eliminado "Kubios Mode" del título visible.
