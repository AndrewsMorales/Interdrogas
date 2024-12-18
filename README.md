# Interdrogas

Este proyecto desarrollado en **Symfony** tiene como objetivo crear un sistema complejo para la realización de pedidos a la empresa **Interdrogas**. El sistema está diseñado tanto para clientes como para transferencistas, permitiendo la creación de pedidos de manera cómoda, eficiente y en tiempo real. Los pedidos están basados en el inventario actualizado de **Siesa**, y permiten realizar confirmaciones de pedidos, consultar históricos y hacer un seguimiento de las facturas.

## Características Principales

### 1. **Gestión de Pedidos para Clientes y Transferencistas**
- **Pedidos desde el Lado del Cliente:** Los clientes pueden realizar pedidos cómodamente a través de una interfaz web, visualizando el inventario actualizado de productos.
- **Pedidos para Transferencistas:** Los transferencistas pueden realizar pedidos durante sus rutas, utilizando el mismo sistema, lo que garantiza que los pedidos estén alineados con el inventario de la empresa.
- **Confirmación en Tiempo Real en Siesa:** El sistema se integra con **Siesa**, lo que permite la confirmación instantánea de los pedidos a través de una **API REST** que comunica el sistema con Siesa para validar y registrar los pedidos de manera eficiente.
- **Histórico de Pedidos y Facturas:** El sistema permite consultar el historial de pedidos realizados, con detalles completos sobre cada factura y su estado actual, lo que facilita el seguimiento y control.

### 2. **Integración con Siesa**
- El sistema realiza operaciones de lectura y escritura sobre el inventario de **Siesa** utilizando una **API REST** para garantizar la sincronización en tiempo real.
- Cada pedido realizado es confirmado en Siesa, asegurando que los datos estén actualizados y sean correctos en ambas plataformas.

### 3. **Interfaz de Usuario Interactiva**
- **JavaScript y jQuery** se utilizan para proporcionar una interfaz dinámica y fácil de usar para los usuarios.
- **Twig** se emplea para las plantillas del lado del frontend, garantizando una visualización clara y ordenada de la información.
  
### 4. **Tecnologías Utilizadas**
- **Backend:** Desarrollado en **Symfony** para una arquitectura robusta y escalable.
- **Frontend:** Usando **JavaScript**, **jQuery** y **Twig** para una experiencia interactiva.
- **Base de Datos:** Utiliza **MySQL** para la gestión interna de datos y **SQL Server** para la integración con el sistema Siesa.
- **API REST:** Para la transacción y sincronización en tiempo real con el sistema de gestión de inventarios **Siesa**.

## Funcionalidades del Proyecto:
- **Gestión de Pedidos:** Permite realizar pedidos tanto para clientes como transferencistas, basados en el inventario actualizado de Siesa.
- **Confirmación en Tiempo Real:** Los pedidos son confirmados en tiempo real en Siesa a través de una API REST.
- **Histórico de Pedidos y Facturas:** Los usuarios pueden consultar pedidos pasados y sus facturas correspondientes.
- **Interfaz Dinámica:** El sistema cuenta con una interfaz web fácil de usar, desarrollada con **JavaScript** y **jQuery**, que mejora la interacción con el usuario.
  
## Conclusión

Este sistema de gestión de pedidos para **Interdrogas** integra de manera eficiente tecnologías modernas como **Symfony**, **JavaScript**, **jQuery**, **Twig**, **PHP**, **MySQL**, **SQL Server** y una **API REST** para garantizar la sincronización en tiempo real con Siesa. El sistema no solo optimiza la gestión de pedidos, sino que también proporciona a los clientes y transferencistas una experiencia fluida y actualizada en todo momento.

---

![fotoInterdrogas](https://github.com/user-attachments/assets/b2256ea8-2a4b-4196-a5de-5b8257d16ce4)
![image](https://github.com/user-attachments/assets/5ce3ff24-5b93-4acb-9ef2-33eb1e9d128a)
![image](https://github.com/user-attachments/assets/6cd8e2ac-9720-4017-ab83-4cafd4e8537c)
