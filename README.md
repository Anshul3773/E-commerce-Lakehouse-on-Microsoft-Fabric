# E-commerce Lakehouse on Microsoft Fabric

This project demonstrates an end-to-end solution for managing an e-commerce dataset using Microsoft Fabric's lakehouse architecture. The process includes creating a workspace, loading data, building a dimensional model, and developing a semantic model with auto-generated reports.

## Architecture Overview:

### Workspace and Lakehouse Creation: Established a workspace and lakehouse for data storage and processing.

![Screenshot (735)](https://github.com/user-attachments/assets/0477f3c7-38c0-47f9-9016-62bfb2db20d1)

![Screenshot (736)](https://github.com/user-attachments/assets/175ed37e-df68-4f29-be64-abf81880f106)

### Data Loading: Uploaded files and loaded the Bronze table (Sales) into the lakehouse.

![Screenshot (726)](https://github.com/user-attachments/assets/9cde38b5-e6ae-4386-a0fd-3999ade1df87)

![Screenshot (725)](https://github.com/user-attachments/assets/61eee4c5-b828-4a83-8f87-a3ae415b1d6c)


### Dimensional Modeling: Created and loaded multiple dimensions (Order Return, Order Priority, Ship Mode, Customer, Product, Date) into the Gold layer.

![Screenshot (727)](https://github.com/user-attachments/assets/7ef515d9-7388-4013-8972-42de341b5dbd)

![Screenshot (728)](https://github.com/user-attachments/assets/c984e190-3f0a-402d-887d-3fddf324c136)

![Screenshot (730)](https://github.com/user-attachments/assets/cd7eeac5-1864-4b30-bce0-de8d776b2911)

![Screenshot (731)](https://github.com/user-attachments/assets/d6264788-a8e9-4e5f-b3a8-73ba24374ee4)

![Screenshot (732)](https://github.com/user-attachments/assets/430d60c7-99b4-42fd-a77d-15c353a7d170)

![Screenshot (733)](https://github.com/user-attachments/assets/35c12282-9415-4f88-bf69-b803aab14bf8)

### Fact Table Loading: Loaded the Fact Sale dimension into the Gold layer.

![Screenshot (729)](https://github.com/user-attachments/assets/cde6c44c-cc98-4297-900a-bdbaca33bbbf)

### Notebook Execution and Archiving: Ran notebooks, mounted the lakehouse, and archived files.

![Screenshot (737)](https://github.com/user-attachments/assets/248643e9-049d-41c3-8623-6bfc2a54353a)


### Data Pipeline: Developed a pipeline to automate the final notebook execution.

![Screenshot (734)](https://github.com/user-attachments/assets/3b14cd4b-c490-453c-8cc2-ff4dbe447d66)

![Screenshot (724)](https://github.com/user-attachments/assets/b3003c23-247a-4ed7-ab05-810a50a4f5c6)

### Semantic Model and Reporting: Created a semantic model and generated auto-reports from it.

![Screenshot (721)](https://github.com/user-attachments/assets/868bb587-1ed4-42e8-83b8-7778cb3f5046)

![Screenshot (722)](https://github.com/user-attachments/assets/febb54d6-8417-4965-bffa-785c0eadbf8d)
