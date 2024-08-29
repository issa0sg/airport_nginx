FROM nginx:latest

RUN rm /etc/nginx/conf.d/default.conf

COPY nginx/nginx.conf /etc/nginx/nginx.conf

# Expose port 80 to the host
EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
