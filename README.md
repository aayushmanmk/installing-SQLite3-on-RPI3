# installing-SQLite3-on-RPI3
Installing SQLite3 on RPI3B+ to create databases.
---




 ![image](https://user-images.githubusercontent.com/124895858/218455802-716a5a77-6549-46c2-bc0b-c85d15668271.png)
 
 ![image](https://user-images.githubusercontent.com/124895858/218455872-c4d21f2b-71a0-4248-9b8d-59d6662ff67b.png)
 
 ![image](https://user-images.githubusercontent.com/124895858/218456027-b48cbaa1-31eb-4938-b08f-9e2b044d60f2.png)

* `sudo apt update`

* `sudo apt full-upgrade`

* `sudo apt install sqlite3`

From here you can use the following command to create a database:

* `sqlite3 (database_name).db`

---

 ```
 select * from JSNP where Symbol=="JNPR.dat" ORDER BY Date DESC limit 1;
 ```

what is does:

 ![image](https://user-images.githubusercontent.com/124895858/220623810-1013324f-1710-4915-8f69-ab5ea16a239b.png)

```
select * from JSNP where Symbol=="J.dat" AND (Date=="2023-02-06" OR Date=="2023-01-03");
```

what it does:

![image](https://user-images.githubusercontent.com/124895858/220626506-b6cc571b-4aee-46f4-b876-d420a875786f.png)
