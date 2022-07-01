installed minikube
installed helm
created the robot-shop namespace
kubectl cretate namespace robot-shop
helm install robo-shop --namespace robo-shop .

kubect port-forward service/web 8080:8080 -n roboshop 

in order to be able to access the app from the browser in the host machine (outside the pod)
as an alternative the minikube load-balancer could be used to assign an external ip to the pod

![RoboshopAppUp](https://user-images.githubusercontent.com/12687143/176894835-1eb70e8c-89a4-4e7f-907d-307f7098bd5e.png)


![logo](https://user-images.githubusercontent.com/12687143/176907267-bfbb1501-d072-416c-93ee-38bf6f221745.png)
