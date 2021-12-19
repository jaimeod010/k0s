
k0s es una nueva distribución de Kubernetes. La versión actual es 0.8.0. Fue publicado en diciembre de 2020; el primer compromiso de todo el proyecto se realizó en junio de 2020.

k0s se envía como un único binario sin dependencias del sistema operativo. Por lo tanto, se define como una distribución de Kubernetes de cero fricción / cero deps / cero costo.

La última versión de k0s:

Envía un Kubernetes 1.19 certificado y (comparado con CIS)
Utiliza containerd como tiempo de ejecución de contenedor predeterminado
Admite arquitecturas Intel (x86-64) y ARM (ARM64)
Utiliza un etcd dentro del clúster
Utiliza el complemento de red Calico de forma predeterminada (habilitando así las políticas de red)
Habilita el controlador de admisión de políticas de seguridad de pod
Utiliza DNS con CoreDNS
Expone métricas de clúster a través de Metrics Server
Permite el uso de ajuste de escala automático horizontal de pod (HPA)
Tiempos de ejecución de Micro VM (con muchas ganas de probar este)
Actualizaciones de clústeres sin tiempo de inactividad
Copia de seguridad y restauración de clústeres
