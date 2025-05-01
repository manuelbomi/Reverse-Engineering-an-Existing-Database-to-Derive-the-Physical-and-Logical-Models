# Data Architecture and Models: Reverse-Engineering-an-Existing-Database-to-Derive-the-Physical-and-Logical-Models

Data model reverse engineering is a data architecture approach through which Data Architects can create a database physical and/or logical model from an existing database. Database models graphically show the structure of a database so that Data Architects and decision makers can see how database elements, such as tables and views, relate to each other without showing the actual data. This process can help to streamline creating a new database or understanding the structure of an existing one.

In this discourse, a data model that is existing in a MS SQL Server database is reversed engineered to yield the data physical and logical models. ER/Studio is used for the reverse engineering procedure. 

---
> [!IMPORTANT]
> Methods of creating logical and physical data models (using ER-Studio) without reverse engineering could be found here: manuelbomi/Data-Architect-Procedure-for-Designing-a-Scalable-Logical-Data-Model-with-ER-Studio and here: manuelbomi/Data-Architect-Procedure-for-Scalable-Physical-Models-and-Database-Deployment-with-ER-Studio
> A very short video that explains how to configure the MS SQL Server Authentication method is available here: https://www.youtube.com/watch?v=-UY0fHckkGc
> 
---
#### To reverse engineer an existing MS SQL Server database, open the ER/Studio software, go to 'File',  'New' and  select 'Reverse engineer an existing database'
![Image](https://github.com/user-attachments/assets/cce74d69-f98d-4dda-b3bd-fc78975e2e6a)

---
#### Click login. Provide login info and click next. Navigate to your database list and select database of interest.

![Image](https://github.com/user-attachments/assets/8b803bfb-e0f9-4502-bbf2-54506ecfd086)

---
####  Add it to selected databases and select all object of interest in the database to include
![Image](https://github.com/user-attachments/assets/003983ed-42a5-4a8c-8c2e-d746db4b7e71)
---

#### Ensure that your selected objects contains all database objects that you desire to select 
![Image](https://github.com/user-attachments/assets/cf0a69fb-0331-40dc-b55a-0a4d01c23381)

---
#### Select other possible options as you wish 
![Image](https://github.com/user-attachments/assets/d2543711-28ec-42a3-ab90-b50c00001ff0)

---

#### This is the summary of the database to reverse 
![Image](https://github.com/user-attachments/assets/8f198b50-e2ae-462f-9b54-21e6f9e1557c)
---
#### Reverse engineering process
![Image](https://github.com/user-attachments/assets/215a396c-ac79-4e88-ad90-36517a4798ba)
---


![Image](https://github.com/user-attachments/assets/54eecb0e-8c0b-47e2-a688-464fa358a6ac)
---
![Image](https://github.com/user-attachments/assets/7a937d3b-8780-4091-b24e-f0cc9fcee8db)

---
#### Both logical and physical models are now available
![Image](https://github.com/user-attachments/assets/1039f493-96dc-47aa-a3c1-3278ea0b5d9b)
----
![Image](https://github.com/user-attachments/assets/d65d1a91-79d5-4adb-9ea0-1df3002c52b7)




---
Thank you for reading through

---

Author's Background

```

Author's Name:  Emmanuel Oyekanlu
Skillset:   I have experience spanning several years in developing scalable enterprise data pipelines, architecting enterprise data solutions,
data engineering, machine learning, NLP and LLM applications as well as deploying scalable solutions (apps) on-prem and in the cloud.
I can be reached through: manuelbomi@yahoo.com
Website:  http://emmanueloyekanlu.com/
Publications:  https://scholar.google.com/citations?user=S-jTMfkAAAAJ&hl=en
LinkedIn:  https://www.linkedin.com/in/emmanuel-oyekanlu-6ba98616
Github:  https://github.com/manuelbomi

```
[![Icons](https://skillicons.dev/icons?i=aws,azure,gcp,scala,mongodb,redis,cassandra,kafka,anaconda,matlab,nodejs,django,py,c,anaconda,git,github,mysql,docker,kubernetes&theme=dark)](https://skillicons.dev)
