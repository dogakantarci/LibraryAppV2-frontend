# Nginx'in resmi imajını baz alıyoruz
FROM nginx:latest

# Frontend dosyalarını /usr/share/nginx/html dizinine kopyalıyoruz
# Bu dizin, Nginx'in varsayılan olarak statik dosyaları sunduğu dizindir
COPY ./LibraryAppV2-frontend/client /usr/share/nginx/html

# Nginx'i dinlemesi gereken portu belirtiyoruz (80)
EXPOSE 80
