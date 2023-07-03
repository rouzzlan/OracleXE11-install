# Create user
login into sqlplus
```text
[rouslan@oracleXE11 ~]$ sqlplus system
```
then run following queres
```text
SQL> connect sys/"50m9FiD3" as sysdba
```
then
```text
SQL> create user rouslan identified by pass;
SQL> grant sysdba to rouslan;  
```