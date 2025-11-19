# 💳 De la Deuda al Dato: ML para Predecir Defaults
Modelo predictivo a partir de datos de clientes de una entidad creditica dentro del contexto de una crisis en Taiwan (año 2005)

🎯 El Problema
En 2005, Taiwán enfrentó una crisis crediticia que expuso la necesidad crítica de detectar tempranamente los impagos. ¿Cómo identificar clientes en riesgo antes de que sea tarde?
Cada default representa:

💸 Pérdidas financieras significativas
📉 Deterioro de la cartera crediticia
⚠️ Riesgo sistémico acumulativo

🔍 Nuestra Solución
Desarrollamos un modelo de Machine Learning enfocado en maximizar el recall: preferimos alertar sobre posibles defaults aunque generemos algunas falsas alarmas, porque el costo de perder un default real es mucho mayor.

📊 Los Datos
Trabajamos con 25,492 clientes y analizamos:

🏦 Financiero: límite de crédito, facturas, pagos
👤 Demográfico: edad, género, educación, estado civil
📈 Comportamental: meses de deuda, patrones de pago

Variable objetivo: Default en octubre (20% de casos positivos)

📁 Estructura del Proyecto
├── 📓 notebooks/          # Análisis exploratorio y modelos
├── 📊 data/              # Dataset original y procesado
├── 🎨 visualizations/    # Gráficos y matriz de confusión
└── 📋 docs/              # Presentación y documentación

👥 Equipo

Javier Gonzalo Valdez - jgvaldez@unsam-bue.edu.ar
Bruno Inguanzo - brunoinguanzo14@gmail.com
Matías Alejandro Vergara Vicencio - mavergaravicencio@estudiantes.unsam.edu.ar

