FROM python:3.12.3-alpine
                
LABEL Role=site
        
RUN mkdir /Site

COPY site-groupe /Site

WORKDIR /Site
   
VOLUME ["/data"]

CMD python3 -m http.server 8090


