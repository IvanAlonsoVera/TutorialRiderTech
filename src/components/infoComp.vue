<template>
  <div class="p-4 col-7 text-white text-center">
    <h2>{{bmwTitle}}</h2>
    <p>{{descripcion}}</p>
    <p>{{consumo}}</p>
  </div>
</template>
<script>
  export default {
    name: 'infoComp',
    data() {
      return {
        bmwTitle: "BMW M5 CS, BMW M5 Competition, BMW M5 y BMW M550i xDrive Berlina.",
        descripcion: "La gama M de Serie 5 combina de forma extraordinaria la deportividad característica de M con la comodidad y la elegancia de una berlina ejecutiva. Descubre cuatro automóviles M únicos y con fuerte personalidad: unos sobresalientes 467 kW (635 CV) y una aceleración de 0 a 100 km/h en solo 3,0 segundos convierten al BMW M5 CS en el BMW M5 más potente jamás visto. Limitado desde el punto de vista de la producción, este modelo especial garantiza una auténtica sensación deportiva con sus componentes de diseño y suspensión M únicos, disponibles en exclusiva para este modelo. Con una potencia máxima de 460 kW (625 CV) y una configuración de la suspensión optimizada para el rendimiento, el BMW M5 Competition con sistema M xDrive supera las expectativas más elevadas. La berlina deportiva de alto rendimiento lo subraya visualmente con numerosos detalles de diseño en Schwarz de brillo intenso. El BMW M5 dispone, además del sistema M xDrive, orientado a la máxima tracción y dinamismo, de una suspensión que satisface cualquier exigencia de confort deportivo en los trayectos largos. En combinación con el potente motor M de 8 cilindros de 441 kW (600 CV), se genera un dinamismo marcado por la fuerza y la agilidad. El cuarteto se completa con el BMW M550i xDrive Berlina: el atlético BMW Serie 5 entrega 390 kW (530 CV) e impresiona con su combinación especialmente equilibrada de deportividad, confort y eficiencia.",
        consumo: "BMW M5 CS: Consumo de combustible en l/100 km (promedio): 11,3 -11,3 Emisiones de CO2 en g/km (promedio): 256-256",
      }
    }
  }
</script>
