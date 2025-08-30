FROM python:3.11-slim
WORKDIR /app
COPY . .
RUN pip install --upgrade pip
RUN pip install numpy pandas matplotlib seaborn scipy jupyter ipywidgets pybind11 pytest
CMD ["python3", "python/core/engine_wrapper.py"]
