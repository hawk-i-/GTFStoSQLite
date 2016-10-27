# GTFStoSQLite

This is a GTFS parser build using golang to parse GTFS data to SQLite database

## Usage

The executables are in dist folder
### for Windows
```batch
GTFStoSQLite.exe 
    -source="path\to\GTFS\directory" 
    -db="path\to\sqlite.db"
    -size=100000
```

* __source (_required_)__: path to GTFS directory
* __db (_required_)__: path to SQLite .db file. This doesn't need to exist
* __size (_optional_)__: Insert batch size. default: 100000. You can increase the speed by increasing the batch size but it will require more memory to run

### for Linux/macOS
```batch
GTFStoSQLite
    -source="path\to\GTFS\directory"
    -db="path\to\sqlite.db"
    -size=100000
```

* __source (_required_)__: path to GTFS directory
* __db (_required_)__: path to SQLite .db file. This doesn't need to exist
* __size (_optional_)__: Insert batch size. default: 100000. You can increase the speed by increasing the batch size but it will require more memory to run
