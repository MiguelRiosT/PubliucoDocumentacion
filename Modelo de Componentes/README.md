 #  Modelo de Componentes #


![Modelo de componentes](https://github.com/MiguelRiosT/S2Publiuco/blob/main/Modelo%20de%20Componentes/ModeloComponentesPubliuco.drawio.png)


 ## _Documentación_ ##

### Java project: ###
- **PubliucoDTO:** Componente que ofrece los objetos de transferencia de datos para poder intercambiar información entre el componente de API y el componente Service.

- **PubliucoCrossCutting:** Componente que ofrece características aspectuales que pueden ser utilizadas de forma general por cualquier componente de la aplicación Publiuco.

- **PubliucoEntity:** Componente que tiene todas las entidades de acceso a datos que serán utilizadas por el componente de repositorio para llevar a cabo las operaciones de acceso a datos.

- **PubliucoRepository:** Componente que ofrece los mecanismos de acceso a datos para el proyecto Publiuco.

- **PubliucoService:** Componente encargado de garantizar el cumplimiento de toda la lógica de negocio de la aplicación, asegurando que el dominio esté protegido de accesos no autorizados en la aplicación Publiuco.

- **UcoCrossCutting:** Componente que ofrece características aspectuales que pueden ser utilizadas de forma general por cualquier proyecto construido sobre Java versión 20.

### Spring Boot: ###

- **PubliucoApi:** Componente encargado de publicar Apis relacionados con los servicios de negocio ofrecidos por la aplicación Publiuco. 

### Significado de color de los componentes: ###

- **Azul**: Componentes externos de la aplicación
  - SpringBoot 3.0.6
  - Java 20

**Componente externo:** Hace referencia a un elemento o parte de la aplicación que no es desarrollado propiamente por el equipo de trabajo, este mismo se adquiere de fuentes externas.

Por lo tanto, un componente externo es aquel que se integra en el aplicativo pero no se desarrolla internamente.
  
- **Verde**: Componentes propios de la organización UCO.
  - UcoCrossCutting  

**Componente propio de una organización:** Hace referencia a un elemento o parte de la aplicación que es de una fuente proveniente de una organización que brinda los elementos necesarios para integrar al aplicativo.

- **Amarillo**: Componentes propios de la aplicación Publiuco.


  - PubliucoDTO
  - PubliucoCrossCutting
  - PubliucoEntity
  - PubliucoRepository
  - PubliucoService
  - PubliucoApi
  
**Componente propio del aplicativo:** Hace referencia a los elementos o partes de la aplicación que son desarrollados propiamente e internamente por el equipo de trabajo del aplicativo.
