# Fabric Databricks UC Mirroring automation

Notebooks to help automate creation of Databricks Mirrored item in Microsoft Fabric.

- [Query UC and Create Items based on UC tag of domain, with schema input required](./Notebooks/UCMirroring_Sync.ipynb)
- [Query UC and Create Items based on user input item name , with schema input required](./Notebooks/UCMirroring_Sync_itemnamer.ipynb)
- [Helper notebook to help troublehshoot UC integration and Fabric settings](./Notebooks/AutomationHelper.ipynb)

Notebooks cannot be run twice, as an error occurs if the same mirror item name is created. Delete the mirrored item to run again.

Refresh of mirrored item will update schema of existing tables.

TODO: Create the ability to input specific lists of schemas and tables so that you can filter the incoming UC data, to create highly customised mirror items with a subset of a schema, in the abscence of tags.




