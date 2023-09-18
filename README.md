[![Image](https://www.vipm.io/package/robusto_systems_lib_error_manager/badge.svg?metric=installs)](https://www.vipm.io/package/robusto_systems_lib_error_manager/) [![Image](https://www.vipm.io/package/robusto_systems_lib_error_manager/badge.svg?metric=stars)](https://www.vipm.io/package/robusto_systems_lib_error_manager/)

# Error Manager
The Robusto Systems Error Manager is a free, open-source, reusable, asynchronous module for handling LabVIEW errors inside LabVIEW applications.

![image](https://github.com/RobustoSystems/ErrorManager/assets/34945974/43030b78-a5d1-4295-84e4-a46c23dc6144)

The Error Manager is a stand-alone, asynchronous LabVIEW module that can help log LabVIEW errors to file, display new error details to the user, and display the chronological or inverse-chronological list of errors that occurred since the module started. The module is framework-agnostic, reusable from project to project, and can keep working even when being “spammed” with many instances of the same error (spam protection functionality). Using the Error Manager in a new application helps ensure out-of-the-box robust and reliable error handling.

By default, when an error is reported to the Error Manager the Error Window seen below is displayed (popped-up). This behaviour can be disabled, such that no window pops up and the error is dealt with silently.
![image](https://github.com/RobustoSystems/ErrorManager/assets/34945974/fc749d1e-9fdf-4336-98e1-9e9252b718b9)

By default, when an error is reported to the Error Manager, the Error Manager logs the error details to an Error Log file. This behaviour can be disabled, such that no log file is produced. The log file is a plain text file.
![image](https://github.com/RobustoSystems/ErrorManager/assets/34945974/d9a7e1eb-cd25-49aa-ba23-f07588651347)
