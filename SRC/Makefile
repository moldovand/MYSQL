CFLAGS=`mysql_config --cflags --libs`

all: Create_DB Create_Populate Last_Row_ID Retrieva_Data

Create_DB: Create_DB.c
	gcc Create_DB.c -o Create_DB $(CFLAGS)

Create_Populate: Create_Populate.c
	gcc Create_Populate.c -o Create_Populate $(CFLAGS)

Last_Row_ID: Last_Row_ID.c
	gcc Last_Row_ID.c -o Last_Row_ID $(CFLAGS)

Retrieva_Data: Retrieva_Data.c
	gcc Retrieva_Data.c -o Retrieva_Data $(CFLAGS)
