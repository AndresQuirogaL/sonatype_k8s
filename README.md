# sonatype_k8s

Crear namespace:

~~~
$ kubectl create namespace sonatype
~~~

Levantar deployment:

~~~
$ kubectl create -f .
~~~

Verificar configuración de servicio iq-server:

~~~
$ kubectl describe service iq-server-service -n sonatype
~~~

Verificar configuración de servicio nexus3:

~~~
$ kubectl describe service nexus-service -n sonatype
~~~
