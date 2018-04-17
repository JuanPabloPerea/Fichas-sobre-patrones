# Singleton
El patron singleton es un patron creacional al problema de la instanciacionn sin limite de objetos de una clase determinada. <br />
Algunas clases que generalmente son parte fundamental de un programa no deben exeder una o varias instancias ya que su estado e interacciones durante la ejecucion del programa son fundamentales, y hay otras clases que dependen de esa, por lo que la posibilidad y/o existencia de varios ejemplares del mismo no es conveniente por lo que conviene implementar singleton. <br />
# Implementacion segun lenguaje
la mayoria de lenguajes contienen los implementos necesartios para realizar el singleton que consiste en la modificacion del metodo constructor con un condicional o la creacion de una interfaz que permita ocultar el constructor de cara a evitar la instanciacion.
# Variantes
Existe uina variante de singleton llamada pool de objetos que consiste en no limitar la creacion de objetos a uno sino a un conjunto finito de objetos que varian de uso y disponibilidad segun la ejecucion del programa y las peticiones del cliente.<br/>
