# tienda

Red de tienda

Participantes:
  Existen 2 participantes, el usuario que consta de id, nombres, apellidos y saldo, ademas de la sucursal que tiene id, nombre y ganancias. El usuario es el que interactua con la plataforma y realiza compras, la sucursal es la que almacena los productos y obtiene las ganancias cuando uno de estos es vendido.
  
Bienes:
  Producto es el bien que se utiliza en la aplicacion, cada producto esta relacionado con una sucursal y una sucursal puede relacionarse con varios productos. Los productos cuentan con id, nombre, existencias, color, tipo, si esta en oferta o no y su respectiva sucursal.
  
Transacciones:
  Existen 3 transacciones, la primera es Reabastecer, que permite a una tienda agregar mas existencias de un producto pidiendo el id de producto y la cantidad que va a reabastecer. La segunda es Recargar, pide el id de un usuario y la cifra de saldo que desea aumentar. Y por ultimo esta el Pago, al momento de realizar un pago se pide el id del usuario y del producto, en esta transaccion ocurren 3 acciones, al producto se le resta 1 en existencias, al saldo del usuario se le resta el valor del producto y por ultimo a las ganancias de la sucursal se le suma el valor del producto.
