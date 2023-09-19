# ORACLE_INSTALL
Procedimentos para criacao do banco de dados Oracle

# DBCA usando o modo SILENT 

![image](https://github.com/alinemoreira89/ORACLE_INSTALL/assets/115798703/6f737b40-b445-4d47-bc53-96eaae3cb6fe)

Segue em texto :

[oracle@inst-06 ~]$ dbca -silent -createDatabase                                                   \
>      -templateName /u01/app/oracle/product/19.0.0/dbhome_1/assistants/dbca/templates/General_Purpose.dbc \
>      -gdbname DBMANUAL -sid  DBMANUAL -responseFile NO_VALUE                   \
>      -characterSet AL32UTF8                                                    \
>      -sysPassword Brs_8m1#4O4I                                                 \
>      -systemPassword Brs_8m1#4O4I                                              \
>      -createAsContainerDatabase true                                           \
>      -numberOfPDBs 1                                                           \
>      -pdbName PDB1                                                             \
>      -pdbAdminPassword Brs_8m1#4O4I                                            \
>      -databaseType MULTIPURPOSE                                                \
>      -memoryMgmtType auto_sga                                                  \
>      -totalMemory 2000                                                         \
>      -storageType FS                                                           \
>      -datafileDestination /u01/app/oracle/oradata/DBMANUAL                     \
>      -redoLogFileSize 50                                                       \
>      -emConfiguration NONE                                                     \
>      -ignorePreReqs


# DBCA usando o modo Interativo ( Interactive Mode)

![image](https://github.com/alinemoreira89/ORACLE_INSTALL/assets/115798703/b2796ef0-2bef-4944-8d6f-5b0af71b63f7)

A seguinte imagem ira aparecer :


![image](https://github.com/alinemoreira89/ORACLE_INSTALL/assets/115798703/c587ad37-975e-4de9-88ff-5cb6e49eff40)
