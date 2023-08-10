The data processing is identical to the chain before, but the whole process is split into two **chain velds**:

- veld_db.yaml

  Runs a database, so that the other velds can load into it, but the user can also inspect / modify
  the data via the database's interface.

- veld_load.yaml

  Runs through the whole processing pipeline as in the other chains before, and loads the final data into
  the running BaseX database.

