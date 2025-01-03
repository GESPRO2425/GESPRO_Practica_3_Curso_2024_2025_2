![header](https://cloud.githubusercontent.com/assets/6546265/22174630/785cdf04-dfe3-11e6-8cf4-024e8dc1c051.png)

[![ZenHub](https://raw.githubusercontent.com/ZenHubIO/support/master/zenhub-badge.png)](https://zenhub.com)
[![Build Status](https://travis-ci.org/davidmigloz/go-bees.svg?branch=master)](https://travis-ci.org/davidmigloz/go-bees)
[![codecov](https://codecov.io/gh/davidmigloz/go-bees/branch/master/graph/badge.svg)](https://codecov.io/gh/davidmigloz/go-bees)
[![Code Climate](https://codeclimate.com/github/davidmigloz/go-bees/badges/gpa.svg)](https://codeclimate.com/github/davidmigloz/go-bees)
[![SonarQube](https://sonarqube.com/api/badges/gate?key=go-bees%3Amaster)](https://sonarqube.com/dashboard/index/go-bees%3Amaster)
[![Dependency Status](https://www.versioneye.com/user/projects/57f7b19e823b88004e06ad33/badge.svg?style=flat-square)](https://www.versioneye.com/user/projects/57f7b19e823b88004e06ad33)
[![Documentation Status](https://readthedocs.org/projects/go-bees/badge/?version=develop)](http://go-bees.readthedocs.io/es/develop/?badge=develop)

## License

Copyright (c) 2016 - 2017 David Miguel Lozano

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

-Rodrigo Portugal Hortigüela y Adrián Carrera Calzada-

Guía de cómo se realiza toda la secuencia de acciones desde que nos posicionamos en un nuevo commit del repositorio Go Bees hasta que pasa a estar visible en nuestra rama master local

## 1º paso
Nos posicionaremos en el commit para poder subir cambios, tener MASTER al día y estar posicionado en master 

![image](https://github.com/user-attachments/assets/c80916c5-3d47-45de-833e-e333a3bd277f)

## 2º paso
Crearemos una rama a partir de una tarea que tenemos que crear con el nombre coincidente con el repositorio Go Bees

![image](https://github.com/user-attachments/assets/448b0264-f1ca-411c-9221-b4ff6421cd95)

![image](https://github.com/user-attachments/assets/ead9e993-584f-4ff9-800d-937035018f24)


## 3º paso
Nos posicionaremos en la rama en nuestro ordenador local dando doble clic sobre ella

![image](https://github.com/user-attachments/assets/72f57c6e-25e7-4a5e-990d-8d3a414809e9)

## 4º paso
En nuestro ordenador, nos dirigiremos a la dirección donde tengamos la carpeta de Go bees, y copiaremos todos los archivos de esa carpeta (excepto el .git) para pegarlos en la carpeta de nuestra práctica

![image](https://github.com/user-attachments/assets/bc27f811-2c0a-40eb-aeb2-71afada494a6)

![image](https://github.com/user-attachments/assets/355835be-e735-4c9c-8627-616ed7f6e682)

## 5º paso
Pulsaremos en view changes

![image](https://github.com/user-attachments/assets/71aa89d9-7eea-45d2-b540-985b20c82d3a)

Pulsaremos en Stage All Changes

![image](https://github.com/user-attachments/assets/8ea0eddd-98c4-4310-9d91-5da52b172762)

Y por último pulsaremos en Commit Changes 

![image](https://github.com/user-attachments/assets/f667eadd-7055-4b12-9d72-7497a4acfd5e)

Haremos un Fetch All

![image](https://github.com/user-attachments/assets/f232ead2-0a65-4ae0-a91e-b4a3fb1f9672)

Después un Pull (fast-forward if possible) 

![image](https://github.com/user-attachments/assets/ca5d8130-cdfd-45c5-93e4-679c06edd69e)

Y por último un Push

![image](https://github.com/user-attachments/assets/26ac4049-d3e1-4c13-91a2-4121a21c3f50)




## 6º paso: 

Iremos a Pull requests en Github y pulsaremos en Compare & pull request

![image](https://github.com/user-attachments/assets/3f1f0ac7-0363-4248-b375-b50c4954dcd7)

Pulsaremos en Create pull request

![image](https://github.com/user-attachments/assets/c8a6d1e5-70c9-4778-9329-ae1ae4344701)

Pulsaremos en Confirm merge

![image](https://github.com/user-attachments/assets/8cba1076-c739-492e-b49e-3523991568c3)

En esta última captura se verá el estado merged, confirmando que está bien
![image](https://github.com/user-attachments/assets/0ca7b9fc-8e8b-4501-b81d-5b2532f96f51)

## 7º paso:

Volvemos a hacer Fetch All

![image](https://github.com/user-attachments/assets/f232ead2-0a65-4ae0-a91e-b4a3fb1f9672)

Después un Pull (fast-forward if possible) 

![image](https://github.com/user-attachments/assets/ca5d8130-cdfd-45c5-93e4-679c06edd69e)



Y por último otro Push

![image](https://github.com/user-attachments/assets/26ac4049-d3e1-4c13-91a2-4121a21c3f50)

En esta captura se muestra cómo debe quedar el commit creado
![image](https://github.com/user-attachments/assets/4c5f1768-08f5-4f9b-9e0a-9cae60b45950)

## Captura del gráfico

![image](https://github.com/user-attachments/assets/f2bdaf4e-c777-498f-baee-d425f97fe3cb)
En esta captura aparece minor fix 152 como ultimo commit cuando no debería ser asi, pero esque cuando estabamos terminando nos dimos cuenta de que no se habia creado bien, porque tuvimos un problema, que cuando entramos en github para hacer la pull request se nos cambio de organización y se creo en una diferente a la que en la que debiamos haberla creado, por eso la volvimos a crear bien al final.
## Primer commit

![image](https://github.com/user-attachments/assets/4d283790-7158-45d3-a386-821819aeee70)

## Último commit

![image](https://github.com/user-attachments/assets/7efe3d9d-7333-4e3c-beca-28c7ca131c86)

## La información del proyecto de Github obtenida desde la opción de menú "Insights→Pulse" (10%):

![image](https://github.com/user-attachments/assets/cdbe1c24-a349-4310-87b5-42e2a205e89c)

![image](https://github.com/user-attachments/assets/44e8899f-3828-4baa-9c63-740cdf358ae1)

## La información del proyecto de Github obtenida desde la opción menú "Insights→ Code frequency" (10%)

![image](https://github.com/user-attachments/assets/aece03a8-51c3-449e-b55f-6f74adfbe311)

## Captura con la relación de las PRQs realizadas cerradas (10%)

![image](https://github.com/user-attachments/assets/a49a0947-4d6e-483f-b6ea-6bc0b0314f84)
