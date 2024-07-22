- Imagenes Utilizadass:

1)- natural-ce: https://hub.docker.com/r/softwareag/natural-ce

    Version: 9.3.1

2)- adabas-manager-ce: https://hub.docker.com/r/softwareag/adabasmanager-ce/tags

    Version: 9.2.0

3)- adabas-ce: https://hub.docker.com/r/softwareag/adabas-ce

    Version: 7.2.0


--------


- Documentacion:

1)- Permisos de ejecucion: 

    chmod +x adabasdb/start.sh adabas_manager/start.sh natural_ce/start.sh

2)- Docker:

    docker-compose build

    docker-compose up -d

3)- Verificar actividad de contenedores:

    docker ps


--------

- Estructura de la App:


        docker-compose.yml

            adabasdb/

                Dockerfile

                start.sh

                bin/

                    adabasdb_start_command # Archivo o Script de la App

            adabas_manager/

                Dockerfile

                start.sh

                bin/

                adabas_manager_start_command # Archivo o Script de la App

            natural_ce/

                Dockerfile

                start.sh

                bin/

                    natural_ce_start_command # Archivo o Script de la App



--------


Created By Matias O. Riedel