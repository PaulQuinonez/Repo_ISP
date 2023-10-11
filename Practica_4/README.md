# Practica 4
# Diagrama Entidad Relacion:
![Evidencia 1](<./Evidencias/1.jpg>)

### Aplicar servicio REST (aplicar por lo menos 2 métodos del CRUD) basado en la entidad transaccional asignada en su trabajo autónomo.
![Alt text](./Evidencias/image-1.png)

### Instalar minikube sobre Docker https://minikube.sigs.k8s.io/docs/start/
![Alt text](./Evidencias/image-2.png)


### Definir configuraciones y secretos para los parámetros de su base de datos y servicio REST.
![Alt text](./Evidencias/image-3.png)
![Alt text](./Evidencias/image-4.png)
![Alt text](./Evidencias/image-5.png)

### Definir el Deployment y el Service para levantar su servicio REST y Base de Datos.
![Alt text](./Evidencias/image-6.png)
![Alt text](./Evidencias/image-7.png)

### Aplicar los siguientes comandos para aplicar su configuración con minikube:

#### kubectl apply -f [file-name].yml para aplicar un archivo específico a la configuración
![Alt text](./Evidencias/image-8.png)


#### kubectl get all para mostrar el estado de su configuración.
![Alt text](./Evidencias/image-9.png)

#### kubectl logs pod/[name-pod] para obtener los logs de un elemento específico
![Alt text](./Evidencias/image-10.png)
![Alt text](./Evidencias/image-11.png)

#### kubectl rollout restart deployment
![Alt text](./Evidencias/image-12.png)

###  kubectl rollout restart service
![Alt text](./Evidencias/image-13.png)

#### minikube service backend-service cuando desee exponer el servicio para poder probarlo
![Alt text](./Evidencias/image-14.png)
![Alt text](./Evidencias/image-15.png)
