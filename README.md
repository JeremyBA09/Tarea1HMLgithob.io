<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet"> <!--Aqui llamamos el estilo de esa pagina e google developers -->
<!--Url de los iconos --> <!--https://developers.google.com/fonts/docs/material_icons-->
    </head>

<body>

    <!--Necesito un encabezado -->
    <header>

        <!--Titulo 1 -->
        <h1> Los 10 Principios de Usabilidad de Jakob Nielsen </h1>

    </header>


    <nav> <!--Barra de navgacion-->

        <ul> <!--Voy hacer una lista no ordenada --> <!--Para poner un identificador hacer un a href-->
            <li> <a href="Visibilidad">  Visibilidad del estado del sistema </a> </li>
            <li><a href="#relacion">Relación entre el sistema y el mundo real</a></li>
            <li><a href="#control">Control y libertad del usuario</a></li>
            <li><a href="#consistencia">Consistencia y estándares</a></li>
            <li><a href="#prevencion">Prevención de errores</a></li>
            <li><a href="#reconocimiento">Reconocimiento antes que recuerdo</a></li>
            <li><a href="#flexibilidad">Flexibilidad y eficiencia de uso</a></li>
            <li><a href="#minimalismo">Diseño estético y minimalista</a></li>
            <li><a href="#ayudar">Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de errores</a></li>
            <li><a href="#ayuda">Ayuda y documentación</a></li>
        </ul>

        <ol> <!--Liata ordenada -->
            <li></li>
            <li></li>
            <li></li>
        </ol>
    </nav>

    <!--Cont pricipal -->
    <main>
        <section id="Visibilidad">  <!--lA SECCION DEJ UN ESPACIADO ARRIBA Y ABAJO -->
            <article><!--dentro de la sec va un articulo -->
                <h2> <center> Visibilidad del estado del sistema </center> </h2>
                <p>  <b> <center> El diseño siempre debe mantener informados a los usuarios sobre lo que está sucediendo, a
                    través de comentarios adecuados dentro de un período de tiempo razonable.</center></b></p> 
                
                    <blockquote>
                        <p>Precio capaticacion: &cent;200000 </p> <!--Esto para poner  precio de colones -->
                       <p> Cuando los usuarios conocen el estado actual del sistema, conocen el resultado de sus
                        interacciones anteriores y determinan los próximos pasos. </p> 
                        <footer>
                            Fuente: 
                            <a 
                               href="https://www.nngroup.com/articles/ten-usability-heuristics/"
                               target="_blank">  <!--el target black hace que se  abra el link en otra pagina -->
                        
                               10 Usability Heuristics for User Interface Design 
                           
                            </a>
                        </footer>

                    </blockquote>
                    <blockquote>

                        <footer>
                            Fuente :
                            <a 
                             href="https://www.nngroup.com/videos/usability-heuristic-system-status/"
                            target="_parent">  <!--el target parent hace que se abra el link en la misma pagina -->

                                Vídeo de 3 minutos sobre la heurística de la visibilidad 
                            </a>

                        </footer>

                    </blockquote>
                
                
                <p>
                    <center>Las interacciones predecibles crean
                        confianza tanto en el producto como en la marca.</center>
                </p>


                        <figure>

                            <img alt = "Descripcion"
                            src="https://media.nngroup.com/media/editor/2020/11/05/heuristic-example-1-rbg-73.png "
                            width="450"
                            height="300"
                            />
                            <figcaption> 'Está aquí' en los mapas del centro comercial se muestra a las personas dónde se encuentran actualmente, para ayudarles a comprender adónde ir a continuación </figcaption> <!--Esta es la leyenda de la imagen y o ve el usuario -->
                        </figure>
            </article>
        </section>

        <section id="relacion">
            <img src="" alt=""> <!--Me perdi aqui -->
            <article>
                <h2>2. Relación entre el sistema y el mundo real</h2>
                <p>El sistema debe hablar el lenguaje de los usuarios, con palabras, frases y conceptos familiares al
                    usuario, en lugar de términos orientados al sistema. Sigue convenciones del mundo real, haciendo que
                    la información aparezca en un orden natural y lógico.</p>
            </article>
            <hr>
        </section>

        <section id="control">
            <article>
                <h2>3. Control y libertad del usuario</h2>
                <p>Los usuarios a menudo eligen funciones del sistema por error y necesitarán una salida clara marcada
                    para dejar la parte no deseada del sistema sin tener que pasar por un proceso extenso.</p>
            </article>
         
            <hr /> <!--Es la linea que separa y con ctrl H cambio algo por todo --> 
        </section>

        <section id="consistencia">            
            <article>
                <h2>4. Consistencia y estándares</h2>
                <p>Los usuarios no deberían tener que preguntarse si diferentes palabras, situaciones o acciones
                    significan lo mismo. Sigue las convenciones de la plataforma.</p>
            </article>
            <span class="material-symbols-outlined">
                menu
                </span>

        </section>

        <section id="prevencion">
            <article>
                <h2>5. Prevención de errores</h2>
                <p>Aún mejor que buenos mensajes de error es un diseño cuidadoso que prevenga la ocurrencia de
                    problemas.</p>
            </article> 
            <hr>
        </section>

        <section id="reconocimiento">
            <article>
                <h2>6. Reconocimiento antes que recuerdo</h2>
                <p>Minimiza la carga de la memoria del usuario haciendo objetos, acciones y opciones visibles. El
                    usuario no debería tener que recordar información de una parte del diálogo a otra.</p>
                    
            </article>
            <hr>
        </section>

        <section id="flexibilidad">
            <article>
                <h2>7. Flexibilidad y eficiencia de uso</h2>
                <p>Los aceleradores —que son invisibles para el usuario novato— pueden a menudo aumentar la velocidad de
                    uso del sistema para el usuario experto de tal manera que el sistema pueda acomodar a ambos usuarios
                    novatos y expertos. Permite a los usuarios adaptar acciones frecuentes.</p>
            </article>
            <hr>
        </section>

        <section id="minimalismo">
            <article>
                <h2>8. Diseño estético y minimalista</h2>
                <p>Los diálogos no deberían contener información que es irrelevante o raramente necesitada. Cada unidad
                    extra de información en un diálogo compite con las unidades de información relevantes y disminuye su
                    visibilidad relativa.</p>
            </article>
            <hr>
        </section>

        <section id="ayudar">
            <article>
                <h2>9. Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de errores</h2>
                <p>Los mensajes de error deberían ser expresados en lenguaje llano (sin códigos), indicar precisamente
                    el problema y sugerir constructivamente una solución.</p>
            </article>
            <hr>
        </section>

        <section id="ayuda">
            <article>
                <h2>10. Ayuda y documentación</h2>
                <p>Aunque es mejor si el sistema puede ser utilizado sin documentación, puede ser necesario proporcionar
                    ayuda y documentación. Cualquier información de ayuda debería ser fácil de buscar, enfocada en la
                    tarea del usuario, listar pasos concretos para llevar a cabo y no ser demasiado extensa.</p>
            </article>
        </section>


    </main>
    <aside>  <!--Barra Lateral  -->
        
    </aside>


    
    <footer> <!--Pie de Pagina  -->

    </footer>


    <!-- <div>  </div> -->

    </head>




    <p>
        <center> Ing en software #1 </center>
    </p>


    <h3>
        <div class="form-check">
            <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadio1" value="option1"
                checked>
            <label class="form-check-label" for="exampleRadio1">
                Apliacion Web
            </label>
        </div>
        <div class="form-check">
            <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadio2" value="option2">
            <label class="form-check-label" for="exampleRadio2">
                Diseño de Redes
            </label>
        </div>
    </h3>


</body>

</html>
