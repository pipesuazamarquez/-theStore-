# -theStore-
NewProduct
<html>
<body>
     <h1>Registro de nuevos productos</h1>
     <hr />
     <form>
    
        <label>nombres:</label> <!- label del campo del nombres -->
        <input type="text"id="nombre" />  <!-campo tipo texto -->

        <label>Edad:</label> <!-Label del campo Edad -->
        <input type="number" id="edad" /> <!-campo tipo numerico -->

        <label>fecha nacimiento: </label> <!-label del campo fecha nacimiento
        <input type="date" id="fechaNacimiento" /> <!-campo tipo fecha -->
           
        <label>Estado civil: </label> <!-Label del campo del estado civil
        <select name="select" id="EstadoCivil"> <!-campo tipo seleccion -campo -->
          <option value="value1">soltero</option> <!-items del campo seleccion -->
          <option value="value2" selected>casado</option>
          <option value="value3">Union libre</option>
        </select>

        <label>Habilidades:</label> <!-label del campo Habilidades campo -->
        <textarea id="habilidades"></textarea> <!-campo tipo texto grande -->

          <button>Guardar</button> <!--boton-->
     </form>
</body>
</html>    
