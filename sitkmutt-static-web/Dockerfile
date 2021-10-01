FROM nginx:1.21.3-alpine

WORKDIR /usr/src/app/

COPY src/ /usr/src/app/
RUN npm install

EXPOSE 8080

CMD ["nginx", "/usr/src/app/radiance/index.html", "8080"]