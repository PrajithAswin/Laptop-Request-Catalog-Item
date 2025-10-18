# 💻 Laptop Request Catalog Item

## 🧩 Overview
The **Laptop Request Catalog Item** project automates the process of requesting laptops within an organization using **ServiceNow’s Service Catalog**.  
It provides a **dynamic form**, **automated workflow**, and **reset functionality** — eliminating manual, error-prone processes and ensuring quick, efficient service delivery.

---

## 🚀 Features
- 🖥️ Dynamic catalog item for laptop requests  
- ⚙️ Real-time field behavior using **Catalog Client Scripts**  
- 🔁 Form reset functionality using:
  ```javascript
  function resetForm() {
      g_form.clearForm();
      alert("The form has been reset.");
  }
