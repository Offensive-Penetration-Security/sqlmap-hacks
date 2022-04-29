## Techniques

- For a time based blind SQL injection, you should use letter T, for example --technique=T .

The list of techniques with its letters is as follows:

```sql
B: Boolean-based blind
E: Error-based
U: Union query-based
S: Stacked queries
T: Time-based blind
Q: Inline queries
```
- Login

```sql
--data="login=username&password=thepassword&form=submit" --method POST --dbs 
```
