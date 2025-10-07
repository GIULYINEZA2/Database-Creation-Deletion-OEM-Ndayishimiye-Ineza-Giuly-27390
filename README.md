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



**Screenshot:**  
*(Insert your PDB creation screenshot here)*

---

## **Task 2: Create and Delete a PDB**

A second PDB was created and deleted as part of the exercise.

- **PDB Name:** gi_to_delete_pdb_27390  

After successful creation, this PDB was deleted to demonstrate database deletion commands and cleanup.

**Screenshots:**  
- PDB Creation  
- PDB Deletion  

*(Insert screenshots here)*

---

## **Task 3: Oracle Enterprise Manager (OEM) Configuration**

Oracle Enterprise Manager (OEM) was configured successfully to monitor and manage the created PDBs.  
The OEM dashboard displays the database environment and user account information.

**Screenshot:**  
*(Insert OEM dashboard screenshot showing your username clearly)*

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

