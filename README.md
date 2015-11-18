# KVS Test Dataset

This directory contains test datasets that can be supported in KVS.
These data can be easily visualize by using kvsview command.

|Data 1||
|:--|:--|
|Filename|TF_rainbow.kvsml|
|Format|KVSML|
|Type|Transfer function|
|Size|256 resolution|
|Description|Rainbow colormap|
|Courtesy|Original|
|Example|kvsview -TransferFunction TF_rainbow.kvsml|

|Data 2||
|:--|:--|
|Filename|TF_red-white-blue.kvsml|
|Format|KVSML|
|Type|Transfer function|
|Size|256 resolution|
|Description|Red-white-blue colormap|
|Courtesy|Original|
|Example|kvsview -TransferFunction TF_red-white-blue.kvsml|

|Data 3||
|:--|:--|
|Filename|blunt.inp|
|Format|AVS UCD|
|Type|Unstructured volume object|
|Size|222,414 tetrahedral cells|
|Description|Airflow over a flat plate with a blunt fin rising from the plate|
|Courtesy|http://www.nas.nasa.gov/Resources/datasets.html|
|Example|kvsview -ExternalFaces blunt.inp|

|Data 4||
|:--|:--|
|Filename|bunny.ply|
|Format|PLY file format|
|Type|Polygon object|
|Size|69,451 faces|
|Description|Stanford Bunny|
|Courtesy|http://graphics.stanford.edu/data/3Dscanrep/|
|Example|kvsview -PolygonRenderer bunny.ply|

|Data 5||
|:--|:--|
|Filename|engine.fld|
|Format|AVS Field|
|Type|Structured volume object|
|Size|256 x 256 x 128, 8 bits|
|Description|Engine block|
|Courtesy| ---|
|Example|kvsview -RayCastingRenderer engine.fld|

|Data 6||
|:--|:--|
|Filename|line.kvsml|
|Format|KVSML|
|Type|Line object|
|Size|6 lines|
|Description|Simple line object data|
|Courtesy|Original|
|Example|kvsview -LineRenderer line.kvsml|

|Data 7||
|:--|:--|
|Filename|lobster.kvsml|
|Format|AVS Field|
|Type|Structured volume object|
|Size|120 x 120 x 34, 8 bits|
|Description|AVS lobster|
|Courtesy|AVS|
|Example|kvsview -RayCastingRenderer lobster.kvsml|

|Data 8||
|:--|:--|
|Filename|point.kvsml|
|Format|KVSML|
|Type|Point object|
|Size|4 points|
|Description|Simple point object data|
|Courtesy|Original|
|Example|kvsview -PointRenderer point.kvsml|

|Data 9||
|:--|:--|
|Filename|polygon.kvsml|
|Format|KVSML|
|Type|Polygon object|
|Size|4 faces|
|Description|Simple polygon object data|
|Courtesy|Original|
|Example|kvsview -PolygonRenderer polygon.kvsml|

|Data 10||
|:--|:--|
|Filename|spx.inp|
|Format|AVS UCD|
|Type|Unstructured volume object|
|Size|12,936 tetrahedral cells|
|Description|Coolant flow simulation in the Super PhoeniX reactor|
|Courtesy|---|
|Example|kvsview -ExternalFaces spx.inp|
