tirsomoda
=========

Sistema loxístico para roupas

Proxecto para a asignatura 'Sectores de Negocio' da Universidade da Coruña que amosa un sistema loxístico básico para pequenas empresas na industria de roupas.

O proxecto divídese en tres bases de datos: materias primas, transportes e roupas; encargándose cada unha da xestión dunha etapa no ciclo de vida do proceso. O fluxo de información, de forma xenérica, comezaría coa entrada das materias primas dende o distribuidor e remataría coa entrega das roupas a un cliente. A relación entre as distintas etapas conséguese mediante a idéntificación das roupas con un número único invariante ó longo do proceso.

Fluxo loxísitico en detalle:

  1. A materia prima chega ó depósito de materias primas.
    1.1 Na base de datos de materias primas gárdase toda a información referida á entrada, saída, caracteríscas e proveedor do          produto.
    1.2 Considérase que un único proveedor pode enviar varias materias primas xuntas.

  2. A materia prima envíase ás fábricas.
    2.1 Na base de datos de transporte g�rdase os env�os realizados de materia prima ou roupa.
    2.2 Os env�os poden ser dende unha f�brica a outra, de f�brica a almacen, de almac�n a f�brica e por �ltimo env�os a clientes.
    2.3 G�rdase a informaci�n dos conductores encargados de conducir un transporte espec�fico.

  3. As roupas chegan ó almacén dende as fábricas.
    3.1 Na base de datos de roupas gárdase a información referida ás fábricas, ás entradas e ás características das roupas.
    3.2 Considérase que unha roupa pode estar formada de varias materias primas.

  4. As roupas envíanse ó cliente final.
    4.1 Na base de datos de roupas gárdase a información referida ó cliente e á saída.

  
  
  * Cada entrada ou saída leva únicamente un tipo de materia prima ou roupa.

