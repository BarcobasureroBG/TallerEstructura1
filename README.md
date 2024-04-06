# TallerEstructura1
Benjamín Garcés 215459144 benjamin.garces@alumnos.ucn.cl
Pablo Jorquera 215455637 pablo.jorquera@alumnos.ucn.cl

Datos presentes en los txt:
Eventos: 
Evento("Carrete","Arica parte Norte","Comida y bebestibles tipo coctel","12/05/2023","Moderna","1234")
Evento("Boda","Puerto Montt parte Baja","barra libre y picoteo","03/08/2024","Clasica","5678")
Evento("Reunion de Trabajo","La Serena la florida","Almuerzo y once","25/11/2025","Ochentera","9012")
Evento("Carrete","Valparaíso parte Centro","Comida y bebestibles tipo coctel","17/02/2026","Moderna","3456")
Evento("Boda","Talca parte Sur","barra libre y picoteo","09/06/2027","Clasica","7890")
Evento("Reunion de Trabajo","Los Ángeles parte Este","Almuerzo y once","22/10/2028","Ochentera","2345")
Evento("Carrete","Iquique parte Oeste","Comida y bebestibles tipo coctel","14/03/2029","Moderna","6789")
Evento("Boda","Chillán parte Norte","barra libre y picoteo","27/07/2030,""Clasica","0123")
Evento("Reunion de Trabajo","Rancagua parte Este","Almuerzo y once","08/11/2031","Ochentera","4567")
Evento("Carrete","Copiapo parte Centro","Comida y bebestibles tipo coctel","30/04/2032","Moderna","8901")
Evento("Boda","Osorno parte Sur","barra libre y picoteo","13/09/2033","Clasica","2344")
Evento("Reunion de Trabajo","Punta Arenas parte Oeste","Almuerzo y once","06/12/2034","Ochentera","6788")
Evento("Carrete","San Felipe parte Norte","Comida y bebestibles tipo coctel","19/02/2035","Moderna","0128")
Evento("Boda","Curicó parte Sur","barra libre y picoteo","02/06/2036","Clasica","3467")
Evento("Reunion de Trabajo",Coyhaique parte Este,Almuerzo y once,15/10/2037,"Ochentera","8970")
Evento("Carrete","Temuco parte Centro","Comida y bebestibles tipo coctel","28/01/2038","Moderna,""3512")
Evento("Boda","Valdivia parte Oeste","barra libre y picoteo","11/05/2039","Clasica","9345")
Evento("Reunion de Trabajo","Antofagasta parte Este","Almuerzo y once","24/09/2040","Ochentera","2589")
Evento("Carrete","Quillota parte Norte","Comida y bebestibles tipo coctel","06/01/2041","Moderna","6723")
Evento("Boda","Puerto Varas parte Sur","barra libre y picoteo","19/05/2042","Clasica","1298")
Evento("Boda","La Serena la florida","barra libre y picoteo","3/3/3","Ochentera","3734")
Evento("Boda","Coquimbo parte bajisima","barra libre y picoteo","3/3/3","Moderna","6769")

Asistentes:
Asistentes(37,"organizador","321987654","Sofía Lara","invitado especial","1234")
Asistentes(29,"invitado","789123456","Carlos Mejía","otro","1234")
Asistentes(22,"invitado","456789123","María Rojas","invitado especial","1234")
Asistentes(29,"novio","192837465","Alejandro Mora","familiar","5678")
Asistentes(18,"novia","987654321","Carla Espinoza","familiar","5678")
Asistentes(31,"padrino","123456789","Roberto Juárez","invitado especial","5678")
Asistentes(33,"madrina","987654312","Lucía Gómez","invitado especial","5678")
Asistentes(28,"invitado","654321789","Omar Vargas","otro","5678")
Asistentes(45,"jefe superior","213456789","Elena Núñez","CEO","9012")
Asistentes(38,"jefe","876543219","Ricardo Soto","Gerente de marketing","9012")
Asistentes(26,"empleado","567891234","Daniela Paz","Analista financiero","9012")
Asistentes(34,"empleado","432178965","Jorge Castillo","Recursos humanos","9012")
Asistentes(38,"organizador","876512349","Roberto Silva","invitado especial","3456")
Asistentes(34,"invitado","765423198","Laura Jiménez","otro","3456")
Asistentes(29,"invitado","654321987","Diego Torres","invitado especial","3456")
Asistentes(34,"novio","287654321","Miguel Ángel Ramos","familiar","7890")
Asistentes(29,"novia","876543219","Lucía González","familiar","7890")
Asistentes(28,"padrino","564738210","Adrián Ferrer","invitado especial","7890")
Asistentes(32,"madrina","432187654","Carla Miranda","invitado especial","7890")
Asistentes(30,"invitado","321876543","Esteban Quesada","otro","7890")
Asistentes(46,"jefe superior","219876543","Eduardo Villanueva","Presidente","2345")
Asistentes(39,"jefe","198765432","Rebeca Linares","Directora Creativa","2345")
Asistentes(27,"empleado","129876543","Raúl Méndez","Desarrollador Web","2345")
Asistentes(25,"empleado","987612345","Sofía Pérez","Analista De Datos","2345")
Asistentes(33,"novio","312456789","Leonardo Vega","familiar","0123")
Asistentes(30,"novia","654789123","Alejandra Morales","familiar","0123")
Asistentes(36,"padrino","987654321","Oscar Díaz","invitado especial","0123")
Asistentes(34,"madrina","123987654","Patricia Rojas","invitado especial","0123")
Asistentes(28,"invitado","456123789","Fabio Luna","otro","0123")
Asistentes(52,"jefe superior","789456123","Marcela Estrada","Directora Ejecutiva","4567")
Asistentes(44,"jefe","321654987","Ignacio Quintana","DirectorRH","4567")
Asistentes(29,"empleado","213456789","Silvana Martí","Ingeniera Sistemas","4567")
Asistentes(31,"empleado","198765432","Tomás Navarro","Técnico Mantenimiento","4567")
Asistentes(41,"organizador","564789123","Gloria Patiño","invitado especial","8901")
Asistentes(37,"invitado","687213945","Mauricio Serrano","otro","8901")
Asistentes(32,"invitado","498765321","Carmen López","invitado especial","8901")

