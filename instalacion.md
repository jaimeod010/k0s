# Instalación de k0s en un nodo.
## 1.- Descarga de k0s
``` 
curl -sSLf https://get.k0s.sh | sh
```
### Una vez descagado k0s podemos ver la version y el estado

Para seber la versión instalada:

```  
k0s version
```
![k0s](https://github.com/jaimeod010/k0s/blob/main/imagenes/k0s-version.png)
## 2.- Tenemos que instalarlo en el cluster.

```
k0s install controller --single
```
## 3.- Ya instalado en el cluster lo iniciamos y vemos el estado de k0s

```
k0s start
k0s status
```
![k0s](https://github.com/jaimeod010/k0s/blob/main/imagenes/k0s-status.png)
