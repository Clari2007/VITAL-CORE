# VITAL-CORE
>El presente proyecto, corresponde a la asignatura de Programación II, y busca implementar los conocimientos adquiridos durante el semestre en un programa que incluya pilares de POO, interfaces gráficas y manejo de archivos.
Nuestro grupo ha elegido crear un programa de atención médica hospitalaria, que incluya características cercanas a la realidad y desarrolle nuestras habilidades en programación.

## 🚀 Módulos
### Módulo de Login-Registro
Permite al usuario crear una cuenta, o iniciar sesión; en el primer caso: el usuario ingresa su nombre, apellido, contraseña y tipo de cuenta: Paciente, Doctor o Farmacéutico (para los últimos dos casos se requieren credenciales de acceso)
Tras ingresar los datos, se genera un correo al usuario y se muestra en pantalla, después se usa este correo y contraseña para iniciar sesión y acceder a los módulos correspondientes.
### Módulo de Paciente 
El paciente puede agendar una cita con los doctores existentes, eligiendo una fecha y hora junto a su motivo de consulta. Si ya se ha atendido su cita, podrá recibir el medicamento de ser necesario para su tratamiento.
### Módulo de Médico
El médico atiende las citas agendadas, llena los campos acerca de gravedad, tratamiento y receta uno o varios medicamentos de ser necesario.
### Módulo de Farmacéutico
El farmacéutico es capaz de visualizar las recetas que requieren medicina y en función de ellas rellenar medicina (puede ser más de lo necesario).

## 🛠️Persistencia de datos
- usuarios.csv permite almacenar datos para el login, aquí se almacenan los correos creador junto a su contraseña (hasheada para mayor seguridad.
- citas.csv almacena información acerca de las citas agendadas: doctor a cargo, fecha y hora, motivo.
- recetas, pedidos-medicamentos.csv guarda los pedidos pendientes de medicamentos a entregar.
- inventario. csv permite guardar la información de los medicamentos en stock.

## 🖥️Interfaz Gráfica
Se utilizó el IDE de Netbeans por su versatilidad de clic and drop para crear interfaces gráficas. Para los diferentes módulos se utilizaron JFrames, con paneles normales o tipo scroll, labels, combobox, spinner, botones, tablas y ventanas emergentes que den interactividad al usuario.

## 📦 Clases y Pilares de POO
Siguiendo el diseño inicial del programa, se tenía en mente el uso de clases como enfermero, facturación, así como la implementación de interfaces, polimorfismo, etc; pero en la implementación y adecuación a un proyecto funcional, se modificaron algunos aspectos, sin embargo se hizo uso de *abstracción* al ocultar detalles de implementación, *encapsulamiento* creando métodos y clases privadas, mientras que la herencia se utilizó para las clases de médico y farmacéutico que derivan de personal médico. 

## 👾 Sobre el Proyecto
- Lenguaje usado: Java 
- IDE utilizado: NetBeans
- Repositorio y control de versiones: Git-Hub
## 💻Autores:
- Estefano Chávez
- Claris Delgado
- Alexis Mendieta
