formularios-II-javascript
========================
1.- Control Select
	este otro objeto visual que podemos disponer en un FORM realiza la seleccion de un string de una lista y tener al mismo valos no visible. 
	El objetivo fundamental en JavaScript es determinar que elemento esta seleccionado y que valor tiene asociado.
	Esto lo hacemos cuando ocurre el evento OnChange

	Para determinar la posicion del indice seleccionado en la lista:

		document.form1.select1.selectedIndex.

	Considerando que el objeto `SELECT` se llama select1 accedemos a la propiedad `SelectedIndex` (almacena la posicion del `string` seleccionado de la lista, numerando a partir de 0).

	Para determinar el `String` seleccionado:
		document.form1.select1.options[document.form1.select1.selectedIndex].text

	Es decir que el objeto `Select1` tiene otra propiedad llamada `options`, a la que accedemos por medio de un Subindice, al `String` de una determinada posicion.

	Hay problemas en los que solamente necesitamos el String alamacenado en el objeto `SELECT` y no el valor asociado (no es obligatorio asociar un valor a cada `String`)