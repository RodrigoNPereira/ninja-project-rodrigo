### Technical case - Data Ninja 
### Rodrigo Nascimento Pereira - Federal University of Itajubá

---

This project was made as a technical interview for Ninja Starutup Jobs.

This code analyzes data from TheLook E-commerce public dataset on BigQuery. It offers basic insights and visualizations on order behavior and cancellation rates.

**Requirements**

- `google-cloud-bigquery` installed
- Credentials file: (`rodrigo-ninja-project-779b537cf084.json`)
- Data Source: `bigquery-public-data.thelook_ecommerce.orders`

**Funcitionality**

The beggining of the structure was made for connecting to the BigQuery via credentials and being able to retriving the dataset for quick vizualization and the whole set for data analysis.

After this step, with the help of matplotlib-pyplot and pandas, it's possible to obtain graphs and show the data in a intiuitive form.

The graphs that were plotted with this code are in the images directory.

**Instructions of use**

For a personal experience and further study with data analysis, you must update the project ID with your own and changing the credentials as well. All of this is possible by creating a Google Cloud account and creating a new project.

**Contact**

This is a prototype and a tool for my personal study, but, if there's any questions, feel free to contact me via rodrigonpgmae@gmail.com