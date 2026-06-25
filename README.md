# CAMMAND FOR ACCOMPLISH THE PROJECT

   2 docker login                                                                                                                             
   3 docker build -f Dockerfilev1 -t manireet06/manireet/web:v1                                                                               
   4 docker build -f Dockerfilev1 -t manireet0607/manireet:v1                                                                                 
   5 docker build -f Dockerfilev1 -t manireet0607/manireet:v1 .                                                                               
   6 docker build -f Dockerfilev1 -t manireet0607/manireet:v1 .                                                                               
   7 ls                                                                                                                                       
   8 cd .\kubernetes_practice_web\                                                                                                            
   9 ls                                                                                                                                       
  10 docker build -f Dockerfilev1 -t manireet0607/manireet:v1 .                                                                               
  11 docker build -f Dockerfilev2 -t manireet0607/manireet:v2 .                                                                               
  12 docker build -f Dockerfilev3 -t manireet0607/manireet:v3 .                                                                               
  13 docker push manireet0607/manireet:v1                                                                                                     
  14 docker push manireet0607/manireet:v2                                                                                                     
  15 docker push manireet0607/manireet:v3                                                                                                     
  16 kubectl apply -f configmap.yaml                                                                                                          
  17 kubectl apply -f deployment.yaml                                                                                                         
  18 kubectl apply -f service.yaml                                                                                                            
  19 kubectl get pod                                                                                                                          
  20 kubectl get pod -w                                                                                                                       
  21 kubectl get deployment                                                                                                                   
  22 kubectl get service                                                                                                                                                                                                                                                                                                                                     
  25 kubectl set image deployment/web-deployment web=yourdockerhubusername/web:v2                                                             
  26 kubectl set image deployment/web-deployment web=manireet0607/manireet:v2                                                                 
  27 kubectl rollout status deployment/web-deployment                                                                                         
  28 kubectl port-forward service/web-service 8080:80                                                                                         
  29 kubectl set image deployment/web-deployment web=manireet0607/manireet:v3                                                                 
  30 kubectl port-forward service/web-service 8080:80                                                                                         
  31 kubectl port-forward service/web-service 8080:80    --
