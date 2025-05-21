# ex3TFelixAlbaGonzalez
Cosas a tener en cuenta: He decidido que consulta y clinica sean el mismo (Clinica) ya que en mi opinión se refieren a las mismas cosas

Diagrama de actividades: El diagrama de actividades es asi ya que he decidido que cliente pueda registrar las consultas, calcular el costo de los tratamientos y generar el historial medico. Cuando un cliente registra una consulta, la clinica le ofrece servicios a mediante el veterinario asignado, el cual registra el diganostico y los medicamentos. Calcular el costo de los tratamientos y generar el historial medico estan unidos al metodo del veterinario(+ registroDeDiagnosticoYMedicamentos()) ya que el resultado depende de lo que el veterinario haya diagnosticado.

Diagrama de secuencias: 1. Devuelve la fecha de la consulta, el tipo de la consulta y el veterinario asignado.
                        2. Devuelve el precio de los medicamentos y tratamientos realizados.
                        3. Devuelve el historial medico de la mascota escogida.

Cuando un cliente registra una consulta para su mascota en su clinica asignada, la clinica le proporciona la fecha de la consulta, su tipo y el veterinario que realizara la consulta, una vez hecho esto, la clinica prestara sus servicios mediante el veterinario que haya sido asignado, el cual realizara el tratamiento necesario en la mascota asignada.

Cuando el cliente quiera calcular el precio de los medicamentos, se le devolveran el precio de los medicamentos de la mascota asignada.
Cuando el cliente quiera generar el historial médico, se le devolveran el historial medico de la mascota asignada de la mascota asignada.
