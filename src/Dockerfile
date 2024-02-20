FROM python:3.11
COPY ./ /src/site
WORKDIR /src/site
RUN pip install mkdocs
EXPOSE 8080
CMD ["mkdocs", "serve", "--dev-addr=0.0.0.0:8080"]