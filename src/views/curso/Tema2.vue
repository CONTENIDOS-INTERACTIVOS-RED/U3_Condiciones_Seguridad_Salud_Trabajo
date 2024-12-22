<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Monitoreo y evaluación de programas de seguridad y salud en el trabajo'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    p(data-aos="fade-left").mb-4 El monitoreo y la evaluación de los programas de gestión de riesgos en seguridad y salud en el trabajo (SST) son procesos fundamentales para garantizar la eficacia y mejora continua de las medidas implementadas. Estos procesos permiten identificar, analizar y mitigar los riesgos a los que están expuestos los trabajadores, asegurando un ambiente laboral seguro y saludable.


    p(data-aos="fade-left").mb-4 #[strong Conozcamos la definición de cada uno de estos términos:]

    .row.align-items-center.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema2/1.png", alt="", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8.order-1

        LineaTiempoD.color-primario.large(data-aos="fade-left")
          p(numero="1" titulo="Monitoreo") El monitoreo implica la recopilación y análisis constante de datos relacionados con la ejecución de los programas de SST. Esto incluye la observación de prácticas laborales, la revisión de incidentes y accidentes, así como la evaluación de la formación y conciencia de los empleados sobre los riesgos presentes en su actividad. A través de indicadores claves de rendimiento (KPI), las organizaciones pueden medir el cumplimiento de los objetivos establecidos y detectar desviaciones que requieran atención.
          p(numero="2" titulo="Evaluación") La evaluación es un proceso más profundo que busca determinar la efectividad de las intervenciones y estrategias implementadas. Implica la revisión de los resultados obtenidos en comparación con las metas propuestas, así como la identificación de áreas de mejora. La evaluación permite a las empresas ajustar sus programas, reforzar sus estrategias y, en última instancia, reducir la incidencia de accidentes y enfermedades laborales.

    .row.mb-5
      .col-lg-4
        figure
          img(src="@/assets/curso/tema2/2.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left").mb-5 Ambos procesos deben ser sistemáticos y realizarse de forma periódica para asegurar que las acciones tomadas respondan a la realidad cambiante del entorno laboral. Al incorporar la retroalimentación de los trabajadores y otros interesados en el proceso de monitoreo y evaluación, las organizaciones pueden fomentar una cultura de seguridad más sólida y promover un entorno de trabajo que priorice el bienestar de todos sus miembros. 

        .bg-color-1.p-4(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/3.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 En conclusión, un monitoreo y evaluación efectivos, son esenciales para el éxito de los programas de gestión de riesgos en SST, contribuyendo a la protección de la salud y seguridad de los trabajadores y, por ende, a la sostenibilidad de la organización.


    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            //- Referencia con enlace 
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/56053" target="_blank" rel="noopener noreferrer") Cortés, J. M. (2017). Sistemas de gestión de calidad (ISO 9001:2015): ( ed.). Editorial ICB. 


            //- Referencia de youtube 
            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=IXEQgAPVM7U" target="_blank" rel="noopener noreferrer") alvarezunahvs. (2024, 1 marzo). 70 Simposio Medicina Laboral ISO 45001 2018 UNAH-VS Modulo I

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
import BannerInterno from '../../components/plantilla/BannerInterno'
export default {
  name: 'Tema2',
  components: {
    BannerInterno,
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
