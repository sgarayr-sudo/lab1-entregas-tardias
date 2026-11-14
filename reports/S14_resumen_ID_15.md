# Resumen S14 - ID 15

## PCA
- Variables numéricas iniciales: 24
- Componentes para >= 90 % de varianza: 15
- Utilidad y posible pérdida de información: (escribir)

## Comparación de modelos (validación)
                                accuracy  precision  recall      f1  average_precision    TN    FP   FN   TP  costo_BRL
experimento                                                                                                            
A. Referencia (sin PCA, C=1.0)    0.6695     0.1263  0.6545  0.2117             0.1508  3282  1612  123  233      17201
B. PCA 90 %, C=1.0                0.6488     0.1157  0.6292  0.1955             0.1281  3182  1712  132  224      18316
C. PCA 90 %, C=0.1                0.6518     0.1171  0.6320  0.1975             0.1284  3197  1697  131  225      18161
D. PCA 90 %, C=10.0               0.6499     0.1165  0.6320  0.1967             0.1280  3187  1707  131  225      18241

- Modelo sin PCA frente a modelos con PCA: (escribir)
- Modelo elegido por menor costo: A. Referencia (sin PCA, C=1.0). Justificación empresarial: (escribir)

## Prueba KS sobre valor_flete
- Hipótesis: (escribir)
- D = 0.0103, p = 0.7402, decisión: No se rechaza H0 al 5 %
- Limitación metodológica: (escribir)
