# Instalacion de Jmeter

The Apache JMeter™ application is open source software, a 100% pure Java application designed to load test functional behavior and measure performance. It was originally designed for testing Web Applications but has since expanded to other test functions. 

### Requirements

<b>Java Version</b>

JMeter requires a fully compliant JVM 8, we advise that you install latest minor version of those major versions. Java 9 is not tested completely as of JMeter 3.2.

<strong>Operating Systems</strong>

JMeter is a 100% Java application and should run correctly on any system that has a compliant Java implementation.

En nuestra consola usamos el siguiente comando :

$ sudo apt-get update<br>
$ sudo apt-get install jmeter



![GitHub Logo](https://github.com/jdcr1425/munin_new/blob/master/imgs/Captura%20de%20pantalla%20de%202017-12-01%2006-33-54.png?raw=true)


<strong> ------------------------------------------------------------------------PRUEBAS------------------------------------------------------------------------------------- </strong>

Instalaremos Apache en nuestra maquina, para poder hacer las pruebas en nuestro localhost.
Usaremos Ansible para instalarlo, usaremos el rol apache y lo instalaremos con el scrpt de ansible *install_apache.yml* para hacer esto.


## Preparacion de los bancos de prueba

![GitHub Logo](https://github.com/jdcr1425/munin_new/blob/master/imgs/pruebas.png?raw=true)

#### se prepararon 9 pruebas

##### 1 usuario 10 peticiones 

![GitHub Logo](https://github.com/jdcr1425/munin_new/blob/master/imgs/1usuario10.png?raw=true)

##### 1 usuario 100 peticiones

![GitHub Logo](https://github.com/jdcr1425/munin_new/blob/master/imgs/1usuario100.png?raw=true)




