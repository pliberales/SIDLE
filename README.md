# SIDLE: Sistema Informático Decentralizado de Listas Electorales
---

# Content Table
1. [Spanish](#Spanish)
   * [Requerimientos Principales](##Requerimientos-Principales)
   * [Requerimientos Secundarios](##Requerimientos-Secundarios)
   * [Versiones](##Versiones)
2. [English](#English)
   * [Main Requeriments](##Main-Requeriments)
   * [Secondary Requeriments](##Secondary-Requeriments)
   * [Versions](##Versions)

# Spanish

El SIDLE, Sistema Integral Descentralizado de Listas Electorales, es un gestor de listas electorales para partidos politicos, su objetivo es democratizar la construcción de las listas y de tal forma evitar las deficiencias que brindan los sistemas clasicos como son la elección primarias internas que conlleva la segmentación del partido y parcialidad de la creación de las listas (abocadas al interes del grupo ganador). El sistema es descentralizado, utilizando block chain, garantizando a la vez la transparencia y la auditoria.


## Requerimientos Principales

1.  Uso de metodología TDD, BDD y Clean Code para el desarrollo.
2.	Gestión de la base de datos del Proyecto o Partido, de forma descentralizada (Block Chain).
3.	Seguridad en el acceso y el manejo de los datos (doble verificación).
4.	Portal con UX/UI fácil de usar y entender. El mismo debe ser fácil de traducir (archivos de Lenguage)
5.	Permite el acceso a los afiliados del Proyecto o Partido únicamente.
6.	Los afiliados deberán tener la siguiente información (Nombre, Apellido, año de nacimiento, DNI/NIE, Nº Registro del partido/proyecto, Correo, Teléfono y Municipio)
7.	Permitir a los miembros elegir ser Candidatos.
8.	Los afiliados pueden dar +1, 0 o -1 por cada Candidatos, por defecto es (0), la valoración es secreta.
9.  Los afiliados pueden apreciar los rankings de los candidatos en todo momento. Seran visibles Nombre, Apellido, Listas alistadas y Municipio.
10.	Puede Detener las apreciaciones en días claves (días para presentación de listas).
11.	El sistema permite definir tipos de listas personalizadas (Municipales, CCAA, Nacionales, Europeas, etc).
12.	Los candidatos pueden alistarse a las listas.
13.	El sistema generá la lista de los candidatos ordenadas por la cantidad de valoraciones (promedial).
14.	Las valoraciones que esten en empate se apreciara por la cantidad de Positivo y Negativos.
15.	En caso de que los positivos y negativos sean iguales, se ordenara por Apellido.
16.	El sistema puede generar la listas candidatales automaticamente y se enviará a los afiliados interesados.
17.	En todo momento se deberá garantizar la transparencia del sistema mediante auditorias.
18.	Desasocia a los afiliados que han dejado el Partido, quita sus valoraciones.
  

## Requerimientos Secundarios

1.  Los miembros podrán ver una planilla personal de los candidatos, la información será aportada por el candidato, fotos, links y contenido multimedia.
2.	Permitir a los miembros elegir ser Jefes de campaña.
3.	Permitir a los candidatos solicitar a los Jefes de campaña dirigir sus campañas.
4.	Permitir a los Jefes de campaña aceptar o declinar su solicitud.
8.	Permitir a los Jefes de campaña solicitar dirigir las campañas a un candidato sin Jefe de campaña asignado.
6.	Permitir a los candidatos renunciar a su Jefe de Campaña.
7.	Perimtie a los jefes de campaña renunciar a sus candidatos.
8.	Los Jefes de Campaña y Candidatos Asociados podrán ver sus datos personales.
9.	Permitir a los candidatos dar valoración a los Jefes de Campañas (+1, 0 y -1).
10.	Deberá tener un ranking visible a todos los afiliados de los Jefes de campaña (Nombre, Apellido, Municipio, Asociado o No.)
11.	Tener un calendario de actividad e inactividad visible, con motivos.


## Versiones

### Versión en Desarrollo

- En Desarrollo la versión 0.0.1


### Versión Estable

- Ninguna versión estable

---

# English 

The SIDLE, Decentralized Integral System of Electoral Lists, is an electoral list manager for political parties. Its objective is to democratize the construction of lists and thus avoid the deficiencies provided by classical systems, such as internal primary elections that lead to party segmentation and partiality in list creation (focused on the interests of the winning group). The system is decentralized, using blockchain, guaranteeing both transparency and auditability.

## Main Requirements

1. Use of TDD, BDD, and Clean Code methodologies for development.
2. Management of the Project or Party database in a decentralized manner (Blockchain).
3. Security in data access and handling (double verification).
4. Portal with easy-to-use and understand UX/UI. It should be easily translatable (language files).
5. Access allowed only to Project or Party affiliates.
6. Affiliates must have the following information (Name, Last Name, Year of Birth, ID/NIE, Party/Project Registration Number, Email, Phone, and Municipality).
7. Allow members to choose to be Candidates.
8. Affiliates can give +1, 0, or -1 for each Candidate; by default, it is (0), and the evaluation is secret.
9. Affiliates can view candidate rankings at all times. Name, Last Name, Lists enlisted, and Municipality will be visible.
10. Can freeze evaluations on key days (days for list submission).
11. The system allows defining custom list types (Municipal, Regional, National, European, etc.).
12. Candidates can enlist in the lists.
13. The system generates the list of candidates ordered by the number of evaluations (average).
14. Tie evaluations will be appreciated based on the quantity of Positive and Negative evaluations.
15. In case Positive and Negative evaluations are equal, it will be ordered by Last Name.
16. The system can automatically generate candidate lists and send them to interested affiliates.
17. Transparency of the system must be guaranteed through audits at all times.
18. Disassociates affiliates who have left the Party, removes their evaluations.

## Secondary Requirements

1. Members will be able to see a personal sheet of the candidates; the information will be provided by the candidate, photos, links, and multimedia content.
2. Allow members to choose to be Campaign Managers.
3. Allow candidates to request Campaign Managers to lead their campaigns.
4. Allow Campaign Managers to accept or decline their request.
5. Allow Campaign Managers to request to lead campaigns for a candidate without an assigned Campaign Manager.
6. Allow candidates to resign from their Campaign Manager.
7. Allow Campaign Managers to resign from their candidates.
8. Campaign Managers and Associated Candidates will be able to view their personal data.
9. Allow candidates to rate Campaign Managers (+1, 0, and -1).
10. There must be a visible ranking to all affiliates of Campaign Managers (Name, Last Name, Municipality, Associated or Not).
11. Have a visible activity and inactivity calendar, with reasons.

## Versions

### Development Version

- In Development Version 0.0.1

### Stable Version

- No Stable Versions
