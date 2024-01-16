# SWIIIRamosAlquiler
### Core Domain
* Gestión de Alquiler
* Gestión de Pagos
  
### Subdominio de apoyo
* Gestión de Clientes
* Gestión de Vehículos
### Subdominio genérico
* Gestión de Seguridad
## Bounded Contexts
* Gestión de Alquiler
* Gestión de Pagos
* Gestión de Clientes
* Gestión de Vehículos
* Autorización/Autenticación
* Gestión de Seguridad
 ## Patrones de Relacion
 * Cooperación: Gestión de Clientes 
 * Cliente - Provedor con capa anticorrupción: GestionPagosContext y GestionClientesContext, GestionPagosContext y GestionVehiculosContext
 * Cliente - Provedor con capa anticorrupción: GestionPagosContext y GestionClientesContext, GestionPagosContext y GestionVehiculosContext, AutorizacionAutenticacionContext y GestionSeguridadContext
* Cliente - Provedor conformista: AutorizacionAutenticacionContext y GestionAlquilerContext
