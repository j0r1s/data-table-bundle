# Exporting

A data table can be exported to various formats, using _exporters_, each of which are built 
with the help of an exporter _type_ (e.g. `CsvType`, `XlsxType`, etc).

## Configuring the exporting feature

By default, the exporting is enabled for every data table type.

Every part of the exporting feature can be configured using the [data table options](#passing-options-to-data-tables):

- `exporting_enabled` - to enable/disable feature completely;

## Built-in exporter types

The following exporter types are natively available in the bundle:

- PhpSpreadsheet
    - [CsvType](#csvtype)
    - [HtmlType](#htmltype)
    - [OdsType](#odstype)
    - [PdfType](#pdftype)
    - [XlsType](#xlstype)
    - [XlsxType](#xlsxtype)
    - [PhpSpreadsheetType](#phpspreadsheettype)
- Base types
    - [ExporterType](#exportertype)

{% include-markdown "exporter/creating_custom_exporter_type.md" heading-offset=1 %}

## Built-in types reference

{% include-markdown "exporters/types/phpspreadsheet/csv.md" heading-offset=2 %}
{% include-markdown "exporters/types/phpspreadsheet/html.md" heading-offset=2 %}
{% include-markdown "exporters/types/phpspreadsheet/ods.md" heading-offset=2 %}
{% include-markdown "exporters/types/phpspreadsheet/pdf.md" heading-offset=2 %}
{% include-markdown "exporters/types/phpspreadsheet/xls.md" heading-offset=2 %}
{% include-markdown "exporters/types/phpspreadsheet/xlsx.md" heading-offset=2 %}
{% include-markdown "exporters/types/phpspreadsheet/phpspreadsheet.md" heading-offset=2 %}
{% include-markdown "exporters/types/exporter.md" heading-offset=2 %}