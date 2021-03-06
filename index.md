---

layout: col-sidebar
title: OWASP Queretaro City
tags: example-tag
region: South America
meetup-group: owasp-queretaro

---

![OWASPQUERETARO](/www-chapter-queretaro-city/assets/images/owasp-queretaro-city.png "OWASP QUERETARO")


## Bienvenidos al Bajio!

Alienados con la filosofía de OWASP, el capitulo de la ciudad de Queretaro busca generar un espacio para compartir conocimiento y acompañar a las personas interesadas en los múltiples proyectos de OWASP que ahora abarcan mucho más que información relacionada con seguridad en el desarrollo.

El capítulo Queretaro busca reunir a personas interesadas en desarrollo y seguridad que se encuentren en toda la region del Bajío. Si eres un apasionado de estos temas y te animas a compartir, por favor no dudes en contactarnos, estamos en busqueda de colaboradores para los futuros eventos. Hasta el momento el trabajo que hemos desarrollado en nuestro capítulo se ha desarrollado desde el área de seguridad y en este nuevo inicio nos encantaría contar con más desarrolladores de diferentes tecnologías contandonos desde sus perspectivas, desafios, experiencias y como abarcan o como podemos unir la seguridad para el bien de toda nuestra comunidad.

Es un gusto para nosotros arrancar este proyecto y esperamos poder contar con el apoyo de la comunidad, actores privados e instituciones privadas para promover los valores y objetivos OWASP en nuestra region.

## Próximos eventos ([meetup](https://www.meetup.com/owasp-queretaro))
{% include chapter_events.html group=page.meetup-group %}

<script type='text/javascript'>
  $(function(){
    $(".timeclass").hover(function() {
      utc_str = $(this).text();
      ndx = utc_str.indexOf(':');
      st_hour_str = utc_str.substring(0, ndx);
      st_min_str = utc_str.substring(ndx + 1, ndx + 3);
      utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(st_hour_str), parseInt(st_min_str), 0);
      start_dt = utc_dt.setZone(luxon.DateTime.local().zoneName);

      ndx = utc_str.lastIndexOf(':');
      end_hour_str = utc_str.substring(ndx - 2, ndx - 1);
      end_min_str = utc_str.substring(ndx + 1, ndx + 3);
      utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(end_hour_str), parseInt(end_min_str), 0);
      end_dt = utc_dt.setZone(luxon.DateTime.local().zoneName);
      popstr = start_dt.toLocaleString(luxon.DateTime.TIME_WITH_SECONDS) + ' to ' + end_dt.toLocaleString(luxon.DateTime.TIME_WITH_SHORT_OFFSET);
      $(this).prop('title', popstr);
    });
  });

  
</script>

## Reuniones
Se proponen reuniones trimestrales y grupos de estudio a formarse relacionados en temas de Seguridad Informatica. Se nombran alguno de ellos:

- Análisis de las nuevas tecnologías de la información y las comunicaciones.
- Análisis de productos (Software & Appliances).
- Investigación de fallas y vulnerabilidades.
- Desarrollo de programas y técnicas de exploit relacionadas.
- Documentación de soluciones de seguridad.
- Desarrollo de herramientas de seguridad.
- Demostraciones. Debates y desarrollo investigativo.

## Colabora
Hay muchas formas de colaborar y contribuir con el capitulo OWASP Guatemala.

- Participando en cualquiera de los proyectos actualmente activos (documentación y herramientas).
- Proponiendo nuevos proyectos.
- Participando y aportando ideas en nuestra lista de correo.
- Asistiendo a las conferencias y reuniones.
- Promoviendo y dando soporte al proyecto OWASP en general.
- Coffee Breaks y rifas en nuestros eventos.


## RTFM
The Open Web Application Security Project (OWASP) is a nonprofit foundation that works to improve the security of software. All of our projects ,tools, documents, forums, and chapters are free and open to anyone interested in improving application security. 

Chapters are led by local leaders in accordance with the [Chapter Policy](https://owasp.org/www-policy/). Financial contributions should only be made online using the authorized online donation button. To be a SPEAKER at ANY OWASP Chapter in the world simply review the [speaker agreement](https://owasp.org/www-policy/) and then contact the local chapter leader with details of what OWASP Project, independent research, or related software security topic you would like to present.

Everyone is welcome and encouraged to participate in our [Projects](/projects), [Local Chapters](/chapters), [Events](/events), [Online Groups](https://groups.google.com/a/owasp.com/){:target='_blank'}, and [Community Slack Channel](https://owasp.slack.com/){:target='_blank'}. We especially encourage diversity in all our initiatives. OWASP is a fantastic place to learn about application security, to network, and even to build your reputation as an expert. We also encourage you to be [become a member](/membership) or consider a [donation](/donate) to support our ongoing work.

