# **Assignment II: Database Creation, Deletion & OEM**

**Name:** Ndayishimiye Ineza Giuly  
**ID:** 27390  

---

## **Overview**

This assignment focuses on performing essential database administration tasks in Oracle, including creating and deleting Pluggable Databases (PDBs) and configuring Oracle Enterprise Manager (OEM). The tasks demonstrate knowledge of database setup, management, and monitoring through OEM.

---

## **Task 1: Create a New Pluggable Database (PDB)**

A new Pluggable Database (PDB) was created using the following format:

- **PDB Name:** gi_pdb_27390  
- **Username:** giuly_plsqlauca_27390  
- **Password:** *(A simple password was chosen as required)*  



![Alt Text]( https://github.com/GIULYINEZA2/Database-Creation-Deletion-OEM-Ndayishimiye-Ineza-Giuly-27390/blob/9305e919d43c7438776ab57eb2499a3310f9fc6a/screenshots/Screenshot%202025-10-04%20131355.png)





![Alt Text]( https://github.com/GIULYINEZA2/Database-Creation-Deletion-OEM-Ndayishimiye-Ineza-Giuly-27390/blob/9305e919d43c7438776ab57eb2499a3310f9fc6a/screenshots/Screenshot%202025-10-04%20131805.png)



 ![Alt Text]( https://github.com/GIULYINEZA2/Database-Creation-Deletion-OEM-Ndayishimiye-Ineza-Giuly-27390/blob/9305e919d43c7438776ab57eb2499a3310f9fc6a/screenshots/Screenshot%202025-10-04%20132018.png)


  ![Alt Text]( https://github.com/GIULYINEZA2/Database-Creation-Deletion-OEM-Ndayishimiye-Ineza-Giuly-27390/blob/9305e919d43c7438776ab57eb2499a3310f9fc6a/screenshots/Screenshot%202025-10-04%20132221.png)


---

## **Task 2: Create and Delete a PDB**

A second PDB was created and deleted as part of the exercise.

- **PDB Name:** gi_to_delete_pdb_27390  

After successful creation, this PDB was deleted to demonstrate database deletion commands and cleanup.


- PDB Creation

    ![Alt Text]( https://github.com/GIULYINEZA2/Database-Creation-Deletion-OEM-Ndayishimiye-Ineza-Giuly-27390/blob/d1a969bed0d1db6b1b72b008b01dda0f84f82243/Screenshot%202025-10-04%20133021.png)

  ![Alt Text]( https://github.com/GIULYINEZA2/Database-Creation-Deletion-OEM-Ndayishimiye-Ineza-Giuly-27390/blob/d1a969bed0d1db6b1b72b008b01dda0f84f82243/Screenshot%202025-10-04%20133103.png)

- PDB Deletion

  
  ![Alt Text]( https://github.com/GIULYINEZA2/Database-Creation-Deletion-OEM-Ndayishimiye-Ineza-Giuly-27390/blob/d1a969bed0d1db6b1b72b008b01dda0f84f82243/Screenshot%202025-10-04%20133158.png) 



---

## **Task 3: Oracle Enterprise Manager (OEM) Configuration**

Oracle Enterprise Manager (OEM) was configured successfully to monitor and manage the created PDBs.  
The OEM dashboard displays the database environment and user account information.

  ![Alt Text]( https://github.com/GIULYINEZA2/Database-Creation-Deletion-OEM-Ndayishimiye-Ineza-Giuly-27390/blob/d1a969bed0d1db6b1b72b008b01dda0f84f82243/Screenshot%202025-10-04%20142955.png) 


  ![Alt Text]( https://github.com/GIULYINEZA2/Database-Creation-Deletion-OEM-Ndayishimiye-Ineza-Giuly-27390/blob/d1a969bed0d1db6b1b72b008b01dda0f84f82243/Screenshot%202025-10-04%20134929.png) 


  ![Alt Text]( https://github.com/GIULYINEZA2/Database-Creation-Deletion-OEM-Ndayishimiye-Ineza-Giuly-27390/blob/d1a969bed0d1db6b1b72b008b01dda0f84f82243/Screenshot%202025-10-04%20141656.png) 


  ![Alt Text]( https://github.com/GIULYINEZA2/Database-Creation-Deletion-OEM-Ndayishimiye-Ineza-Giuly-27390/blob/d1a969bed0d1db6b1b72b008b01dda0f84f82243/Screenshot%202025-10-04%20142210.png) 



## **Connecting to sqldeveloper**

  ![Alt Text]( https://github.com/GIULYINEZA2/Database-Creation-Deletion-OEM-Ndayishimiye-Ineza-Giuly-27390/blob/d1a969bed0d1db6b1b72b008b01dda0f84f82243/Screenshot%202025-10-04%20162834.png) 


  ![Alt Text]( https://github.com/GIULYINEZA2/Database-Creation-Deletion-OEM-Ndayishimiye-Ineza-Giuly-27390/blob/d1a969bed0d1db6b1b72b008b01dda0f84f82243/Screenshot%202025-10-07%20130605.png)


---

## **Notes & Challenges**

During the assignment, the following challenges were encountered:

- Difficulty connecting to the container database (CDB) while creating PDBs.  
  **Solution:** Ensured proper connection as SYSDBA and verified the paths used in the `FILE_NAME_CONVERT` clause.
  
- Delays in starting the Oracle Enterprise Manager service.  
  **Solution:** Restarted the Oracle listener and ensured the Oracle Management Service (OMS) was running.

All issues were resolved, and the tasks were completed successfully.

---

## **Conclusion**

The assignment provided hands-on experience with Oracle database creation, deletion, and management through OEM. It strengthened understanding of multitenant architecture and administrative operations essential for real-world database environments.

