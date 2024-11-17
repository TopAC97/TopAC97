🌠ESTA ES LA PARTE DEL HTML QUE VA CON EL JAVA🌠


<main>
        <section>
          <header>
              <h2 class="titulo">Pares</h2>
          </header>
          <br>
          <article class="formContainer">
            <form action="./numeros.html">
              <div>
                <label for="inicio">Valor Inicial</label>
                <input id="inicio" type="text" required placeholder="Ingresa un número">
              </div>
              <div>
                <label for="final">Valor final</label>
                <input id="final" type="text" required placeholder="Ingresa un número">
              </div>
              <div>
                  <label for="resp">Los pares son:</label>  // 🍨 en java utilicé tab=2 porque quiero sacar los pares de un numero inicial a uno final
                  <textarea id="resp" rows="5" cols="10">
                    
                  </textarea>
              </div>
              <div>
                <button type="button" onclick="ejercicio5()">Aceptar</button> // 🐯 aqui llamo a la función, en otro ejercicio tuve este problema de poner el nombre de otra función en lugar de la correcta
                <button type="submit">ir al home</button>
                <button type="reset">Limpiar</button> // 🍂 este boton borra lo que estuvo en el espacio en donde va lo que se ingresó y el resultado
              </div>
            </form>
          </article>
        </section>
      </main>
<!---
TopAC97/TopAC97 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
