# Query builder (.NET Framework) — EasyQuery on Windows Forms

**Query builder.** A desktop query builder: users pick the columns and conditions in the EasyQuery controls, and the app builds the query and shows the result.

Part of [EasyQuery samples for Windows Forms](../README.md).

## Tech stack

| | |
|---|---|
| Host | .NET Framework 4.8.1 |
| UI | Windows Forms |
| Language | C# |
| EasyQuery | 7.5.0 — `Korzh.EasyQuery.Db`, `Korzh.EasyQuery.WinForms`, `Korzh.EasyQuery.SqlServerGate`, `Korzh.EasyQuery.DataExport`, `Korzh.EasyQuery.EntityFramework6` |
| EasyData | 1.6.0 — `EasyData.Exporters.ClosedXML`, `EasyData.Exporters.Default`, `EasyData.Core` |
| Database | SQL Server Express LocalDB |

## Prerequisites

* Windows with .NET Framework 4.8.1 (Developer Pack) and Visual Studio 2022 17.2 or later
* SQL Server Express LocalDB (installed with Visual Studio)

## Run it

### Visual Studio

1. Open `Samples.WinForms.sln` from the repository root.
2. Set `EqDemoWinFormsNet4` as the startup project.
3. Press F5.

## License key

You don't need one to try the samples. Without a key they show a short reminder that EasyQuery is in trial mode. A purchased license key removes it; set it in code, before the EasyQuery controls are created (see `EasyQueryForm`):

```csharp
Korzh.EasyQuery.WinForms.License.Key = "your key goes here";
```

Ready to buy? See the [licensing options on korzh.com](https://korzh.com/easyquery?utm_source=github&utm_medium=sample&utm_campaign=eq-samples-winforms&utm_content=EqDemoWinFormsNet4#winforms-edition).

## Sample database

The demo database is created and filled automatically on the first start (about a minute or
two). It uses SQL Server Express LocalDB; the connection string is in the app's configuration file.

## Related samples

* [Query builder (.NET) — Windows Forms](https://github.com/easyquery/eq-samples-winforms/tree/main/EqDemoWinFormsNet6)
* [Query builder (.NET Framework, Visual Basic) — Windows Forms](https://github.com/easyquery/eq-samples-winforms/tree/main/EqDemoWinFormsNet4VB)
* [Query builder (.NET) — WPF](https://github.com/easyquery/eq-samples-wpf/tree/main/EqDemoWpfNet6)
* [Query builder (.NET Framework) — WPF](https://github.com/easyquery/eq-samples-wpf/tree/main/EqDemoWpfNet4)
