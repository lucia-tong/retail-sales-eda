# Retail Sales EDA — Centros Comerciales Istanbul

Un análisis exploratorio de casi 100.000 transacciones de compra-venta en centros comerciales de Estambul (2021–2022). Proyecto del Máster en Data & AI — Nuclio Digital School.

## qué hace

* calcula el total de ingresos generados por todas las ventas
* identifica el centro comercial y la categoría con más facturación
* encuentra el día con más ventas y el cliente que más gastó
* calcula la distribución porcentual de ventas por categoría
* analiza el día de la semana con más ventas por cada centro comercial

## estructura

```
retail/
├── data/
│   └── datos_ventas_centros_comerciales.csv  # Dataset 
├── retail.ipynb                    # Notebook 
└── README.md                                
```

## cómo ejecutarlo

```bash
pip install pandas jupyter
jupyter notebook retail.ipynb
```

## resultados principales

* facturación total: ~1.490 millones
* centro con más ventas: Mall of Istanbul
* categoría líder: Clothing (34.5% de los ingresos)
* producto más caro: categoría Toys
* cantidad promedio por transacción: 3 unidades

## stack

python · pandas · jupyter
