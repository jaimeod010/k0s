# Comprobaciones
 
1.- Creamos un pod:

```
k0s kubectl kubectl apply -f nginx.yaml
 
```
  2.- Usamos  port-forward para tener conexion con el pod 
  
  
```
k0s kubectl port-forward pod/pod-nginx-1 8089:80
```

  3.- Usamos un curl para extraer el html de la pagina

```
   curl localhost:8089
```
 ![k0s](https://github.com/jaimeod010/k0s/blob/main/imagenes/curl-k0s.png)
