# Data-Engineer-Assignment

Install Pandas, SQLAlchemy and Metaflow using following cmd: 

pip install pandas
pip install sqlalchemy
pip install metaflow

Run these commands in the directory where python is installed, if using conda install using conda workspace. 

Install PostgreSQL to your machine. 

Open the script MetaflowETL.ipynb and change the values of username, password and database in the command

engine = create_engine('postgresql://username:password@localhost:5432/database')

Once the dependencies are installed run the following command in terminal: 

python MetaflowETL.py run
