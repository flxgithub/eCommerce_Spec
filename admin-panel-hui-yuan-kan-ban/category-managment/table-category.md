### ** DB Table Category **

---

| **Column ** | **Data Type** | **Comment** |
| :--- | :--- | :--- |
| category\_id | BIGINT | Category idetifier number  |
| create\_by | VARCHAR\(50\) | Category created by a person  |
| create\_time  | TIMESTAMP | Time create category  |
| update\_by  | VARCHAR\(50\) | A person update category  |
| update\_time | TIMESTAMP | Update time of category |
| rec\_state | INTEGER | Count status to prevent concurrency conflict |
| category  | VARCHAR\(50\) | Product category  |
| description  | VARCHAR\(1000\) | Description of category  |
| parent\_category  | BIGINT |  |
| state | VARCHAR\(50\) |  |
| url\_path  | VARCHAR\(1000\) |  |
| image\_path  | VARCHAR\(1000\) |  |
| meta\_keywords | VARCHAR\(1000\) |  |
| meta\_description | VARCHAR\(1000\) |  |
| meta\_title  | VARCHAR\(1000\) |  |
| name  | VARCHAR\(1000\) |  |
| show\_in\_menu | BOOLEAN default false |  |
| sort\_order | INTEGER default 0 |  |



