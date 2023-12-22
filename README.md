Parte de Android completada entera con éxito.

Al iniciar sesión con un Usuario, se lanza la actividad MainActivity.java con un botón para poder listar las insignias del usuario loggeado.

Creación de layouts: insignias_minimo2_jordi.xml y  detail_insignias_minimo2_jordi.xml.

Layout modificado: activity_main.xml

Creación de actividades: InsigniasActivityMinimo2.java . Se accede con un boton a partir de MainActivity.java .

Creación de clase Insignia y adición de ruta para realizar la funcion getInsignias:   

@GET("usuario/listar_insignias_usuario/insignias/{username}")
    Call<List<Insignia>> getInsignias(@Path("username")String username);

No queda nada pendiente.
