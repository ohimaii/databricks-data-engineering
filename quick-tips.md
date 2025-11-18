1. current_catalog(): This function returns the name of the catalog that is currently active in the session. Useful to know where you are and if you need to use three level namespace.

   Example: `SELECT current_catalog()`
   
2. current_schema(): This function returns the name of the schema that is currently active in the session. Useful to know where you are and if you need to use three level namespace.

   Example: `SELECT current_schema()`

3. LIST statement: This Databricks SQL statement works in Unity Catalog to list all the objects that are immediately contained at a URL. This URL could point to either managed or external storage locations.

   Example: LIST `/Volumes/folder00/folder01/final_folder`

