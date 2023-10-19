FROM nginx:latest

WORKDIR /app/appv1

RUN apt-get update && apt-get upgrade -y && apt-get install python3 telnet git -y 

#RUN git clone https://github.com/andinhodantas/Projeto-mobile.git  /app/appv1 && /bin/bash

EXPOSE 80
CMD RUN git clone https://github.com/andinhodantas/Projeto-mobile.git  /app/appv1 && /bin/bash
#CMD ["nginx","-g","daemon off;" ]

#Bildar a imagem 
# docker bild -t (nome da imagem)

#docker tag nome:latest  andinhodantas/nome(anderson_mobile):latest (versão)

# docker push andinhodantas/nome(anderson_mobile):latest (versão)