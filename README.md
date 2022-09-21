This repo creates a local DBs on my machine using SQLITE.

The SQLite DB that contains a patient table with 8 columns.

Dummy patient data table is created using sqlite3.

The creations of fake patient data is coded in the files "createDB.py" and "connectDB.py"

The flask app is connected to the local SQLite DB in this repo

Inside the flask app, a route called ‘/patients’ display the list of
patients retrieved from the SQlite DB.

The flask app will be deployed to a VM on GCP.
