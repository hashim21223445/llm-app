FROM python:3.15-rc-alpine3.22

WORKDIR /app

RUN pip install streamlit python-dotenv

COPY . .

EXPOSE 8501

CMD ["streamlit", "run", "server.py", "--server.port", "8501", "--server.address", "0.0.0.0"]
