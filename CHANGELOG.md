# Changelog

## Versión 1

Score local: 269925.840 +/- 67086.532
Score en Kaggle: 212414.37973
Registros entrenamiento: 334462
Columnas: ['lat',
    'lon',
    'l6',
    'rooms',
    'bedrooms',
    'bathrooms',
    'surface_total',
    'surface_covered',
    'price'
]

Características:

- Se conservan solo filas con currency en dolares.
- Se conservan filas que solo sean de argentina.
- Se conservan solo las operaciones de venta.
- Se mantienen en el df aquellas propiedades de tipo Departamentos y PH.
- Estandarización min-max
- Tranformación sqrt
