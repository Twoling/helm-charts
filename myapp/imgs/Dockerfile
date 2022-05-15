FROM busybox:latest

RUN mkdir /data/ && \
	echo 'myapp: v3' > /data/index.html && \
	ln -sv /etc/hostname /data/hostname.html

CMD ["httpd", "-f", "-h", "/data/"]
