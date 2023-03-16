# Taller1-Formularios-de-matricula-Cesde
Primer taller Introducción a la programación
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de estudiantes</title>
</head>

<body>
    <table border="1" style="width: 100%;">
        <tr>
            <th>ESTUDIANTE</th>
            <th colspan="4">------------</th>
            <th colspan="3">Fecha</th>
        </tr>
        <tr>
            <th>HORARIO</th>
            <th>Dia</th>
            <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
            <th>Hora</th>
            <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
            <th>23</th>
            <th>06</th>
            <th>23</th>
        </tr>
    </table>
    <table border="1" style="width: 100%;">
        <th colspan="2">Tipo de evidencia para evaluar</th>
        <th>Nota</th>
        <tr>
            <th>Desempeño</th>
            <td>Crea formularios utilizando los diferentes controles HTML5</td>
            <td></td>
        </tr>
        </tr>
    </table>
    <main>
        <h1 style="text-align: center;">FORMULARIO DE INSCRIPCIÓN</h1>
        <section>
            <fieldset style="width: 900px; margin:0 auto;">
                <!---Primera parte del formulario-->
                <legend>DATOS DEL ESTUDIANTE</legend>
                <table>
                    <tr>
                        <td>Identenficación*</td>
                        <td>&nbsp;</td>
                        <td><input type="number" name="number" id="number" placeholder="Obligatorio max 17Nros"></td>
                        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
                        <td>Fecha de nacimiento</td>
                        <th>&nbsp;</th>
                        <th><input type="date"></th>
                        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
                        <td rowspan="5">
                            <fieldset>
                                <legend>Tiempo Libre</legend>
                                <input type="checkbox" name="" id="">Estudio <br>
                                <input type="checkbox" name="" id="">Deporte <br>
                                <input type="checkbox" name="" id="">Redes sociales <br>
                                <input type="checkbox" name="" id="">Musica<br>
                                <input type="checkbox" name="" id="">Video Juegos <br>
                            </fieldset>
                        </td>
                    <tr>
                        <td style="text-align: left;">Apellidos</td>
                        <td>&nbsp;</td>
                        <td><input type="text" placeholder="Obligatorio Max 20 Letras"></td>
                        <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
                        <td style="text-align: left;">Edad</td>
                        <td>&nbsp;</td>
                        <td><input type="number" name="" id=""></td>
                    <tr>
                        <td style="text-align: left;">Nombre</td>
                        <td>&nbsp;</td>
                        <td><input type="text" placeholder="Obligatorio Max 20 Letras"></td>
                        <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
                        <td style="text-align: left;">Mes nacimiento</td>
                        <td>&nbsp;</td>
                        <td><input type="month" name="" id=""></td>
                    </tr>
                    <tr>
                        <td>Correo</td>
                        <td>&nbsp;</td>
                        <td><input type="email" name="" id="" placeholder="Ejemplo@gmail.com"></td>
                        <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
                        <td>Genero</td>
                        <td>&nbsp;</td>
                        <td><input type="radio" name="genero" id="genero">Masculino <input type="radio" name="genero"
                                id="genero">Femenino</td>
                    </tr>
                    <td>Celular</td>
                    <td>&nbsp;</td>
                    <td><input type="number" name="" id="" placeholder="xxx-xxx-xx-xx"></td>
                    <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
                    <td>Comuna(*barrios)</td>
                    <td>&nbsp;</td>
                    <td><select name="Barrios" id="barrios">
                            <option value="">Elije una opción &nbsp;&nbsp;&nbsp;</option>
                        </select></td>

                    </tr>
                </table>

            </fieldset>
            <br><br><br>
        </section>
    </main>
    <main> <!--Inicia segunda parte del formulario-->
        <h1 style="text-align: center;">*** SELECCIONAR LAS MATERIAS DEL SEMESTRE ***</h1>
        <table style="margin: 0 auto;" class="subjects">
            <tr>
                <th>MATERIAS</th>
                <th>Nro<br>Creditos</th>
                <th>Vlr 1 credito</th>
                <th>Subtotal</th>
                <th>Horario</th>
            </tr>

            <tr>
                <td><select name="" id="" style="width: 160px;">
                        <option value="">Elije una Opcion</option>
                        <option value="">Logica de programación</option>
                        <option value="">Introducción a la Programación</option>
                        <option value="">Metodologías Ágiles</option>
                <td><input type="number" min="0" max="10"></td>
                <td><input type="text"></td>
                <td><input type="text"></td>
                <td><input type="submit" value="Calcular"></td>
                <td><select name="" id="" style="width: 160px;">
                        <option value="">Elije una Opcion</option>
                        <option value="">8:00 a.m - 12:00 p.m</option>
                        <option value="">12:00 p.m - 4:00 p.m</option>
                </td>
            </tr>
            <tr>
                <td><select name="" id="" style="width: 160px;">
                        <option value="">Elije una Opcion</option>
                        <option value="">Logica de programación</option>
                        <option value="">Introducción a la Programación</option>
                        <option value="">Metodologías Ágiles</option>
                </td>
                <td><input type="number" min="0" max="10"></td>
                <td><input type="text"></td>
                <td><input type="text"></td>
                <td><select name="" id="" style="width: 160px;">
                        <option value="">Elije una Opcion</option>
                        <option value="">8:00 a.m - 12:00 p.m</option>
                        <option value="">12:00 p.m - 4:00 p.m</option>
                </td>
            </tr>

            </tr>
            <tr>
                <td><select name="" id="" style="width: 160px;">
                        <option value="">Elije una Opcion</option>
                        <option value="">Logica de programación</option>
                        <option value="">Introducción a la Programación</option>
                        <option value="">Metodologías Ágiles</option>
                </td>
                <td><input type="number" min="0" max="10"></td>
                <td><input type="text"></td>
                <td><input type="text"></td>
                <td><select name="" id="" style="width: 160px;">
                        <option value="">Elije una Opcion</option>
                        <option value="">8:00 a.m - 12:00 p.m</option>
                        <option value="">12:00 p.m - 4:00 p.m</option>
                </td>
                </td>
            </tr>
            <tr>
                <td><select name="" id="" style="width: 160px;">
                        <option value="">Elije una Opcion</option>
                        <option value="">Logica de programación</option>
                        <option value="">Introducción a la Programación</option>
                        <option value="">Metodologías Ágiles</option>
                </td>
                <td><input type="number" min="0" max="10"></td>
                <td><input type="text"></td>
                <td><input type="text"></td>
                <td><select name="" id="" style="width: 160px;">
                        <option value="">Elije una Opcion</option>
                        <option value="">8:00 a.m - 12:00 p.m</option>
                        <option value="">12:00 p.m - 4:00 p.m</option>
                </td>
            </tr>
            </tr>
            <tr>
                <td><select name="" id="" style="width: 160px;">
                        <option value="">Elije una Opcion</option>
                        <option value="">Logica de programación</option>
                        <option value="">Introducción a la Programación</option>
                        <option value="">Metodologías Ágiles</option>
                </td>
                <td><input type="number" min="0" max="10"></td>
                <td><input type="text"></td>
                <td><input type="text"></td>
                <td><select name="" id="" style="width: 160px;">
                        <option value="">Elije una Opcion</option>
                        <option value="">8:00 a.m - 12:00 p.m</option>
                        <option value="">12:00 p.m - 4:00 p.m</option>
                </td>
            </tr>
            <tr>
                <th> ...... </th>
                <th>Nro<br>Creditos</th>
                <th> ...... </th>
                <th>Total</th>
            </tr>

            <tr>
                <th></th>
                <th><input type="number" min="0" max="10"></th>
                <th></th>
                <th><input type="text"></th>
                <td><input type="submit" value="Calcular"></td>
            </tr>
            <tr>
                <td></td>
            </tr>
            <tr>
                <td></td>
            </tr>
            <tr>
                <td><input type="submit"></td>
            </tr>
        </table>
        </section>
    </main> <br><br><br><br>
    <footer>
        <li>Desarrollador: Mateo Machado</li>
        <li>Correo: mateo.machado@masglobalconsulting.com</li>
        <li>Contacto: +57 301 691 4669</li>
    </footer>

</body>

</html>
