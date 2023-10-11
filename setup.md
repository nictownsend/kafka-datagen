```sql
create table store_details (storeID varchar primary key, storeName varchar, manager varchar);
insert into store_details values ('A1', 'Charville', 'Paul Smith'),('A2', 'Smartbury','John Cops'),('B1','Westbourne','Joe Bloggs'),('B2','Eastchester','Sue West'),('B3','Furston','Angie Gust');
```

```json
{"store":"A1", "time": "2023-10-11 14:01:04", "transactions":15 }
{"store":"A2", "time": "2023-10-11 14:01:14", "transactions":14 }
{"store":"B1", "time": "2023-10-11 14:02:34", "transactions":13 }
{"store":"B2", "time": "2023-10-11 14:01:34", "transactions":1 }
{"store":"B3", "time": "2023-10-11 14:03:04", "transactions":2 }
{"store":"A1", "time": "2023-10-11 15:03:04", "transactions":15 }
{"store":"A2", "time": "2023-10-11 15:03:04", "transactions":32 }
{"store":"B1", "time": "2023-10-11 15:03:04", "transactions":45 }
{"store":"B2", "time": "2023-10-11 15:03:04", "transactions":1 }
{"store":"B3", "time": "2023-10-11 15:03:04", "transactions":23 }
{"store":"A1", "time": "2023-10-11 16:03:04", "transactions":45 }
{"store":"A2", "time": "2023-10-11 16:03:04", "transactions":67 }
{"store":"B1", "time": "2023-10-11 16:03:04", "transactions":89 }
{"store":"B2", "time": "2023-10-11 16:03:04", "transactions":1 }
{"store":"B3", "time": "2023-10-11 16:03:04", "transactions":11 }
{"store":"B3", "time": "2023-10-11 17:03:04", "transactions":11 }
```
