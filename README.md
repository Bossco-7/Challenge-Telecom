# Challenge_Python_AluraStore

Proyecto para acreditar el challenge de Python.

# Informe final

El análisis automático sobre la base de clientes compara el monto total reportado por cliente con lo esperado según su tarifa mensual y tiempo con la compañía (expected_total = monthly_charge × tenure). El informe identifica un subconjunto de clientes cuya facturación total es significativamente menor que la esperada — casos que requieren investigación priorizada. Estas discrepancias pueden deberse a evasión de pagos, errores en facturación, promociones, reembolsos o datos incompletos. Se entregan archivos con los clientes sospechosos (suspect_customers.csv), visualizaciones (histograma, scatter y barra por método de pago) y un informe con prioridades.
Hallazgos clave (qué debemos comunicar)

    Método de detección: se aplicaron dos reglas heurísticas principales:

        Ratio: total_reportado / total_esperado < 0.75 (cliente pagó <75% de lo esperado) y tenure ≥ 3 meses.

        Gap absoluto: expected_total − total_reportado > 2 × monthly_charge (faltan >2 meses de cargos) y tenure ≥ 3 meses.

    Resultados entregados: listado de clientes sospechosos, resumen por método de pago, gráficos que muestran distribución de ratios y relación entre tenure y gap.

    Tipos de evidencia en el informe: métricas numéricas (gap absoluto, ratio), razones textuales por cliente (ej. “paid <75% expected”, “gap >2 months”), y agrupación por método de pago para priorizar conciliaciones.
