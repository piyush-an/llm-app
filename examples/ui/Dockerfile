FROM python:3.10.12

RUN pip install streamlit python-dotenv

WORKDIR /app

COPY server.py ./

EXPOSE 8501

CMD ["streamlit", "run", "server.py", "--server.port", "8501"]