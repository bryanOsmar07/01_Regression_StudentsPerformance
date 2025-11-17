## End to End ML Project - Regression Students Performance

docker run -it --rm -p 8888:8888 -p 5000:5000 jupyter/pyspark-notebook

git config --global user.name "<USER>"
git config --global user.email <CORREO>

git clone https://github.com/bryanOsmar07/01_Regression_StudentsPerformance.git

cd 01_Regression_StudentsPerformance/

pip install -r requirements.txt
python src/components/data_ingestion.py
python app.py

http://localhost:5000/predictdata
