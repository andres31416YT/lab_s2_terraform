#Ejercicio Semana 2 Infraestructura como codigo
Version con entrno "localhost"
#REQUISITOS:
    Docker
    Terraform
#Donde cambiar entorno?
    terraform.tfvars:
        entorno = "?"
        prefijo_nombre = "?"
        puerto_frontend = ?
        puerto_backend = ?
        puerto_db = ?
#Pasos para ejecutar
    #Inicializar terraform
        terarform init
    #Buscar errores
        terraform validate
    #Ver plan de accion
        terraform terraform plan
    #Ejecutar
        terraform apply