# TeleBook

![alt tag](https://raw.githubusercontent.com/DataMoon/telebook/master/gquVlu.png)

Telebook is a GUI telephone directory that helps organising telephone numbers.<br>
For each new entry, user has to define values in four fields: ID, FULL NAME, JOB and PHONE NUMBER.<br><br>

In order to launch the application you have to initially start the JDBC Derby network server locally:

```
cd dist/lib
java -jar derbyrun.jar server start -h localhost
```

Then you can either left-click manually on Telebook.jar file which is located in dist folder or execute:
```
java -jar Telebook.jar
```

![alt tag](https://raw.githubusercontent.com/DataMoon/telebook/master/screen.png)