# Modelo "Insolation Forest" para Detección de Anomalías en ReteICA

### Problema: 
El municipio de La Unión, Valle del Cauca, Colombia, enfrenta desafíos en la detección de anomalías en las declaraciones del impuesto ReteICA. Estas anomalías pueden indicar fraude fiscal o errores en las declaraciones, lo que afecta la recaudación y la transparencia tributaria.

## Equipo
* Luis Delio Salazar
* Juan Mayorga
* Wilson Russi
* Juan David Velez

## Modelo usado
- K-Means para segmentar contribuyentes y Isolation Forest para detectar anomalías en los pagos del impuesto ReteICA.
- Isolation Forest se eligió por su eficacia en la detección de anomalías en conjuntos de datos con alta dimensionalidad y su capacidad para manejar grandes volúmenes de datos sin necesidad de etiquetado previo.

## Resultado principal
* El modelo central es Isolation Forest, que obtuvo métricas sólidas:

**AUC**: 0.9833 — excelente discriminación
**Accuracy**: 0.9570
**F1 Score**: 0.7036

## Tecnologías
- Python
- Scikit-learn
- Pandas
- Matplotlib
- FastAPI
- MongoDB
- Docker
- Redis
- Uvicorn
- React (para el frontend)
- Flask (para el backend)


### Descripción del Proyecto
AnomalyWatch es un sistema de detección de anomalías en declaraciones del impuesto ReteICA del municipio de La Unión, Valle del Cauca, Colombia. Su objetivo es identificar patrones inusuales de pago que puedan indicar fraude fiscal o errores en las declaraciones, promoviendo el cumplimiento tributario y la transparencia.
