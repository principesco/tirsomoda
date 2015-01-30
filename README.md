tirsomoda
=========

Sistema loxítico para roupas

Proxecto para a asignatura 'Sectores de Negocio' da Universidade da Coruña que amosa un sistema loxístico básico para pequenas empresas na industria de roupas.

O proxecto divídese en tres bases de datos: materias primas, transportes e roupas; encargándose cada unha da xestión dunha etapa no ciclo de vida do proceso. O fluxo de información, de forma xenérica, comezará coa entrada das materias primas dende o distribuidor e rematará coa entrega das roupas a un cliente. A relación entre as distintas etapas conséguese mediante a identificación das roupas con un número único invariante ao longo do proceso.

Fluxo loxísitico en detalle:

  1. A materia prima chega ao depósito de materias primas.
    1.1 Na base de datos de materias primas gárdase toda a información referida á entrada, saída, características, proveedor da materia prima e a fábrica onde se enviarán dende saídas ditas materias primas. 
    1.2 Considérase que un único proveedor pode enviar varias materias primas xuntas.

  2. A materia prima envíase ás fábricas.
    2.1 Na base de datos de transporte gárdase os envíos realizados de materia prima ou roupa.
    2.2 Os envíos poden ser dende unha fábrica a outra, de fábrica a almacen, de almacén a fábrica e por último envíos a clientes.
    2.3 Gárdase a información dos conductores encargados de conducir un transporte específico.

  3. As roupas chegan ao almacén dende as fábricas.
    3.1 Na base de datos de roupas gárdase a información referida ás fábricas, ás entradas e ás características das roupas.
    3.2 Considérase que unha roupa pode estar formada de varias materias primas.

  4. As roupas envíanse ao cliente final.
    4.1 Na base de datos de roupas gárdase a información referida ao cliente e á saída.

  
  
  * Cada entrada ou saída leva únicamente un tipo de materia prima ou roupa.

