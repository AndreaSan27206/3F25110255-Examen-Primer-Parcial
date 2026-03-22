¿Qué tipo de relación existe entre "Vehículo" y "Camioneta"? ¿Es herencia, agregación o asociación?
R= Es asociación, ya que "Vehiculos" puede SER UNA "Camioneta"

¿Cómo se representa la restricción de que un cliente solo puede alquilar un máximo de tres vehículos?
R=Yo lo intente basada en la multiplicidad para aclarar este limite de alquileres: Clientes "1" o-- "1..3" Alquileres

¿Qué modificadores de acceso serían adecuados para los atributos de cada clase?
R= creo que todas, "+" para ver publico lo que los clientes necesitan asegurar al hacer un alquiler
"-" privados para solo la empresa 
"#" Protegidos para cosas que formalmente no todo usuario de la empresa debería ver 