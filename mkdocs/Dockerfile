FROM python:3
COPY ./Sosotech.Docs/ /Sosotech.Docs/

RUN pip install mkdocs

RUN mkdocs new Sosotech.Docs

EXPOSE 8000

WORKDIR /Sosotech.Docs/



ENTRYPOINT ["mkdocs"]

CMD ["serve", "--dev-addr=0.0.0.0:8000"]