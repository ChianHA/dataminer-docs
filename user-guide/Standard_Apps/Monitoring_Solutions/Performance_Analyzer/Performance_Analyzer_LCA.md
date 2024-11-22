---
uid: Performance_Analyzer_LCA
---

# Performance Analyzer app

Raw numbers can often be difficult to interpret, which is why the Performance Analyzer solution provides a built-in low-code app to visualize the data collected by the solution. Using this app will make it much easier to make decisions based on the collected performance metrics.

To use this app, the [Performance Analyzer library](xref:Performance_Analyzer_Library) must have been implemented in the system.

## Installing the Performance Analyzer app

To install the Performance Analyzer app, deploy the [Performance Analyzer](https://catalog.dataminer.services/details/414894ce-21ae-48e7-b2c3-0652fff08349) package from the DataMiner Catalog.

> [!TIP]
> See also: [Deploying a Catalog item to your system](xref:Deploying_a_catalog_item).

## Performance Analyzer app user interface

Below, you can find an overview of the main components of the app.

![Performance Analyzer LCA](~/user-guide/images/performance_analyzer_lca.png)

1. **Performance Analyzer Metrics Folder**: Defines the folder where performance data files are located. By default, this is `C:\Skyline_Data\PerformanceAnalyzer`.

1. **Files**: Shows a list of files available in the selected directory, with each file’s name, creation date, last modified date, and size. You can select a file in this list to analyze it in detail.

1. **Collections**: Displays a list of collections in the selected file. A "collection" refers to one disposal of the collector.

1. **Collections Filter**: Allows you to filter collections based on metadata, making it easy to locate a specific collection or understand its context.

1. **Collection Metadata**: Provides all the relevant details related to the context in which a collection was created.

1. **Metrics**: Provides a detailed list of individual metrics, each representing a specific operation or method call. The table includes information such as class, method, and start and end times, making it easier to identify which parts of the code impact the performance.

1. **Metrics Filter**: Allows you to filter metrics by specific classes, methods, execution time ranges, or metadata.

1. **Metric Metadata**: Provides more context information for the metrics, making it easier to understand them.

1. **Timeline**: Visual representation of every metric. You can focus on a specific block by double-clicking the corresponding table entry.

1. **Metric Metadata (Timeline)**: Provides an overview of the context for the selected timeline block.