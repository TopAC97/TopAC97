function ejercicio5(){
  let inicio = 0, final = 0, r = 0;
  const tab = 2; // 🍄 el const se usa para una variable que tiene un valor y no requiere ser cambiado
  inicio = document.getElementById("inicio").value; // ☘️ toma un elemento que tenga ese id en el documento html que tenemos
  final = document.getElementById("final").value; // ☘️ este es igual
  inicio = parseInt(inicio); // 🐳 convierte caracteres alfanuméricos a numérico
  final = parseInt(final); // 🐳 a la variable tab no se le utiliza parseInt() porque la variable ya tiene un valor fijo, en este caso, numérico
  let resultado = document.getElementById("resp");
  resultado.innerHTML = ""; // 🍥 limpia lo que haya en la etiqueta para agregar una respuesta
  while (inicio <= final) {
    r = inicio % tab;
    if (r === 0) {
      resultado.innerHTML += `${inicio} es par \n`
      console.log(inicio + " es par ");
    }
    inicio = inicio + 1;
  }
}


<!---
TopAC97/TopAC97 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
