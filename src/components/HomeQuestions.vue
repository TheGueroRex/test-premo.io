<template>
  <div class="questions">
    <h2>Preguntas frecuentes</h2>
    <p>
      Tenemos a tu disposición toda la información que necesitas conocer, así
      como también sobre el proceso de facturación y pagos. Además, nuestro
      equipo de atención al cliente está disponible para brindarte asesoramiento
      y resolver cualquier duda que puedas tener al respecto
    </p>
    <div class="question">
      <div>
        <h3>
          ¿Que productos ofrecen
          <span
            ><svg
              width="17"
              height="11"
              viewBox="0 0 17 11"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M1 9.3186L8.5 1.8186L16 9.3186"
                stroke="#0A142F"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </span>
        </h3>
      </div>
      <div class="answer">
        Actualmente, en nuestro portafolio de productos financieros ofrecemos
        diferentes opciones que se adaptan a las necesidades de nuestros
        clientes, entre ellas se encuentran: CREDITO1, CREDITO2, CREDITO3,
        CREDITO4, y CREDITO5. Cada uno de estos productos está diseñado para
        brindar opciones de financiamiento accesibles y adecuadas para cada
        situación financiera.
      </div>
    </div>
    <div class="question">
      <div>
        <h3>Tiempo estimado para aprobación de crédito solicitado. <span
            ><svg
              width="17"
              height="11"
              viewBox="0 0 17 11"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M1 9.3186L8.5 1.8186L16 9.3186"
                stroke="#0A142F"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </span></h3>
      </div>
      <div class="answer">
        Nuestro tiempo de respuesta habitual es de 48 horas para asegurarnos de
        brindar una atención de calidad y cuidadosa en cada una de las
        solicitudes que recibimos.
      </div>
    </div>
    <div class="question">
      <div>
        <h3>¿Cuál es el plazo estipulado de mi crédito? <span
            ><svg
              width="17"
              height="11"
              viewBox="0 0 17 11"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M1 9.3186L8.5 1.8186L16 9.3186"
                stroke="#0A142F"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </span></h3>
      </div>
      <div class="answer">
        Ofrecemos opciones de crédito con plazos flexibles de hasta 60 meses
        para que puedas elegir el plan de pago que mejor se adapte a tus
        necesidades financieras.
      </div>
    </div>
    <div class="question">
      <div>
        <h3>¿Existen costos ocultos asociados a la solicitud de crédito? <span
            ><svg
              width="17"
              height="11"
              viewBox="0 0 17 11"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M1 9.3186L8.5 1.8186L16 9.3186"
                stroke="#0A142F"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </span></h3>
      </div>
      <div class="answer">
        Queremos brindarte tranquilidad financiera, por eso no realizamos ningún
        tipo de cobro ni solicitamos pagos por adelantado en ninguna etapa del
        proceso de solicitud de crédito.
      </div>
    </div>
    <div class="question">
      <div>
        <h3>¿Cuánto tiempo lleva operando PREMO? <span
            ><svg
              width="17"
              height="11"
              viewBox="0 0 17 11"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M1 9.3186L8.5 1.8186L16 9.3186"
                stroke="#0A142F"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </span></h3>
      </div>
      <div class="answer">
        Somos una Institución Financiera con una trayectoria con más de 10 años
        en el mercado, lo que nos permite ofrecerte no solo respaldo, sino
        también un asesoramiento experto en todo momento para que puedas tomar
        la mejor decisión financiera.
      </div>
    </div>
    <div class="question">
      <div>
        <h3>¿La tasa de interés ofrecida es fija o variable? <span
            ><svg
              width="17"
              height="11"
              viewBox="0 0 17 11"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M1 9.3186L8.5 1.8186L16 9.3186"
                stroke="#0A142F"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </span></h3>
      </div>
      <div class="answer">
        Para brindarte estabilidad financiera, te ofrecemos una tasa de interés
        fija que se mantendrá invariable durante todo el plazo de
        financiamiento, lo que significa que podrás tener un mejor control sobre
        tus pagos mensuales y presupuestar de manera más efectiva.
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeQuestions",
};
</script>

<style>
.questions {
  margin: 0 auto;
  width: 70%;
  height: auto;
}

.questions h2 {
  text-align: center;
  font-size: 2.2em;
}

.questions p {
  width: 70%;
  margin: 0 auto;
  margin-bottom: 50px;
}

.question {
  width: 55%;
  margin: 0 auto;
}

.question h3 {
  width: 100%;
  display: flex;
  justify-content: space-between;
}

.question h3 span{
  cursor: pointer;
}

.answer {
  color: #75778c;
  border-bottom: 3px solid #75778c65;
  padding-bottom: 30px;
}
</style>
