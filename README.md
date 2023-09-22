[![Image](https://www.vipm.io/package/robusto_systems_lib_error_manager/badge.svg?metric=installs)](https://www.vipm.io/package/robusto_systems_lib_error_manager/) [![Image](https://www.vipm.io/package/robusto_systems_lib_error_manager/badge.svg?metric=stars)](https://www.vipm.io/package/robusto_systems_lib_error_manager/)

# Error Manager
The Robusto Systems Error Manager is a free, open-source, reusable, asynchronous module for handling LabVIEW errors inside LabVIEW applications.

![image](https://github.com/RobustoSystems/ErrorManager/assets/34945974/43030b78-a5d1-4295-84e4-a46c23dc6144)

The Error Manager is a stand-alone, asynchronous LabVIEW module that can help log LabVIEW errors to file, display new error details to the user, and display the chronological or inverse-chronological list of errors that occurred since the module started. The module is framework-agnostic, reusable from project to project, and can keep working even when being “spammed” with many instances of the same error (spam protection functionality). Using the Error Manager in a new application helps ensure out-of-the-box robust and reliable error handling.

By default, when an error is reported to the Error Manager the Error Window seen below is displayed (popped-up). This behaviour can be disabled, such that no window pops up and the error is dealt with silently.
![image](https://github.com/RobustoSystems/ErrorManager/assets/34945974/fc749d1e-9fdf-4336-98e1-9e9252b718b9)

By default, when an error is reported to the Error Manager, the Error Manager logs the error details to an Error Log file. A typical log file is shown below. This behaviour can be disabled, such that no log file is produced. The log file is a plain text file.
![image](https://github.com/RobustoSystems/ErrorManager/assets/34945974/d9a7e1eb-cd25-49aa-ba23-f07588651347)

The behaviour of the Error Manager can be tailored by changing the settings values stored in the Settings file. The contents of the default settings file are shown below. By default, this settings file is named "Error Manager Settings.ini", but it can be renamed.
![image](https://github.com/RobustoSystems/ErrorManager/assets/34945974/3cf581e1-902e-4834-8809-b1e7d4e526c5)

## Development Environment
The Error Manager codebase is written in LabVIEW 2023 Q3 (32-bit).

## Process to build and publish the VI Package
1. The LabVIEW project is "Saved for previous..." for LabVIEW version 2016.
2. The 2016 version of the files is used as the source folder for the VI package.
3. The VI package is uploaded to https://www.vipm.io/

At the moment the process to build and publish the VIPM package is completely manual. A future improvement would be for this process to be automated.
