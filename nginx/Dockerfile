FROM nginx:latest

# Kopiér din Nginx-konfigurationsfil til containeren
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Tilføj en mappe til lydfilerne
RUN mkdir -p /usr/share/nginx/html/audio

# Eksponer port 80
EXPOSE 80
