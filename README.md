## Beego API Project

- create db, tables 

---

`bee api my-api -driver=mysql -conn="user:pass@tcp(127.0.0.1:3306)/db_myapi" && code my-api && cd my-api && go mod tidy && bee run -downdoc=true -gendoc=true`