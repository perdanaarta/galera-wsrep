FROM haproxy:latest

# Copy HAProxy configuration file into the container
COPY haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg

# Expose HAProxy port
EXPOSE 3306

CMD ["haproxy", "-f", "/usr/local/etc/haproxy/haproxy.cfg"]
