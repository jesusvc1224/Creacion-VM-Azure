# Creacion-VM-Azure
Creacion de una maquina virtual en Azure

Lo primero que debemos de realizar es ingresar en [Azure](https://portal.azure.com/#home).

## Paso 1

Dentro del menu principal de Azure, seleccionamos el icono de la maquina virtual.

![image](https://user-images.githubusercontent.com/105994812/175844296-2d375f19-5179-4b95-b6ed-9f793dfd585f.png)

## Paso 2

Dentro de Maquinas Virtuales, vamos a crear y seleccionamos crear una maquina virtual hospedada por Azure.

![image](https://user-images.githubusercontent.com/105994812/175845012-b66ded07-5d01-4b5f-be97-c3892c1408ed.png)

## Paso 4

### Dentro de la creacion de nuestra maquina virtual estaremos en los Datos basicos.

![image](https://user-images.githubusercontent.com/105994812/175845348-c8365b11-a033-49cb-8157-52c29661d30d.png)

- En el apartado de Suscripcion lo dejamos en Azure for students
- En Grupo de Recursos colocamos el nombre como queremos que se llame nuestro grupo de recursos en esta caso pondre Laboratorio1
- En nombre de maquina vamos a nombrar nuestra maquina virtual en este caso la nombre como Maquina1
- En region sleccionaremos en donde queremos que se encuentre nuestra maquina virtual, en este caso quiero que mi maquina virtual este alojada en el Oeste de Estados Unidos
- En opciones de disponibilidad la dejamos como este seleccionada al igual que en zona de disponibilidad, esto se refiere si queremos que este disponible en caso de que falle el centro de datos de Azure.

![image](https://user-images.githubusercontent.com/105994812/175846399-cf3b024c-8509-4d42-a894-7905c4a208aa.png)

- En tipo de seguridad lo dejamos en estandar
- En imagen seleccionaremos que sistemas operativo que queremos que corra nuestra maquina virtual, en este caso seleccionare Windows 10 Pro.
- En instancia de Azure de acceso puntual lo dejamos como esta.

![image](https://user-images.githubusercontent.com/105994812/175846776-85381784-f202-465b-be1b-b825d31db4d3.png)

- En tamaño selecionaremos el tipo de maquina que querremos, selecionando la memoria RAM que contendra nuestra maquina virtual, el cpu que tendra y tendremos el precio que costara la maquina virtual.

![image](https://user-images.githubusercontent.com/105994812/175846933-f03aeef0-ed60-40d3-99a1-3b9d48ecd87a.png)

- En este caso seleccionare la primera opcion.

![image](https://user-images.githubusercontent.com/105994812/175846903-7dd4678d-c652-4c43-8ae3-bd7fdb93e8d0.png)

### Ahora en cuenta de administrador escribiremos el nombre de usuarios de nuestra maquina virtual, al igual que ingresaremos una contraseña.

En Reglas de puerto de entrada dejamos las opciones que estan seleccionadas.

![image](https://user-images.githubusercontent.com/105994812/175847411-7f393f1d-330a-47ec-bcfe-ca17427ae681.png)

Y en licencias seleccionamos la casilla.

![image](https://user-images.githubusercontent.com/105994812/175847475-3337d86b-b7eb-4e89-900a-da3dc76df251.png)

Y damos Siguiente.

## Paso 5

En el apartado de Disco dejamos tal cual este seleccionado.

![image](https://user-images.githubusercontent.com/105994812/175848340-ccaae4bd-367e-4beb-b402-e475dd48ece1.png)

## Paso 6

En redes dejamos como predeterminado todo.

![image](https://user-images.githubusercontent.com/105994812/175848426-e06eaff0-dc57-4274-8480-058deda49fea.png)

## Paso 7

En administración dejamos las opciones que estan por determinado.

![image](https://user-images.githubusercontent.com/105994812/175848583-ae8ef256-2850-45de-a1d1-87f989d42558.png)

## Paso 8

Dejamos las opciones que estan previamente seleccionadas.

![image](https://user-images.githubusercontent.com/105994812/175848688-0cc06919-5d70-4424-a98b-9720432a4846.png)

## Paso 9

En Etiquetas podemos dejar las opciones vacias o llenarlas con los datos de Nombre junto con un valor.


Como ejemplo:

![image](https://user-images.githubusercontent.com/105994812/175848996-48d74b99-d63b-469c-81e0-a35451f15e14.png)

## Paso 10

Continuamos con Revisar y crear, donde nos dara un resumen con los datos de la maquina virtual que crearemos, al igual que el costo que este tendra por su uso en hgoras.

![image](https://user-images.githubusercontent.com/105994812/175849114-c41d64e5-e1ad-4a05-83d6-39b83894bb18.png)

### Y damos en crear.

![image](https://user-images.githubusercontent.com/105994812/175849215-3824245f-5c0a-4cf2-bb47-f01e97aab5c4.png)

Nos mostrara que nuestra maquina virtual a sido creada.

![image](https://user-images.githubusercontent.com/105994812/175849523-d40fe0a0-5ec6-44a1-a8a3-3507fca9c376.png)

## Paso 11

Ahora veremos y ejecutaremos nuetra maquina virtual.


Vamos a ir al recurso.

![image](https://user-images.githubusercontent.com/105994812/175849667-e8237003-b948-4526-bfd9-d7fdf6a13d52.png)

Seleccionamos conectar

![image](https://user-images.githubusercontent.com/105994812/175849865-8309046f-2fc8-4288-aa0b-0aca20fc4820.png)

Y vamos a RDP.

![image](https://user-images.githubusercontent.com/105994812/175849964-705036a4-582a-4434-9625-37108dce232d.png)

Y descargamos el archivo RDP

![image](https://user-images.githubusercontent.com/105994812/175850065-cc0f8f6b-c0ce-42bf-8584-d0905d2da021.png)

Ahora ejecutaremos el archivo RDP que descargamos.

![image](https://user-images.githubusercontent.com/105994812/175850184-cfdb2d54-c921-4726-83f3-fa494a411e30.png)

Nos saldra una ventana emergente, la cual daremos en conectar.

![image](https://user-images.githubusercontent.com/105994812/175850347-5eee70c6-5870-4795-9686-42975dc975b2.png)

Nos pedira que ingresemos nuestros datos para iniciar sección, los cuales son los que determinamos al crear nuestra maquina virtual.

![image](https://user-images.githubusercontent.com/105994812/175850801-7dcbc659-c51a-4718-b1e1-e75e4d7cb32b.png)

Nos conectara a nuestra maquina virtual.

![image](https://user-images.githubusercontent.com/105994812/175850952-463512d3-7528-4b03-9100-7e53a297e0bd.png)

Nos pedira aceptar y certificado y concetarnos, le daremos en conectarse de todos modos.

![image](https://user-images.githubusercontent.com/105994812/175851027-576094c2-5d4a-457f-bf44-551f457700a2.png)

Ya estaremos iniciando nuestra maquina virtual.

![image](https://user-images.githubusercontent.com/105994812/175851129-d4caef3e-be6c-4c23-a002-973590be5e13.png)

Damos en aceptar.

![image](https://user-images.githubusercontent.com/105994812/175851223-e53d02d1-2735-4f08-8694-f507d6abc452.png)

Y listo ya estaremos dentro de nuestra maquina virtual.

![image](https://user-images.githubusercontent.com/105994812/175852003-50204a03-4dfa-4a61-b038-66ddb6b3130e.png)

