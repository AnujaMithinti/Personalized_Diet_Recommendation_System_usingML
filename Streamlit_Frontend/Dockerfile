# Frontend/Dockerfile

FROM python:3.10.8

RUN mkdir -p app/frontend

COPY Streamlit_Frontend app/frontend

WORKDIR /app/frontend

RUN pip install --upgrade pip
RUN pip install -r requirements.txt
RUN pip install altair==4.2.0


EXPOSE 8501

ENTRYPOINT ["streamlit","run"]

CMD ["Hello.py"]
