### **DB Table Attribute**

---

| **Column** | **Data Type ** | **Comment ** |
| :--- | :--- | :--- |
| attribute\_id | BIGINT default  |  |
| create\_by | VARCHAR\(50\) |  |
| create\_time | TIMESTAMP |  |
| update\_by | VARCHAR\(50\) |  |
| update\_time | TIMESTAMP |  |
| rec\_state | INTEGER |  |
| attribute\_type | VARCHAR\(50\) |  |
| attribute | VARCHAR\(50\) |  |
| description | VARCHAR\(1000\) |  |
| parent\_attribute | VARCHAR\(50\) |  |

### DB Table -** Attribute Type**

---

| **Column ** | **Data Type ** | **Comment ** |
| :--- | :--- | :--- |
| type\_id | BIGINT default |  |
| create\_by | VARCHAR\(50\) |  |
| create\_time | TIMESTAMP |  |
| update\_by | VARCHAR\(50\) |  |
| update\_time | TIMESTAMP |  |
| rec\_state | INTEGER |  |
| attribute\_type | VARCHAR\(50\) |  |
| description | VARCHAR\(1000\) |  |
| parent\_attribute\_type | VARCHAR\(50\) |  |
| field\_type | VARCHAR\(50\) |  |
| editor\_type | VARCHAR\(50\) |  |
| editor\_label | VARCHAR\(1000\) |  |
| default\_value | VARCHAR\(1000\) |  |
| is\_required | VARCHAR\(1000\) |  |
| is\_user\_defined | BOOLEAN default false |  |
| is\_visible | BOOLEAN default false |  |
| is\_searchable | BOOLEAN default false |  |
| is\_filterable | BOOLEAN default false |  |
| position \_order | INTEGER default 0 |  |



