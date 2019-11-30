# Movies-ETL

Code to Delete data from SQL Tables 

conn=sqlite3.connect('movies.db')   
curs=conn.cursor()
DELETE FROM movies
DELETE FROM ratings
conn.commit()
conn.close()
