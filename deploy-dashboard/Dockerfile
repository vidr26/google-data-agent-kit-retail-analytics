FROM nginx:alpine
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY dashboard.html /usr/share/nginx/html/index.html
COPY dashboard.html /usr/share/nginx/html/dashboard.html
COPY launch_week_plan.md /usr/share/nginx/html/launch_week_plan.md
EXPOSE 8080
CMD ["nginx", "-g", "daemon off;"]
