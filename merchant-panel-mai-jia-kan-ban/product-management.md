### **Product Management **

---

Pre- Condition \(Add Product\)

1. Add **Brand** Name to system.
2. Add **Categories** to system. 
3. Add **Filter **group for each categories.  Example category for: Food supplement. \(Vitamin A, Vitamin B, Vitamin C\)
4. Add **Options** group for each product. Example A product: T-shirt \( size: X, M, L, XL\)
5. Add new **Product** to system.

1. | **Fields** | **Filter** | **Grid View** | **Condition ** |
   | :--- | :--- | :--- | :--- |
   | Brands                                 \(Add, Delete, Edit\) | Brand Name, Status | Brand Name, Action,          Status | First |
   | Categories                          \(Add, Delete, Edit\) | Auto fill in default               category, Status | Category Name, Action,       Status | Second |
   | Filter \(Add, Delete, Edit\) | Filter Name, Status | Filter Group, Action, Status | Forth |
   | Options \(Add, Delete, Edit\) | Option Group, Status | Option Group, Action,           Status | Fifth |
   | Product \(Add, Delete, Edit\) | Product Name, Model, Brand, Status | Product ID, Product Name,  Product Image, Quantity, Price, Action, Status  | Last  |

---

### **Add Product **

| **Fields** |  |
| :--- | :--- |
| Product Name\* |  |
| Product Description |  |
| Model\* |  |
| Category | If new category, submit for admin approval |
| Price |  |
| Quantity |  |
| Dimension \(L x W x H\) |  |
| Weight |  |
| Minimum Purchase Quantity |  |
| Status \(View Only\) |  |
|  |  |
| **Links Data ** |  |
| Category | Auto fill in complete. Condition: Must be approve by admin |
| Brands | Auto fill in complete. Condition: Must be approve by admin |
| Options | Auto fill in complete. Condition: Must be approve by admin |

##### \* cannot be empty

### 

### **Add Categories **

| **Fields ** | **Submit approval** |
| :--- | :--- |
| Category Name |  |
| parents |  |
| Filters |  |
| Image |  |



