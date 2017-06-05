### ** DB Table Category **

---

| **Column ** | **Data Type** | **Comment** |
| :--- | :--- | :--- |
| category\_id | BIGINT | Category idetifier number |
| create\_by | VARCHAR\(50\) | Category created by a person |
| create\_time | TIMESTAMP | Time create category |
| update\_by | VARCHAR\(50\) | A person update category |
| update\_time | TIMESTAMP | Update time of category |
| rec\_state | INTEGER | Count status to prevent concurrency conflict |
| category | VARCHAR\(50\) | Product category |
| description | VARCHAR\(1000\) | Description of category |
| parent\_category | BIGINT | First layer of categoy |
| state | VARCHAR\(50\) | Category state \(A-Active, S-Suspend\) |
| url\_path | VARCHAR\(1000\) | Path of category |
| image\_path | VARCHAR\(1000\) | Image path of category |
| meta\_keywords | VARCHAR\(1000\) | Specific type of meta tag |
| meta\_description | VARCHAR\(1000\) | Description of meta tag |
| meta\_title | VARCHAR\(1000\) | Title of meta tag |
| name | VARCHAR\(1000\) | Category name |
| show\_in\_menu | BOOLEAN default false | Disply mode in menu |
| sort\_order | INTEGER default 0 | Sorting out category |



