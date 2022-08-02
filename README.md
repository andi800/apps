# Apps


## Qt

### Qt Widget
- C++
- very fast, oldschool
- QPainter CPU renderer
- Support for SVG, PDF, Print, Richtext, Full Unicode, Installer, Classic .exe
- Pain of header files
- Support for Mac, iOS, Linux, Windows7, Win10, Android

### Qt QML/Quick
- C++ / JavaScript


## Windows Forms App
- C#
- .NET 6
- Windows 10/11 only

## Uno Platform
### Uno UWP App

### Uno Win SDK App

## WinUI App
- C#
- Windows App SDK vs. Project Reunion

## MAUI
- C#

## UWP (Universal Windows)
- C#

## WPF
- C#

## MFC
- C++

## Win32 API
- C (C++)

|Description|Language|Win|Mac|iOS|Android|Linux|2D Graphics|3D graphics|Lizenz|Controls|Graphic exports
|---|---|---|---|---|---|---|---|---|---|---|---
|Qt |C++ / JavaScript / QML|:white_check_mark:|:white_check_mark:|:white_check_mark:|:white_check_mark:|:white_check_mark:|QPainter CPU (fast)|Qt3D wrapper GPU|LGPL|:white_check_mark: All|:white_check_mark: All
|WinUI SDK App .NET6|C# |:white_check_mark:|:x:|:x:|:x:|:x:|Win2D API, Shapes, Skia? :grey_question:|:grey_question:|MIT?|:white_check_mark: All|All when Skia?
|Maui .NET6|C# |:white_check_mark:|:white_check_mark:|:white_check_mark:|:white_check_mark:|:x:|Skia GPU accelerated|:grey_question:|MIT?|Treeview? Datagrid? Expander? PrintPreview? RichText?|:white_check_mark: All
|Platform Uno .NET6|C# |:white_check_mark:|:white_check_mark:|:white_check_mark:|:white_check_mark:|:white_check_mark:|Skia? :grey_question:|:grey_question:|MIT?|TODO|All when Skia?
|WinForms .NET6 |C# |:white_check_mark:|:x:|:x:|:x:|:x:|Skia accelerated|OpenTK? SharpGL :grey_question:|MIT?|Expander?|:white_check_mark: All

Controls:
- Checkable-Treeview
- Datagrid
- Expander
- PrintPreview
- RichText
- Tabs

Graphics exports:
- SVG
- PDF
- DOCX / ODF / RTF
- XLSX
- CSV
- HTML



