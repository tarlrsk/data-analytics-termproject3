# Big Data Anlytics Course - Project 3

Perform data analytics using notebook tool.

Using data from MongoDB sample: sample_supplies

## Export data set

Use the package manager [mongodb-database-tools](https://www.mongodb.com/docs/database-tools/installation/installation/) to export data.

```bash
mongoexport --uri="mongodb+srv://<username>:<password>@<cluster>/sample_supplies" --collection="sales" --jsonArray --out=sales.json
```