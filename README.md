# VbaImportExportAddIn
This is an Excel Add-In to import macros from text files and export macros to text files.

## How to use

### ExpImportort macros
1. Put Excel book and macros, for example as follows.
```
./
├ Book2.xlsm
└ Book2.xlsm.VBA
    ├ Classes
    │    └ Class1
    │
    ├ ExcelObjects
    │    ├ Sheet1
    │    └ ThisWorkbook
    │
    ├ Forms
    │    ├ UserForm1
    │    └ UserForm1.frx
    │
    └ Modules
         └ Module1
```
2. Open Excel book. (For example, open Book2.xlsm.)
3. Click "Import" in Ribbon.  
 ![click import](https://github.com/minoru-nagasawa/DeleteHiddenObjectAddin/blob/master/import.png) 

### Export macros
1. Click "Export" in Ribbon.  
 ![click export](https://github.com/minoru-nagasawa/VbaImportExportAddIn/blob/master/export.png) 
2. All macros are exported, for example as follows.
```
./
├ Book1.xlsm
└ Book1.xlsm.VBA
    ├ Classes
    │    └ Class1
    │
    ├ ExcelObjects
    │    ├ Sheet1
    │    └ ThisWorkbook
    │
    ├ Forms
    │    ├ UserForm1
    │    └ UserForm1.frx
    │
    └ Modules
         └ Module1
```

## Installation
1. Download "VbaImportExportAddIn.xlam".
2. Move "VbaImportExportAddIn.xlam" to "C:\Users\[Username]\AppData\Roaming\Microsoft\AddIns".
3. Input [Alt] -> [t] -> [i] to show Add-In dialog.
4. Check "VbaImportExportAddIn" and then click "OK".  
 ![add-in dialog](https://github.com/minoru-nagasawa/VbaImportExportAddIn/blob/master/select-add-in.png)

