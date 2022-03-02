# CityGML3_ADE

ADE conversion test from CityGML 2.0 ADE to CityGML 3.0 ADE

ADE:
- Source: [urbanObject.xsd v1.5](https://www.chisou.go.jp/tiiki/toshisaisei/itoshisaisei/iur/schemas/uro/1.5/urbanObject.xsd) (Urban Object Module) from [i-Urban Revitalization](https://www.chisou.go.jp/tiiki/toshisaisei/itoshisaisei/iur/index.html) (aka i-uR, Urban Planning ADE)
- Automatically Converted ADE (by @TatjanaKutzner): [urbanObject_CityGML3.xsd](https://github.com/nob140/CityGML3_ADE/blob/main/AutomaticConversion/urbanObject_CityGML3.xsd)
- Manually Converted ADE (by @nob140 and @clausnagel): [urbanObject_CityGML3.xsd](https://github.com/nob140/CityGML3_ADE/blob/main/ManualConversion/urbanObject_CityGML3.xsd)

- Note:
  - Automatically converted ADE using ShapeChange developed by @TatjanaKutzner
  - Manually converted ADE developed by @nob140 and @clausnagel

CityGML Data:
- Data Source: Tokyo Station in 53394611_bldg_6697_op2.gml and Meiji Memorial Picture Gallery in 53394517_bldg_6697_op2.gml from [Project PLATEAU](https://www.geospatial.jp/ckan/dataset/plateau-tokyo23ku) (CC BY 4.0)
- Note:
  - All data are validated by VS Code and XML Extension by Red Hat (checking syntaxs errors).
  - i-UR 1.5 is same as i-UR 1.4 except for namespace URL (due to change of Japanese government server). Though original data of Project PLATEAU is using ADE i-UR 1.4, the URL of namespace "uro" were modified for using converted i-UR 1.5 ADE.

- Sample 1: Tokyo Station (Mesh ID: 53394611, Building ID: 13101-bldg-871)
  - [Using Automatically Converted ADE](https://github.com/nob140/CityGML3_ADE/blob/main/AutomaticConversion/53394611_bldg_6697_op2_CityGML3.gml)
  - [Using Manually Converted ADE](https://github.com/nob140/CityGML3_ADE/blob/main/ManualConversion/53394611_bldg_6697_op2_CityGML3.gml)

![Original CityGML 2.0 image](53394611_bldg_6697_TokyoStation_CityGML2.png "Original CityGML2 ADE data")

![Converted CityGML 3.0 image](53394611_bldg_6697_TokyoStation_CityGML3.png "Converted CityGML3 ADE data")

- Sample 2: Meiji Memorial Picture Gallery (Mesh ID: 53394517, Building ID: 13104-bldg-53)
  - [Using Automatically Converted ADE](https://github.com/nob140/CityGML3_ADE/blob/main/AutomaticConversion/53394517_bldg_6697_op2_CityGML3.gml)
  - [Using Manually Converted ADE](https://github.com/nob140/CityGML3_ADE/blob/main/ManualConversion/53394517_bldg_6697_op2_CityGML3.gml)

![Original CityGML 2.0 image](53394517_bldg_6697_MeijiMemorialPictureGallery_CityGML2.png "Original CityGML2 ADE data")

![Converted CityGML 3.0 image](53394517_bldg_6697_MeijiMemorialPictureGallery_CityGML3.png "Converted CityGML3 ADE data")
