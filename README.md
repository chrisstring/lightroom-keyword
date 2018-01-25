# lightroom-keyword

LightroomExporter:
  creates new CSV file ready to be imported into Lightroom via LRTransporter Plugin.
  Creates a new CSV using SKUs in a donor CSV matched against a PIM export
  Users supply skus in simple CSV, one sku for each line. Users will also need to supply the PIM export file. Currently setup for custom PIM export


Append Keywords:
  Reads each line in CSV and does gen specific matching and keyword adding, saves out a copy of the csv with a new name.