FUNCIONES:

Asistentes:
    
    ~Asistentes(); 
    // Destructor de la clase Asistentes

    int getEdad(); 
    // Función para obtener la edad del asistente

    void eliminarAsistentes(vector<Asistentes*>&);
    // Función para eliminar un asistente de un vector de punteros a Asistentes

    int sumaEdades(vector<Asistentes*>&);
    // Función para calcular la suma de las edades de todos los asistentes en un vector 

    Asistentes* crearAsistente(string);
    // Función para crear un nuevo objeto Asistentes 

    string getTipoPersona(); 
    // Función para obtener el tipo de persona del asistente

    string getRut(); 
    // Función para obtener el rut del asistente

    string getNombre(); 
    // Función para obtener el nombre del asistente

    string getDatoDiferenciador(); 
    // Función para obtener el dato diferenciador del asistente

    string getCodigoEvento(); 
    // Función para obtener el código del evento al que asistió el asistente

    string informacionCompletaAsistente(); 
    // Función para obtener la información completa del asistente

    void actualizarDatosAsistentes(string); 
    // Función para actualizar los datos de los asistentes

    Asistentes* agregarDatosAsistentes(string);
    // Función para agregar datos de los asistentes

Eventos:

    ~Eventos();//destructor
    Eventos(string, string, string, string, string, string);
    // Constructor para crear un nuevo evento con información inicial como tipo de evento, ubicación, si se ofrecen alimentos, fecha, tipo de música y código del evento.

    void agregarAsistente(Asistentes*&);
    // Agrega un nuevo asistente (apuntado por el puntero Asistentes) al evento.

    string obtenerCodigoEvento(vector<Eventos*>&);
    // Devuelve el código de un evento específico de una lista de eventos.

    bool compararFechas(string, string);
    // Compara dos fechas para determinar si son iguales, anteriores o posteriores.

    bool verificarCodigoEvento(string, vector<Eventos*>&);
    // Verifica si un código de evento ya existe en la lista de eventos.

    bool cantidadEventosDia(vector<Eventos*>&, string);
    // Verifica la cantidad de eventos programados para una fecha específica.

    void crearEvento(vector<Eventos*>&, string);
    // Crea y añade un nuevo evento a la lista de eventos.

    void informacionGeneral(vector<Eventos*>&);
    // Muestra información general sobre todos los eventos en la lista.

    void agregarDatosEventos(vector<Eventos*>&, string, string);
    // Añade o modifica datos específicos de un evento.

    void desplegarEventos(vector<Eventos*>&);
    // Muestra todos los eventos en la lista.

    void actualizarDatosEventos(string);
    // Actualiza los datos de un evento específico.

    void registrarAsistente(vector<Eventos*>&);
    // Registra un nuevo asistente en un evento específico.

    void revisionAsistentes(vector<Eventos*>&);
    // Revisa la lista de asistentes de todos los eventos.

    void eliminarEvento(vector<Eventos*>&);
    // Elimina un evento específico de la lista de eventos.

    string informacionCompletaEventos();
    // Devuelve una cadena de texto con toda la información de un evento, incluyendo detalles y asistentes.

    vector<Asistentes*> getAsistentes();
    // Devuelve un vector con los punteros a los asistentes de un evento.

    string getTipoEvento();
    // Devuelve el tipo de un evento (por ejemplo, concierto, conferencia).

    string getUbicacion();
    // Devuelve la ubicación donde se llevará a cabo el evento.

    string getAlimentos();
    // Indica el tipo de alimentos.

    string getFecha();
    // Devuelve la fecha en la que está programado el evento.

    string getTipoMusica();
    // Devuelve el tipo de música que se ofrecerá en el evento.

    string getCodigoEvento();
    // Devuelve el código único asignado al evento.