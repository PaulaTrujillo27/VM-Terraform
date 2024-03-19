  # Despliegue de Máquina Virtual en Azure con Terraform
  
# Descripción 
Este proyecto tiene como objetivo crear una máquina virtual en azure utilizando terraform.

# Desarrollo

Una vez que se ha definido la Infraestructura como Código (IaC) utilizando Terraform, donde se obtiene una dirección IP pública para nuestra VM y se habilita la gestión por SSH en el archivo principal, podemos observar que este contiene:

- Grupo de recursos de Azure.
- Red virtual de Azure.
- Subred de Azure.
- IP pública de Azure.
- Interfaz de red de Azure.
- Grupo de seguridad de red de Azure.
- Asociación de grupo de seguridad de red de Interfaz de red de Azure.
- Regla de seguridad de red de Azure.
- Máquina virtual de Azure.
- Disco de sistema operativo de almacenamiento.

# Comandos:

- Inicializar el directorio de trabajo para trabajar con Terraform: terraform init
- Validar la configuración de Terraform: terraform validate
- Visualizar y validar los cambios necesarios para aplicar la configuración de la infraestructura: terraform plan
- Aplicar un formato al archivo de definición creado con Terraform: terraform fmt
- Crear la infraestructura: terraform apply
- En caso de necesitar eliminar la infraestructura, se utiliza el comando: terraform destroy

# Comprobación:

- Terraform init

![image](https://github.com/PaulaTrujillo27/VM-Terraform/assets/71205932/8d70d3f6-a966-4007-ae1e-7e831debaccf)

- Terraform Validate

![image](https://github.com/PaulaTrujillo27/VM-Terraform/assets/71205932/86cac900-36ac-462e-aec3-d62c0d106b74)

- Terraform Plan

![image](https://github.com/PaulaTrujillo27/VM-Terraform/assets/71205932/28261d62-9ab4-4815-a900-ef453ab3ebe3)
![image](https://github.com/PaulaTrujillo27/VM-Terraform/assets/71205932/29a4a18a-855f-4514-94c8-97192e3bf36a)

- Ver la máquina en Azure

![image](https://github.com/PaulaTrujillo27/VM-Terraform/assets/71205932/1014b014-57ef-49f6-8b64-2ee1a5f928b1)

- Dirección IP Pública

![image](https://github.com/PaulaTrujillo27/VM-Terraform/assets/71205932/9a3ab0c2-87cc-4c72-8144-6a8d14512203)

- Acceder a la máquina desde SSH desde local

![image](https://github.com/PaulaTrujillo27/VM-Terraform/assets/71205932/07af6101-7df3-4710-a747-2d4a046a88fc)
![image](https://github.com/PaulaTrujillo27/VM-Terraform/assets/71205932/d38402ad-794c-4599-8078-78656470518e)
















