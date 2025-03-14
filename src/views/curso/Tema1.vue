<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Estrategias para la implementación de Sistema de Gestión de Seguridad y Salud en el Trabajo'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .bg-color-2.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto
          figure
            img(src='@/assets/curso/tema1/1.png', alt='')
        .col-lg
          .p-4
            p.mb-0(data-aos="fade-up") La implementación de un Sistema de Gestión de Seguridad y Salud en el Trabajo es esencial para garantizar un entorno laboral seguro y saludable, disminuyendo riesgos y promoviendo el bienestar de los trabajadores. En un contexto en el que las organizaciones enfrentan desafíos constantes relacionados con la seguridad laboral y la salud ocupacional, resulta crucial adoptar estrategias efectivas que no solo cumplan con la normativa vigente, sino que también fortalezcan la cultura de prevención y cuidado dentro de la empresa.

    .row.mb-5
      .col-lg-4.order-lg-2
        figure
          img(src="@/assets/curso/tema1/3.png", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        p.mb-4(data-aos="fade-left") La iniciativa de establecer un Sistema de Gestión de Seguridad y Salud en el Trabajo, no solo busca la protección de los empleados, sino que también se traduce en beneficios tangibles para la organización, como la reducción de accidentes laborales, el aumento de la productividad y la mejora del clima organizacional. 

        .bg-color-3.p-4(data-aos="fade-left").mb-4
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Para lograr una implementación exitosa, es fundamental desarrollar un enfoque integral que involucre la capacitación del personal, la identificación y evaluación de riesgos, así como la promoción de una comunicación abierta y efectiva, entre todos los niveles de la organización.

        p(data-aos="fade-left") En este sentido, se presentan diversas estrategias que abarcan desde la planificación y organización de recursos, hasta la evaluación continua del sistema, asegurando así su eficacia y adaptación a las necesidades cambiantes del entorno laboral. Esta introducción plantea la necesidad de un compromiso colectivo, en la búsqueda de ambientes de trabajo más seguros, donde la salud y la seguridad, sean prioridades compartidas por todos los involucrados.

    .row.mb-5
      .col-lg-4
        figure
          img(src="@/assets/curso/tema1/4.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left").mb-4 La seguridad y salud en el trabajo (SST) es un aspecto fundamental en la gestión empresarial, especialmente en un contexto como el colombiano, donde la protección de los trabajadores y la prevención de riesgos laborales son prioritarios para el desarrollo económico y social. 

        .bg-color-1.p-4(data-aos="fade-left").mb-4
          p(data-aos="fade-left") La implementación de un Sistema de Gestión de Seguridad y Salud en el Trabajo (SGSST) es una herramienta eficaz que permite a las organizaciones gestionar de manera adecuada los riesgos asociados a sus actividades.
          p(data-aos="fade-left").mb-0 El decreto 1072 del 2015 y la norma ISO 45001:2018, establecen los requisitos para un sistema de gestión eficaz, que promueve un entorno de trabajo seguro y saludable.

        p(data-aos="fade-left") Colombia ha establecido un marco normativo robusto que promueve la seguridad y salud en el trabajo. La Ley 1562 del 2012, que reforma el Sistema General de Riesgos Laborales, el decreto 1072 del 2015 y la resolución 0312 del 2019, que establece los lineamientos para la implementación del SGSST, son pilares fundamentales en esta área. La adopción de la ISO 45001, permite a las empresas alinear sus procesos a nivel internacional, facilitando la integración de los estándares globales en la realidad local.

    h3(data-aos="fade-left") Principios de la norma ISO 45001:2018

    p(data-aos="fade-left") La norma ISO 45001, enfatiza varios principios claves que deben ser considerados en la planificación y diseño del SGSST, entre los cuales se destacan:

    .bg-full-width.bg-color-info.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-10
            ImagenInfografica.color-primario(data-aos="zoom-in")
                template(v-slot:imagen)
                  figure
                    img(src='@/assets/curso/tema1/info1.png', alt='', style="max-width: 1083px;").mx-auto

                .bg-color-white.box-shadow.p-3(x="18%" y="17.5%" numero="1")
                  h5 Gestión de riesgos
                  p Fomenta un enfoque proactivo en la identificación y control de los riesgos laborales.

                .bg-color-white.box-shadow.p-3(x="100%" y="48.5%" numero="2")
                  h5 Participación de los trabajadores
                  p La incorporación de los empleados en el proceso, es fundamental para reconocer los peligros y encontrar soluciones efectivas.

                .bg-color-white.box-shadow.p-3(x="18%" y="88.5%" numero="3")
                  h5 Enfoque en el liderazgo
                  p El compromiso de la alta dirección, es vital para establecer una cultura de seguridad en la organización.

                .bg-color-white.box-shadow.p-3(x="78%" y="88.5%" numero="+")
                  h5 Mejora continua
                  p Promueve la revisión y evaluación constante, de los procesos, para mejorar el sistema.


    h3(data-aos="flip-up") Pasos para la planificación y diseño del SGSST

    h4(data-aos="fade-right") A. Compromiso de la alta dirección

    p(data-aos="fade-left") El punto de partida fundamental en el desarrollo de un SGSST, es el compromiso absoluto e incondicional de la alta dirección. Este compromiso no solo implica la mera declaración de intenciones, sino que se traduce en acciones concretas y en una dedicación visible y permanente hacia la creación de un entorno laboral seguro y saludable. Algunas de ellas son:

    .row.align-items-center.mb-5
      .col-lg-5
        figure
          img(src="@/assets/curso/tema1/5.png", alt="", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-7
        p(data-aos="fade-left") El enfoque colaborativo tiene múltiples beneficios en la resolución de conflictos:

        LineaTiempoD.color-primario.large(data-aos="fade-left")
          p(numero="1" titulo="Asumir una postura proactiva") La alta dirección debe asumir una postura proactiva, garantizando que se asignen los recursos necesarios, tanto humanos como materiales, para llevar a cabo esta estrategia. Esto significa que la gerencia no solo debe destinar un presupuesto apropiado, sino también asegurar que se cuente con la infraestructura adecuada, tecnología, formación y capacitación continua que respalde las iniciativas de seguridad y salud en el trabajo.
          p(numero="2" titulo="Establecer políticas claras y bien definidas") Es crucial que se establezcan políticas claras y bien definidas que prioricen la seguridad y salud de todos los colaboradores de la organización. Estas políticas deben ser comunicadas de manera efectiva y accesible, de modo que todos los empleados comprendan su importancia y se sientan motivados a participar activamente en su implementación.
          p(numero="3" titulo="Definir roles y responsabilidades") Para que el sistema de gestión funcione de manera efectiva, es necesario que se definan claramente los roles y responsabilidades de cada miembro de la organización. Esto implica delinear quiénes son los responsables de la supervisión de las prácticas de seguridad, la gestión de riesgos y la atención de la salud laboral, así como establecer mecanismos de coordinación entre diferentes departamentos.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12
        .bg-color-1.p-4(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/6.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 El compromiso de la alta dirección es la piedra angular sobre la cual se construye un sistema de gestión de seguridad y salud en el trabajo efectivo. Sin este apoyo claro y decidido, será difícil alcanzar los objetivos propuestos y, lo que es más importante, asegurar el bienestar de todos los colaboradores en el ámbito laboral.


    h4(data-aos="fade-right") B. Evaluación y diagnóstico de la situación actual

    p(data-aos="fade-left") Antes de avanzar en el diseño y la implementación efectiva del Sistema de Gestión de la Seguridad y Salud en el Trabajo (SGSST), resulta indispensable llevar a cabo una evaluación exhaustiva y meticulosa, del estado actual de la organización, en relación con la seguridad y salud laboral. Los pasos son:

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white(data-aos="zoom-in")
          .row.align-items-center.p-4.p-md-5
            .col-lg-5
              figure
                img(src="@/assets/curso/tema1/slider-1.png")
            .col-lg-7
              h5 Diagnóstico inicial
              p Realizar un diagnóstico inicial no solo es fundamental, sino que se convierte en la piedra angular sobre la cual se fundamenta  el desarrollo de un sistema que sea tanto eficiente como plenamente alineado a las normativas y regulaciones vigentes que rigen esta materia.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5
              figure
                img(src="@/assets/curso/tema1/slider-2.png")
            .col-lg-7
              h5 Discutir
              p Discutiremos sobre el impacto de las estrategias de implementación del Sistema de Gestión de Seguridad y Salud en el Trabajo, en el cumplimiento de objetivos más amplios, como el bienestar social y la calidad de vida de los trabajadores. Las empresas en Colombia, tienen un papel fundamental en la promoción de ambientes laborales seguros y saludables, trascendiendo la mera obligación legal para convertirse en actores comprometidos con el desarrollo social. La revisión de casos prácticos locales nos brindará herramientas para comprender y aplicar efectivamente, estas estrategias en contextos reales.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5
              figure
                img(src="@/assets/curso/tema1/slider-3.png")
            .col-lg-7
              h5 Organizar
              p Organizaremos un espacio de reflexión crítica y análisis colaborativo. Se espera que los participantes desarrollen habilidades analíticas y creativas en la formulación de estrategias para la implementación del Sistema de Gestión de Seguridad y Salud en el Trabajo, mediante un enfoque que fomente la mejora continua y la innovación en las prácticas de seguridad y salud laboral. A través de actividades teóricas y prácticas, se incentivará la capacidad de identificar soluciones efectivas y adecuadas a los desafíos específicos, que enfrentan las organizaciones en Colombia.

    h4.mb-5(data-aos="fade-right") C. Identificación y evaluación de riesgos

    .bg-full-width.bg-fondo-1
      .px-4.px-md-5.pb-md-3

        .row.mb-5
          .col-lg-4.order-lg-2
            figure
              img(src="@/assets/curso/tema1/8.png", data-aos="zoom-in").mb-4.mb-lg-0
          .col-lg-8.order-lg-1
            .bg-color-3.p-4(data-aos="fade-left").mb-4
              .row.align-items-start
                .col-lg-auto
                  img(src="@/assets/curso/tema1/7.svg", style="max-width: 90px").mx-auto
                .col-lg
                  p.mb-0 Dentro de los parámetros de los sistemas de gestión, se subraya la importancia crucial de identificar y evaluar los riesgos potenciales que pueden presentarse en el entorno laboral. La identificación de riesgos es un proceso fundamental para garantizar la seguridad y salud de los trabajadores, debido a que permite anticipar situaciones que podrían comprometer su bienestar. 

            p(data-aos="fade-left") Para realizar esta tarea, de manera efectiva, las organizaciones deben llevar a cabo un análisis integral de riesgos, que no solo considere las condiciones de seguridad relacionadas con la maquinaria, instalaciones y entorno laboral, sino que también incluya elementos igualmente relevantes. Debe:

        .row.justify-content-center.align-items-stretch.mb-5
          .col-lg-6.col-xl-6.mb-4(data-aos="zoom-in-up")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema1/9.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Técnicas creativas	
                p.mb-0 Factores psicosociales como el estrés laboral y las relaciones interpersonales; aspectos químicos relacionados con la exposición a sustancias químicas, agentes biológicos y factores organizacionales, que implican la cultura empresarial y la estructura jerárquica.
          .col-lg-6.col-xl-6.mb-4(data-aos="zoom-in-down")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema1/10.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Evaluar 
                p.mb-0 Factores psicosociales como iluminación, ruido, vibraciones y radiaciones, así como considerar fenómenos naturales, riesgos biomecánicos tales como movimientos repetitivos y manipulación manual de cargas, esfuerzos excesivos, riesgos de seguridad vial y riesgos locativos, entre otros.

    p(data-aos="fade-right").mb-5 Y estas son las normas a tener en cuenta:

    TabsC.color-secundario.mb-5(data-aos="zoom-in")
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Decreto 1072 del 2015" :icon="require('@/assets/bullets/icon-tab-c.svg')" )
        .row
          .col-md-6.col-lg-5.col-xl-4
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema1/11.png', alt='')
          .col-md-6.col-lg-7.col-xl-8.mb-4.mb-md-0
            h4 Decreto 1072 del 2015
            p Proporciona un marco normativo que establece directrices claras y precisas, sobre la gestión del riesgo en el ámbito laboral. Este decreto pone énfasis en la necesidad de considerar una variedad de variables que pueden afectar la salud y seguridad de los trabajadores, promoviendo una visión holística en la gestión de riesgos. La normativa se centra en la prevención y control de riesgos, impulsando a las organizaciones a ser proactivas en la identificación de peligros antes de que se materialicen en accidentes o enfermedades laborales.
        
          
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Decreto 1072 del 2015" :icon="require('@/assets/bullets/icon-tab-c.svg')" )
        .row
          .col-md-6.col-lg-5.col-xl-4
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema1/12.png', alt='')
          .col-md-6.col-lg-7.col-xl-8.mb-4.mb-md-0
            h4 Resolución 0312 del 2019
            p Complementa las disposiciones y añade un enfoque más detallado al definir criterios específicos para la identificación de riesgos, indicando que la participación activa de los trabajadores en este proceso es indispensable para alcanzar una comprensión más completa y precisa de los peligros presentes en el entorno laboral. Este involucramiento no solo permite que los trabajadores compartan su experiencia y conocimiento de las condiciones de trabajo, sino que también facilita la identificación de peligros que podrían pasar desapercibidos en un análisis superficial, contribuyendo a una evaluación más efectiva.
        
    .row.mb-5
      .col-lg-4.order-lg-2
        figure
          img(src="@/assets/curso/tema1/14.png", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        .bg-color-3.p-4(data-aos="fade-left").mb-4
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/13.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Es importante resaltar que la inclusión de los empleados en la identificación de riesgos, no solo mejora la efectividad del proceso de evaluación, sino que también contribuye a crear un ambiente laboral más seguro y saludable.  

        p(data-aos="fade-left") La participación activa fomenta la colaboración y la comunicación abierta entre los trabajadores y la gerencia, lo que a su vez fortalece el compromiso de todos los involucrados hacia la seguridad laboral. Al adherirse a los requerimientos establecidos por la normativa vigente, las organizaciones no solo cumplen con sus responsabilidades legales, sino que también sientan las bases para una cultura de prevención que prioriza el bienestar de sus trabajadores y promueve un entorno laboral positivo y saludable.

    h4(data-aos="fade-right").mb-5 D. Establecimiento de objetivos y metas

    .row.mb-5.align-items-stretch
      .col-lg-4
        .bg-color-4.p-4(data-aos="fade-left").h-100
          p.mb-0 Una vez completado el diagnóstico inicial y realizada la evaluación de riesgos en el entorno laboral, es fundamental proceder a la formulación de objetivos claros y alcanzables, que guiarán las acciones de mejora en materia de seguridad y salud en el trabajo (SST). Estos objetivos deben ser específicos, medibles, alcanzables, relevantes y temporales, lo que asegura que sean efectivamente implementables y evaluables en el tiempo.
      .col-lg-4
        figure.h-100
          img(src="@/assets/curso/tema1/15.png", data-aos="zoom-in")
      .col-lg-4
        .bg-color-3.p-4(data-aos="fade-left").h-100
          p.mb-0 Es imprescindible que los objetivos establecidos estén alineados con la política del SST de la empresa, garantizando así cohesión en todas las iniciativas y acciones a realizar. La integración de estos objetivos con los principios y valores corporativos facilita una comprensión más profunda de su importancia y fomenta un compromiso activo por parte de todos los empleados.

    p(data-aos="fade-left") Por ejemplo, un objetivo concreto podría ser la reducción del 20 % en la cantidad de accidentes laborales en un período de un año. Este objetivo no solo es específico y medible, sino que también contribuye a crear un ambiente de trabajo más seguro y saludable para todos los empleados. Además, puede ser desglosado en metas intermedias, como la implementación de capacitaciones trimestrales sobre prácticas seguras, la mejora de los equipos de protección personal o la realización de auditorías mensuales para identificar y mitigar riesgos.

    .row.mb-5
      .col-lg-4.order-lg-2
        figure
          img(src="@/assets/curso/tema1/17.png", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        .bg-color-1.p-4(data-aos="fade-left").mb-4
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/16.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Establecer estos objetivos y metas, no solo permite monitorear el progreso de la empresa en materia de seguridad y salud en el trabajo, sino que también promueve una cultura organizacional enfática en la prevención y la mejora continua.

        p(data-aos="fade-left") A través de este enfoque proactivo, la empresa estará mejor equipada para enfrentar los desafíos en seguridad y salud laboral, beneficiando tanto a la organización como a sus empleados.


    h4(data-aos="fade-right").mb-5 E. Creación de un plan de trabajo

    p(data-aos="fade-left").mb-4 Para conocer sobre este paso, lo invitamos a escuchar el siguiente podcast.

    .bg-full-width.bg-color-5.mb-5
      .p-4.p-md-5
        .row.justify-content-between.align-items-center
          .col-lg-6
            TarjetaAudio.color-primario.bg-color-white.mb-3(
              texto="Creación de un plan de trabajo"
              tiempo
              :audio="require('../../assets/curso/podcast/Podcast_1.mp3')"
            )
          .col-lg-5
            figure
              img(src="@/assets/curso/tema1/18.svg", data-aos="zoom-in")


    h4.mb-5(data-aos="fade-left") F. Capacitar y concientizar a los trabajadores 

    p.mb-5(data-aos="fade-left") La formación del personal constituye un aspecto esencial y fundamental en el diseño e implementación de un Sistema de Gestión de Seguridad y Salud en el Trabajo. Para garantizar un entorno laboral seguro y saludable, es crucial que todos los trabajadores reciban:

    .row.align-items-center.mb-5
      .col-lg-4
        figure(data-aos="zoom-in")
          img(src="@/assets/curso/tema1/19.png", alt="").mb-4.mb-lg-0
      .col-lg-8

        LineaTiempoD.color-primario.large(data-aos="fade-left")
          p(numero="1" titulo="Capacitación regular y continua") Esta capacitación se debe fundamentar en prácticas seguras y plenamente conscientes de los riesgos asociados a sus labores diarias. No solo debe abarcar los procedimientos específicos para realizar sus tareas de manera segura, sino también brindarles una comprensión integral de los peligros a los que pueden estar expuestos en su entorno laboral.
          p(numero="2" titulo="Programa de inducción") Un programa bien estructurado que debe incluir no solo la presentación de la importancia del sistema de gestión de seguridad y salud en el trabajo, sino también un detallado repaso de la normativa vigente y las políticas internas de la empresa que regulan la seguridad. Durante la inducción, los trabajadores deben ser informados sobre sus derechos y responsabilidades en materia de seguridad, así como sobre los recursos disponibles, como equipo de protección personal y acceso a servicios médicos.
          p(numero="3" titulo="Sesiones de formación periódicas") Implementación de sesiones de formación periódicas que mantienen a los empleados actualizados acerca de las mejores prácticas, las nuevas normativas y los avances en tecnología que puedan influir en la seguridad laboral. Estas formaciones deben ser interactivas y adaptadas a las necesidades específicas de cada puesto de trabajo, fomentando una cultura de seguridad proactiva donde los empleados puedan hacer preguntas, expresar inquietudes y compartir experiencias.
          p(numero="4" titulo="Simulacros de emergencia") Incorporar simulacros de emergencia y talleres prácticos, representa otra estrategia efectiva para reforzar el aprendizaje. A través de situaciones simuladas, los trabajadores pueden practicar sus respuestas ante incidentes, lo que aumenta su confianza y capacidad para actuar adecuadamente en caso de una emergencia real. 


    p(data-aos="fade-left").mb-5 El compromiso de la alta dirección también es un factor clave. Es esencial que los líderes de la organización no solo apoyen la formación en seguridad y salud, sino que también participen activamente en ella, demostrando así su compromiso con el bienestar de sus empleados. Al cultivar un ambiente donde la seguridad es una prioridad compartida, se fomenta una mayor responsabilidad entre todos los miembros del equipo.


    .row.mb-5
      .col-lg-4.order-lg-2
        figure
          img(src="@/assets/curso/tema1/21.png", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        .bg-color-1.p-4(data-aos="fade-left").mb-4
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/20.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Es importante evaluar y medir la efectividad de los programas de formación en seguridad y salud. Esto permite realizar ajustes necesarios y asegurarse de que la capacitación sea relevante y efectiva, adaptándose a los cambios en el entorno laboral y a nuevas normativas.

        p(data-aos="fade-left") En resumen, la formación continua del personal en temas de seguridad y salud no solo es un requisito legal, sino una inversión en el bienestar de los empleados y el futuro de la organización.


    h4(data-aos="fade-right").mb-5 G. Preparación y respuesta ante situaciones de emergencia

    p(data-aos="fade-right").mb-5 La prevención y preparación ante emergencias son componentes esenciales en el diseño del Sistema de Gestión de la Seguridad y Salud en el Trabajo (SGSST). Un enfoque proactivo en la identificación y mitigación de riesgos, permite a las organizaciones salvaguardar la integridad de sus trabajadores y asegurar la continuidad de sus operaciones. Para ello, es fundamental desarrollar y mantener un plan de emergencias que contemple la identificación de posibles situaciones de riesgo, como incendios, desastres naturales, accidentes industriales, entre otros. Este plan incluye:

    TabsC.color-secundario.mb-5(data-aos="zoom-in")
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Análisis de riesgos exhaustivo" :icon="require('@/assets/bullets/icon-tab-c-2.svg')" )
        .row
          .col-md-6.col-lg-5.col-xl-4
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema1/22.png', alt='')
          .col-md-6.col-lg-7.col-xl-8.mb-4.mb-md-0
            h4 Análisis de riesgos exhaustivo
            p La primera etapa del plan consiste en realizar un análisis de riesgos exhaustivo, que incluya la evaluación de los escenarios más probables y sus posibles impactos. Esto se complementa con la capacitación periódica del personal en temas de seguridad, asegurando que todos los trabajadores conozcan los procedimientos a seguir en caso de una emergencia. La creación de equipos de respuesta y la designación de roles claros son igualmente importantes para asegurar una respuesta eficaz ante cualquier eventualidad.
        
          
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Simulacros regulares" :icon="require('@/assets/bullets/icon-tab-c-2.svg')" )
        .row
          .col-md-6.col-lg-5.col-xl-4
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema1/23.png', alt='')
          .col-md-6.col-lg-7.col-xl-8.mb-4.mb-md-0
            h4 Simulacros regulares
            p Es imprescindible incluir simulacros regulares que permitan a los trabajadores familiarizarse con los protocolos de evacuación y respuesta rápida. Estos ejercicios no solo fortalecen la preparación individual, sino que también fomentan una cultura de seguridad dentro de la organización. También se deben considerar medios de comunicación claros y efectivos para alertar y coordinar acciones en caso de emergencia.
            
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Monitoreo y revisión constante" :icon="require('@/assets/bullets/icon-tab-c-2.svg')" )
        .row
          .col-md-6.col-lg-5.col-xl-4
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema1/24.png', alt='')
          .col-md-6.col-lg-7.col-xl-8.mb-4.mb-md-0
            h4 Monitoreo y revisión constante
            p Complementa las disposiciones y añade un enfoque más detallado al definir criterios específicos para la identificación de riesgos, indicando que la participación activa de los trabajadores en este proceso es indispensable para alcanzar una comprensión más completa y precisa de los peligros presentes en el entorno laboral. Este involucramiento no solo permite que los trabajadores compartan su experiencia y conocimiento de las condiciones de trabajo, sino que también facilita la identificación de peligros que podrían pasar desapercibidos en un análisis superficial, contribuyendo a una evaluación más efectiva.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12
        .bg-color-1.p-4(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/25.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 La prevención y preparación ante emergencias dentro del SGSST, son esenciales para crear un ambiente laboral seguro, minimizando riesgos y asegurando el bienestar de todos los colaboradores. Una cultura de seguridad sólida no solo protege a los trabajadores, sino que también fortalece la reputación y la sostenibilidad de la organización. 

    h4(data-aos="fade-right").mb-5 H. Reporte e investigación de incidentes, accidentes de trabajo y enfermedades laborales

    .row.mb-5

      .col-lg-8

        .bg-color-3.p-4(data-aos="fade-left").mb-4
          p(data-aos="fade-left").mb-0 El reporte e investigación de incidentes, accidentes de trabajo y enfermedades laborales dentro del Sistema de Gestión de la Seguridad y Salud en el Trabajo (SGSST), es fundamental para identificar las causas delictivas y prevenir futuros eventos negativos en el entorno laboral. 

        p(data-aos="fade-left") Este proceso implica la recopilación sistemática de datos, el análisis exhaustivo de las circunstancias que rodearon el incidente y la implementación de medidas correctivas y preventivas. Al fomentar una cultura de transparencia y aprendizaje organizacional, las empresas no solo cumplen con la normativa legal, sino que también protegen la salud de sus trabajadores y mejoran la productividad general. La efectiva comunicación de los hallazgos y la capacitación continua son esenciales para fortalecer la prevención y garantizar un ambiente laboral seguro.

      .col-lg-4
        figure
          img(src="@/assets/curso/tema1/26.png", data-aos="zoom-in")


    h4(data-aos="fade-right").mb-5 I. Rendición y evaluación de la Gestión en Seguridad y Salud en el Trabajo (SST)

    .row.mb-5
      .col-lg-4
        figure
          img(src="@/assets/curso/tema1/27.png", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8
        .bg-color-3.p-4(data-aos="fade-left").mb-4
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/28.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 La rendición de cuentas en SST, implica un compromiso por parte de la dirección hacia la transparencia y la responsabilidad en la implementación de políticas y prácticas que resguarden la salud y seguridad de sus empleados.  

        p(data-aos="fade-left") Esto incluye establecer protocolos claros para la identificación, evaluación y control de riesgos laborales, así como la creación de espacios de diálogo donde los trabajadores puedan expresar sus preocupaciones y sugerencias. Un enfoque participativo, donde los empleados están  involucrados en la toma de decisiones, potencia el grado de aceptación y efectividad de las medidas de SST, fomentando una cultura de seguridad en la que todos se sientan responsables y comprometidos.

    h4(data-aos="fade-right").mb-5 J. Implementar acciones preventivas y correctivas

    p(data-aos="fade-left").mb-5 La implementación de acciones preventivas y correctivas en Salud y Seguridad en el Trabajo (SST), es fundamental para garantizar el bienestar de los trabajadores y la integridad de las operaciones dentro de cualquier organización. Estas acciones no solo buscan minimizar los riesgos asociados a las actividades laborales, sino que también promueven un ambiente de trabajo saludable y productivo:

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white(data-aos="zoom-in")
          .row.align-items-center.p-4.p-md-5
            .col-lg-5
              figure
                img(src="@/assets/curso/tema1/slider-1-2.png")
            .col-lg-7
              h5 Evaluación de riesgos
              p Es crucial realizar una evaluación de riesgos que permita identificar los peligros potenciales en el lugar de trabajo. Esta evaluación debe ser sistemática y considerar todos los aspectos del entorno laboral, desde las condiciones físicas hasta los aspectos organizacionales. Una vez que se hayan  identificado los riesgos, es necesario priorizarlos en función de su probabilidad de ocurrencia y las posibles consecuencias que podrían derivarse de ellos.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5
              figure
                img(src="@/assets/curso/tema1/slider-2-2.png")
            .col-lg-7
              h5 Acciones preventivas
              p Estas acciones preventivas están orientadas a eliminar o reducir la probabilidad de que ocurran incidentes. Esto puede incluir la implementación de controles técnicos, como la mejora de la ventilación en áreas de trabajo donde se manejen sustancias tóxicas, o la adquisición de equipos de protección personal adecuados. Asimismo, es fundamental llevar a cabo capacitaciones regulares para el personal, asegurándose de que todos estén informados sobre las mejores prácticas, así como sobre la correcta utilización de los equipos y herramientas. La creación de una cultura de seguridad también es esencial, donde cada empleado se sienta empoderado para reportar condiciones inseguras y participar en la identificación de soluciones.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5
              figure
                img(src="@/assets/curso/tema1/slider-3-2.png")
            .col-lg-7
              h5 Acciones correctivas
              p Las acciones correctivas son aquellas que se implementan una vez que se ha producido un incidente, o se ha identificado un incumplimiento. Estas acciones buscan no solo atender la situación inmediata, sino también establecer medidas para evitar que se repita en el futuro. Esto podría implicar la revisión y modificación de procedimientos de trabajo, la implementación de nuevas medidas de control o la re-capacitación del personal en áreas específicas. Es fundamental llevar a cabo un análisis de causas raíz para entender por qué ocurrió el incidente y así abordar de manera efectiva las falencias existentes.


    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12
        .bg-color-1.p-4(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/29.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Acabamos de ver algunos de los pasos para la planificación y diseño de un Sistema de Gestión de la Seguridad y Salud en el Trabajo (SGSST), sin embargo, es importante mencionar que solo son algunas pinceladas, dado que un sistema de gestión tiene muchísimos más componentes que llevan a robustecer la gestión en seguridad y salud en el trabajo en las organizaciones. 

    .bg-full-width.bg-color-6
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7
            h2.mb-4(data-aos="flip-up") ISO 45001:2018
            p.mb-0(data-aos="fade-right") Se recomienda leer:
            p.mb-4 ISO 45001:2018, Organización Internacional de Normalización. (2018). Sistemas de gestión de seguridad y salud en el trabajo—Requisitos con orientación para su uso (ISO 45001).

            a.anexo.mb-4.bg-white.w-fit(href="https://www.iso.org/obp/ui/#iso:std:iso:45001:ed-1:v1:es" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#DBE7FC'}")
                img(src="@/assets/componentes/link.svg")
              .anexo__texto
                p <strong>Sitio web. </strong> ISO 45001:2018

          .col-lg-5
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema1/30.png', alt='')

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.iso.org/standard /63787.html" target="_blank" rel="noopener noreferrer") Organización Internacional de Normalización. (2018). Sistemas de gestión de seguridad y salud en el trabajo—Requisitos con orientación para su uso (ISO 45001)
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/225263" target="_blank" rel="noopener noreferrer") Cortés, J. M. (2018). Sistemas de gestión de la seguridad y salud en el trabajo (ISO 45001:2018): (1 ed.). Editorial ICB. 
 

            //- Referencia de youtube 
            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=qg8JR9B9sWc" target="_blank" rel="noopener noreferrer") IMQ Prevención. (2022, 10 enero). Webinar. Implantación de la norma ISO 45001

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.tabs-content
  background-color: $color-sistema-h
.img-infografica
  background-color: $color-adicional-1
</style>
