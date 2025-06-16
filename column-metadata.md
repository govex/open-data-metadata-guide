# Column Metadata

Although column metadata is often limited or left out entirely, it is very helpful to data consumers who frequently work with, write software for, or analyze datasets. Column metadata attributes provide important details about the data which the column contains. Many open data portals include the necessary tools to create column metadata when publishing new data.

* **Name**: Human-readable name of the column. It should be in plain English and usually a word, or a few words at the most.
* **Description**: Human-readable description of the column’s contents. This description should include how values in this column are created or updated; address any data quality concerns, such as unexpected or unusual values;, and explain any meanings which might be stored as codes,often used for record classification, and more frequent in source data systems designed for limited storage space.
* **Data Type**: Specifying a data type helps improve the consistency and quality of data. Common data types are text, numbers, dates/times, booleans (yes/no or true/false), and geometry (points, lines, polygons). Some open data portals will prevent records from being added or updated if the type of a value is incorrect.
* **Required**: Specifying whether a value is required in the column for every row in the table helps improve the quality of data. Some open data portals will prevent records from being added or updated if the column is marked as required but the datum was not included.
* **Machine Name**: Machine-readable version of the column’s Name. This is often a copy of the Name, with changes that make it suitable for computer software to use. These changes may include replacing spaces with underscores (or removing them entirely), applying [camel-case](https://en.wikipedia.org/wiki/CamelCase), and/or ensuring it is unique from other column names.

