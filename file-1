notebook_df = spark.sql(
    """
    SELECT *
    FROM `uma-catalog`.default.my_table
    WHERE id = 1
    """
)
path_value = notebook_df.collect()[0]['path']
print(path_value)
dbutils.notebook.run(path_value, 600)
