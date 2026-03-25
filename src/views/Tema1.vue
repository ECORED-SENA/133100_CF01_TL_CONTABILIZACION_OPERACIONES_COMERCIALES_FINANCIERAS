<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Comerciante

    .row.justify-content-center.mb-5
      .col-lg-12(data-aos="zoom-in")
        .row.d-flex.align-items-stretch.bg-t1-1
          .col-xl-auto.pe-xl-0.mb-4.mb-xl-0.d-flex.d-none.d-lg-block
            figure.m-0.p-0.w-100.h-100.d-flex
              img(src='@/assets/curso/tema1/img1.png', alt='', class="w-100 h-100 object-fit-cover" style="margin-left: -10px;")
          .col-xl.d-flex
            .p-4.w-100.d-flex.align-items-center
              p.mb-0 Antes de hablar de empresa, sociedad y su clasificación, es importante enfocarse en el tema de comerciantes; sus deberes, derechos y obligaciones. Teniendo en cuenta que a partir de aquí comienzan a configurarse las actividades que se consideran mercantiles y son ejercidas por los comerciantes, se verán reflejadas en el momento de crear la empresa de acuerdo con el marco normativo vigente.
  
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Concepto y calidad

    p.mb-5 El concepto de comerciante, según el Código de Comercio, se define por el ejercicio profesional de actividades mercantiles, independientemente de si se actúa directamente o a través de terceros. La calidad de comerciante implica cumplir ciertos requisitos, como el registro en la Cámara de Comercio y la disponibilidad de un establecimiento abierto al público. Con la globalización y el avance tecnológico, el comercio ha evolucionado, dando paso a estrategias de marketing innovadoras y al auge del comercio electrónico, facilitado por dispositivos móviles y plataformas digitales.

    .video(data-aos="zoom-in")
      iframe(width="560" height="315" src="https://www.youtube.com/embed/Grpi6UZRWLM?si=btyjE1_LDnDWLJ3G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    Separador
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Deberes, derechos y obligaciones

    p.mb-5 De acuerdo con el Código de Comercio, es obligación de todo comerciante:

    .row.bg-t1-2
      .col-12
        .px-5
          .carousel-bg.mb-5
            .row.justify-content-center.align-items-center
              .col-lg-4.d-none.d-lg-block(data-aos="fade-right")
                figure
                  img(src="@/assets/curso/tema1/img2.png", alt="alt", style="width: 305px").m-auto
              .col-lg-8(data-aos="fade-left")
                SlyderF.custom.mb-5(columnas=" col-md-6 col-xl-6")
                  .tarjeta.tarjeta--slyder.p-4
                    .row.justify-content-center.mb-3
                      .col-8
                        img(src="@/assets/curso/tema1/img3.svg", alt='', style="width: 90px").m-auto
                    p.text-center.mb-2.bg-c6 #[b 01]
                    p.text-center.mb-0 Matricularse en el registro mercantil.

                  .tarjeta.tarjeta--slyder.p-4
                    .row.justify-content-center.mb-3
                      .col-8
                        img(src="@/assets/curso/tema1/img4.svg", alt='', style="width: 90px").m-auto
                    p.text-center.mb-2.bg-c6 #[b 02]
                    p.text-center.mb-0 Inscribir en el registro mercantil todos los actos, libros y documentos respecto de los cuales la ley exija esa formalidad.

                  .tarjeta.tarjeta--slyder.p-4
                    .row.justify-content-center.mb-3
                      .col-8
                        img(src="@/assets/curso/tema1/img5.svg", alt='', style="width: 90px").m-auto
                    p.text-center.mb-2.bg-c6 #[b 03]
                    p.text-center.mb-0 Llevar contabilidad regular de sus negocios conforme a las prescripciones legales.

                  .tarjeta.tarjeta--slyder.p-4
                    .row.justify-content-center.mb-3
                      .col-8
                        img(src="@/assets/curso/tema1/img6.svg", alt='', style="width: 90px").m-auto
                    p.text-center.mb-2.bg-c6 #[b 04]
                    p.text-center.mb-0 Conservar, con arreglo a la ley, la correspondencia y demás documentos relacionados con sus negocios o actividades.

                  .tarjeta.tarjeta--slyder.p-4
                    .row.justify-content-center.mb-3
                      .col-8
                        img(src="@/assets/curso/tema1/img7.svg", alt='', style="width: 90px").m-auto
                    p.text-center.mb-2.bg-c6 #[b 05]
                    p.text-center.mb-0 Denunciar ante el juez competente la cesación en el pago corriente de sus obligaciones mercantiles.

                  .tarjeta.tarjeta--slyder.p-4
                    .row.justify-content-center.mb-3
                      .col-8
                        img(src="@/assets/curso/tema1/img8.svg", alt='', style="width: 90px").m-auto
                    p.text-center.mb-2.bg-c6 #[b 06]
                    p.text-center.mb-0 Abstenerse de ejecutar actos de competencia desleal.

          p.mb-5 Respecto al último punto, además de considerar lo dispuesto en el Código de Comercio (Secretaría del Senado, 2020), también se considera lo dispuesto en las Normas sobre Competencia Desleal (Secretaría del Senado, 2020), donde se especifican las acciones que se consideran competencia desleal:

    .row.align-items-center.mb-5
      .col-lg
        .row.align-items-center
          .col-lg(data-aos="fade-right")
            ul.lista-ul--color
              li.d-flex
                i.fa-solid.fa-chevron-right
                |
                p.mb-0 Actos de desviación de la clientela.

              li.d-flex
                i.fa-solid.fa-chevron-right
                |
                p.mb-0 Actos de desorganización.
              li.d-flex
                i.fa-solid.fa-chevron-right
                |
                p.mb-0 Actos de confusión.

              li.d-flex
                i.fa-solid.fa-chevron-right
                |
                p.mb-0 Actos de engaño.

              li.d-flex
                i.fa-solid.fa-chevron-right
                |
                p.mb-0 Actos de descrédito.

              li.d-flex
                i.fa-solid.fa-chevron-right
                |
                p.mb-0 Actos de comparación.
          .col-lg(data-aos="fade-right")
            ul.lista-ul--color
              li.d-flex
                i.fa-solid.fa-chevron-right
                |
                p.mb-0 Actos de imitación.

              li.d-flex
                i.fa-solid.fa-chevron-right
                |
                p.mb-0 Explotación de la reputación ajena.

              li.d-flex
                i.fa-solid.fa-chevron-right
                |
                p.mb-0 Violación de secretos.

              li.d-flex
                i.fa-solid.fa-chevron-right
                |
                p.mb-0 Inducción a la ruptura contractual.

              li.d-flex
                i.fa-solid.fa-chevron-right
                |
                p.mb-0 Violación de normas.

              li.d-flex
                i.fa-solid.fa-chevron-right
                |
                p.mb-0 Pactos desleales de exclusividad.
      .col-lg-auto.d-none.d-lg-block(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema1/img9.png', alt='',).m-auto

    .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/tema1/icon1.svg" style="max-width: 60px").m-auto
      .col
        h3 Trámites legales para ejercer el comercio

    p.mb-5 El ejercicio del comercio implica cumplir con una serie de trámites legales que garantizan el cumplimiento normativo y la operatividad empresarial. Desde la verificación del nombre de la empresa hasta la afiliación de colaboradores a la seguridad social, cada paso es clave para el reconocimiento legal y la protección de los derechos comerciales, tributarios y laborales. Este proceso no solo facilita la formalización de los negocios, sino que también contribuye a un entorno empresarial más seguro y regulado.

    .video(data-aos="zoom-in")
      iframe(width="560" height="315" src="https://www.youtube.com/embed/n5Bv63FxmNY?si=qDXawDi9lK-DVoFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    Separador
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3 Registro mercantil

    .row.justify-content-center.align-items-center.mb-5
      .col-lg
        p.bg-t1-3.p-4(data-aos="zoom-in") El registro mercantil se tramita ante la Cámara de Comercio y su principal objetivo es identificar a los comerciantes y los establecimientos de comercio; por ende, al inscribirse se otorga la calidad de comerciantes. Así mismo, se registran todos los actos, libros y documentos respecto de los cuales la ley exigiere esa formalidad (Secretaría del Senado, 2020).
        p.mt-2 Para realizar la inscripción es importante identificar el tipo de empresa y/o sociedad que va a registrar, teniendo en cuenta determinar si se constituye bajo persona natural o jurídica. Esto para el diligenciamiento y presentación de los documentos pertinentes.
      .col-lg-auto.col-md-9(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema1/img10.png', alt='',).m-auto
    
    .fondo___slider.mb-5
      .px-5
        .ajuste-slider(data-aos="zoom-in")
          SlyderA(tipo="b")
            .row.justify-content-center.align-items-center
              .col-xl-6.mb-4
                figure
                  img(src='@/assets/curso/tema1/img11.png', alt='' style="max-width: 500px").m-auto
              .col-xl-6
                h4 Registro Único Tributario (RUT)
                p.mb-0 Es el documento que se tramita ante la Dirección de Impuestos y Aduanas Nacionales (DIAN), el cual relaciona la clasificación y responsabilidades del contribuyente.
            .row.justify-content-center.align-items-center
              .col-xl-6.mb-4
                figure
                  img(src='@/assets/curso/tema1/img12.png', alt='' style="max-width: 500px").m-auto
              .col-xl-6
                h4 Número de Identificación tributaria (NIT)
                p.mb-0 Es el número que se obtiene una vez se ha tramitado el RUT, el cual identifica al contribuyente ante las diferentes entidades de control y supervisión. En el caso de las personas naturales se encuentra compuesto por el número de documento de identidad y el dígito de verificación. En cuanto a la identificación del NIT de las personas jurídicas, la DIAN y la cámara de comercio mediante proceso realizan la asignación de 9 dígitos y el dígito de verificación.
            .row.justify-content-center.align-items-center
              .col-xl-6.mb-4
                figure
                  img(src='@/assets/curso/tema1/img13.png', alt='' style="max-width: 500px").m-auto
              .col-xl-6
                h4 CIIU
                p.mb-0 Es la clasificación de las actividades económicas de los empresarios del país de la manera más precisa. Las cámaras de comercio del país, a partir del año 2000, se rigen por la Clasificación Industrial Internacional Uniforme (CIIU) de todas las actividades económicas.
            .row.justify-content-center.align-items-center
              .col-xl-6.mb-4
                figure
                  img(src='@/assets/curso/tema1/img14.png', alt='' style="max-width: 500px").m-auto
              .col-xl-6
                h4 Persona natural
                p.mb-0 De acuerdo con el Artículo 74 del Código Civil, son todos los individuos de la especie humana, cualquiera que sea su edad, sexo, estirpe o condición. Las empresas que se constituyen bajo esta modalidad son integradas por una persona, quien adquiere los derechos y obligaciones. 
            .row.justify-content-center.align-items-center
              .col-xl-6.mb-4
                figure
                  img(src='@/assets/curso/tema1/img15.png', alt='' style="max-width: 500px").m-auto
              .col-xl-6
                h4 Persona jurídica
                p.mb-0 Es una persona ficticia, que contrae derechos y obligaciones. Dentro de esta figura se encuentran las sociedades comerciales. Por tanto, para ejercer la representación, se realiza mediante apoderado o representante legal.
            .row.justify-content-center.align-items-center
              .col-xl-6.mb-4
                figure
                  img(src='@/assets/curso/tema1/img16.png', alt='' style="max-width: 500px").m-auto
              .col-xl-6
                h4 Razón social
                p.mb-0 Es el nombre de la empresa, que se encuentra registrado en la cámara de comercio y demás entidades de control. Ejemplo: Nalsani SAS.
            .row.justify-content-center.align-items-center
              .col-xl-6.mb-4
                figure
                  img(src='@/assets/curso/tema1/img17.png', alt='' style="max-width: 500px").m-auto
              .col-xl-6
                h4 Razón comercial
                p.mb-0 Es el nombre que se asigna a la empresa, para darse a conocer ante el público o mercado. Ejemplo: Totto es el nombre comercial y su razón social es Nalsani SAS.
            .row.justify-content-center.align-items-center
              .col-xl-6.mb-4
                figure
                  img(src='@/assets/curso/tema1/img18.png', alt='' style="max-width: 500px").m-auto
              .col-xl-6
                h4 Registro de personas naturales:
                ul.lista-ul--color
                  li.d-flex
                    i.bg-icon-ul
                    p.mb-0.ms-2 Verificar el nombre o razón social que se va a asignar a la empresa. Donde se obtenga el certificado de homonimia. Este trámite hoy en día se puede realizar de forma virtual.
                  li.d-flex
                    i.bg-icon-ul
                    p.mb-0.ms-2 Diligenciar el formulario RUES.
                  li.d-flex
                    i.bg-icon-ul
                    p.mb-0.ms-2 Presentar el RUT.
                  li.d-flex
                    i.bg-icon-ul
                    p.mb-0.ms-2 La solicitud de registro se hará a más tardar un mes después de haber iniciado actividades comerciales.
                  li.d-flex
                    i.bg-icon-ul
                    p.mb-0.ms-2 Copia del documento de identidad de forma legible, además de presentar el original.
            .row.justify-content-center.align-items-center
              .col-xl-6.mb-4
                figure
                  img(src='@/assets/curso/tema1/img19.png', alt='' style="max-width: 500px").m-auto
              .col-xl-6
                h4 Registro de personas jurídicas:
                ul.lista-ul--color
                  li.d-flex
                    i.bg-icon-ul
                    p.mb-0.ms-2 Diligenciar el formulario RUES.

                  li.d-flex
                    i.bg-icon-ul
                    p.mb-0.ms-2 Presentar el documento privado o escritura de constitución de la sociedad.

                  li.d-flex
                    i.bg-icon-ul
                    p.mb-0.ms-2 Presentar el RUT.

                  li.d-flex
                    i.bg-icon-ul
                    p.mb-0.ms-2 La solicitud de registro se hará a más tardar un mes después de haber iniciado actividades comerciales.

                  li.d-flex
                    i.bg-icon-ul
                    p.mb-0.ms-2 Copia del documento de identidad de forma legible, además de presentar el original.

    p.mb-0 Cabe resaltar, que el comerciante debe realizar la inscripción en la cámara de comercio de la jurisdicción donde se encuentra ubicado el establecimiento de comercio. Una vez finalice el proceso se podrá obtener el certificado de registro mercantil. Así mismo, se debe realizar la renovación de la matrícula mercantil de forma anual, entre el 1 de enero al 31 de marzo de cada año.

    Separador
    #t_1_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.4 Cámara de Comercio: actos mercantiles

    .row.justify-content-center.align-items-center.mb-5
      .col-lg
        p.mb-3.bg-t1-5.p-4(data-aos="zoom-in") De acuerdo con el Código de Comercio, “Las cámaras de comercio son instituciones de orden legal con personería jurídica, creadas por el Gobierno Nacional, de oficio o a petición de los comerciantes del territorio donde hayan de operar. Dichas entidades serán representadas por sus respectivos presidentes” (Secretaría del Senado, 2020. Art. 78).
        p.mb-0 Estas instituciones tienen como objetivo llevar la matrícula de los comerciantes y sus establecimientos. En el Art. 86 del Código de Comercio (Secretaría del Senado, 2020), se establecen las siguientes funciones a las cámaras de comercio:
      .col-lg-auto.d-none.d-lg-block(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema1/img20.png', alt='', ).m-auto

    .row.align-items-center.mb-5
      .col-lg-6
        .row.align-items-center.justify-content-center.row-equal-height 
          .col-2
            figure
              img(src="@/assets/curso/tema1/img21.svg", alt="", style="width: 50px").m-auto
          .col-10
            p.mb-0 Servir de órgano de los intereses generales del comercio ante el Gobierno y ante los comerciantes mismos.
        hr.borde-num
      .col-lg-6
        .row.align-items-center.justify-content-center.row-equal-height 
          .col-2
            figure
              img(src="@/assets/curso/tema1/img22.svg", alt="", style="width: 50px").m-auto
          .col-10 
            p.mb-0 Adelantar investigaciones económicas sobre aspectos o ramos específicos del comercio interior y exterior y formular recomendaciones a los organismos estatales y semioficiales encargados de la ejecución de los planes respectivos.
        hr.borde-num
      .col-lg-6
        .row.align-items-center.justify-content-center.row-equal-height 
          .col-2
            figure
              img(src="@/assets/curso/tema1/img23.svg", alt="", style="width: 50px").m-auto
          .col-10
            p.mb-0 Llevar el registro mercantil y certificar sobre los actos y documentos en él inscritos, como se prevé en este código.
        hr.borde-num
      .col-lg-6
        .row.align-items-center.justify-content-center.row-equal-height 
          .col-2
            figure
              img(src="@/assets/curso/tema1/img24.svg", alt="", style="width: 50px").m-auto
          .col-10 
            p.mb-0 Dar noticia en sus boletines u órganos de publicidad de las inscripciones hechas en el registro mercantil y de toda modificación, cancelación o alteración que se haga de dichas inscripciones.
        hr.borde-num
      .col-lg-6
        .row.align-items-center.justify-content-center.row-equal-height 
          .col-2
            figure
              img(src="@/assets/curso/tema1/img25.svg", alt="", style="width: 50px").m-auto
          .col-10
            p.mb-0 Organizar exposiciones y conferencias, editar o imprimir estudios o informes relacionados con sus objetivos.
        hr.borde-num
      .col-lg-6
        .row.align-items-center.justify-content-center.row-equal-height 
          .col-2
            figure
              img(src="@/assets/curso/tema1/img26.svg", alt="", style="width: 50px").m-auto
          .col-10 
            p.mb-0 Rendir en el mes de enero de cada año un informe o memoria al Superintendente de Industria y Comercio acerca de las labores realizadas en el año anterior y su concepto sobre la situación económica de sus respectivas zonas, así como el detalle de sus ingresos y egresos.
        hr.borde-num

    .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/tema1/icon1.svg" style="max-width: 60px").m-auto
      .col
        h3 De los actos, operaciones y empresas mercantiles

    p.mb-5  De acuerdo con el Código de Comercio se consideran actos mercantiles los siguientes (Secretaría del Senado, 2020):

    .row.justify-content-center.mb-5
      .col-lg-3.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
        .tarjeta--boton.p-5.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/tema1/img27.svg', alt="" style="max-width: 90px").m-auto
          h3.text-center 01
          p.text-center.mb-0 La adquisición de bienes para enajenarlos o arrendarlos, dedicadas a la comercialización.
      .col-lg-3.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
        .tarjeta--boton.p-5.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/tema1/img28.svg', alt="" style="max-width: 90px").m-auto
          h3.text-center 02
          p.text-center.mb-0 Las operaciones financieras.
      .col-lg-3.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
        .tarjeta--boton.p-5.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/tema1/img29.svg', alt="" style="max-width: 90px").m-auto
          h3.text-center 03
          p.text-center.mb-0 Las empresas de servicios, que satisfacen necesidades.
      .col-lg-3.col-md-9(data-aos="zoom-in")
        .tarjeta--boton.p-5.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/tema1/img30.svg', alt="" style="max-width: 90px").m-auto
          h3.text-center 04
          p.text-center.mb-0 Las empresas industriales que se dedican a transformar materia prima en producto terminado.

    .row.bg-t1-7
      .col-12
        .p-5 
          .row.align-items-center
            .col-lg
              p.mb-3 Con el fin de ampliar la información, lo invitamos a explorar el siguiente recurso.
              a.anexo.mb-4.mb-lg-0(href="http://www.secretariasenado.gov.co/senado/basedoc/codigo_comercio_pr003.html" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")
                .anexo__texto
                  p #[b Enlace web]. Código de comercio 
            .col-lg-auto.col-md-9(data-aos="zoom-in")
              figure
                img(src='@/assets/curso/tema1/img31.svg', alt='', ).m-auto
</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
