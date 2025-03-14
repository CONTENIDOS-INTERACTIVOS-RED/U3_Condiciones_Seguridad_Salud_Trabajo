<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Estrategias para el fomento de una cultura de seguridad en el trabajo'")
  .container.tarjeta.tarjeta--blanca.px-4.px-md-5

    .bg-full-width.bg-color-1
      .p-4.p-md-5
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema3/1.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 Fomentar una cultura de seguridad en el trabajo es esencial para garantizar un entorno laboral protegido y eficiente. Se utilizan estrategias prácticas como la formación continua, la comunicación efectiva y el compromiso de la alta dirección para promover la prevención de riesgos y fortalecer el bienestar de los empleados. A través de estas iniciativas, las organizaciones pueden integrar la seguridad como un valor fundamental, impulsando la productividad y la satisfacción laboral.

    .bg-full-width.bg-color-6.border-top.color-secundario
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-8
            h2.mb-4(data-aos="flip-up") Estrategias para el fomento de una cultura de seguridad en el trabajo
            p.mb-4(data-aos="fade-right") La promoción de una cultura de seguridad en el trabajo es un pilar esencial para garantizar un entorno laboral seguro, saludable y productivo. En el PDF Estrategias para el fomento de una cultura de seguridad en el trabajo, se exploran estrategias clave para fomentar esta cultura, desde la formación continua y la comunicación efectiva, hasta la integración de tecnologías innovadoras y la participación activa de los empleados. A través de estas iniciativas, se busca no solo cumplir con las normativas vigentes, sino también construir un ambiente laboral en el que la seguridad sea un valor compartido, promoviendo el bienestar de los trabajadores y fortaleciendo el desempeño organizacional. Este material está diseñado para ofrecer una visión integral y práctica, impulsando a las organizaciones hacia la excelencia en seguridad laboral.

            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Estrategias para el fomento de una cultura de seguridad en el trabajo

          .col-lg-4
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema4/1.png', alt='')
    
    .bg-full-width.border-top.actividad.bg-color-actividad
      .p-4.p-md-5
        #Actividad                
          <Actividad :cuestionario="cuestionario"/>

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            //- Referencia con enlace 
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/53622" target="_blank" rel="noopener noreferrer") ISO (Organización Internacional de Normalización). (2017). ISO 14001:2015 para la pequeña empresa: ( ed.). AENOR - Asociación Española de Normalización y Certificación. 

            //- Referencia sin enlace 
            p.d-flex.my-4
              img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
              span Organización Internacional de Normalización. (2015). Sistemas de gestión de la calidad—Requisitos con orientación para su uso (ISO 9001).
            
            p.d-flex.my-4
              img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
              span Organización Internacional de Normalización. (2015). Sistemas de gestión ambiental- Requisitos con orientación para su uso (ISO 14001).
            //- Referencia de youtube 
            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://open.spotify.com/episode/6UwAofmRsGQxRtJpbAZHXa?si=LcJX7r3PRjqBZiVBfJmbCA" target="_blank" rel="noopener noreferrer") Cómo generar cultura preventiva desde la base Spotify. (s. f.). 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
</template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema3',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Matemática financiera',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              'En la formación continua, se sugiere la diversificación de métodos de enseñanza porque:  ',
            imagen: require('@/assets/actividad/imagen1.png'),
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Reduce costos de capacitación',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Ayuda a mantener la atención de los empleados',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Es más fácil para el facilitador',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Se limita a un solo estilo de aprendizaje',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto:
              'Si la empresa “Eléctricos Villanueva Orientales” tiene 300 trabajadores y necesita constituir el copasst. ¿Cuántos representantes por los trabajadores y empleador deben tener para que cumpla con la normatividad legal vigente?',
            imagen: require('@/assets/actividad/imagen2.png'),
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'un representante por cada una de las partes',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'tres representantes por cada una de las partes ',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'dos representantes por cada una de las partes',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'cuatro representantes por cada una de las partes.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto:
              'La empresa cocos del valle quiere establecer un SG-SST basado en cultura preventiva ¿Cuál es el primer paso fundamental para establecer una cultura de seguridad laboral?',
            imagen: require('@/assets/actividad/imagen3.png'),
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Comprar equipos de protección',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Establecer el compromiso de la alta dirección',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Contratar supervisores de seguridad',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Realizar inspecciones periódicas',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto:
              '¿Qué elemento es esencial para mantener una comunicación efectiva en seguridad laboral?',
            imagen: require('@/assets/actividad/imagen4.png'),
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Reuniones mensuales obligatorias',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Canales de comunicación bidireccionales',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Reportes escritos únicamente',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Comunicación exclusiva entre supervisores',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto: 'La capacitación en seguridad laboral debe ser:',
            imagen: require('@/assets/actividad/imagen1.png'),
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Solo al inicio del contrato',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Únicamente cuando ocurren accidentes',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Continua y actualizada regularmente',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'Una vez al año',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
        ],
        mensaje_final_aprobado:
          '¡Felicidades! Has superado la prueba con éxito.',
        mensaje_final_reprobado:
          'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
      },
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.bg-color-actividad
  background-color: #EBF1F5
</style>
