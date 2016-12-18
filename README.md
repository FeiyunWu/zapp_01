https://github.com/FeiyunWu/zapp_01


push by http://localhost:8080/webide/index.html

fei999northwind
https://account.hanatrial.ondemand.com/

link:http://www.sap.com/developer/tutorials/hcp-create-destination.html

fei999i18n
{i18n>title}===file(i18n.properties)  title=Titleini18n.


fei999odata
1.http://services.odata.org/V2/Northwind/Northwind.svc/Products

at the end:?$skiptoken=20
</entry>
  <link rel="next" href="http://services.odata.org/V2/Northwind/Northwind.svc/Products?$skiptoken=20" />
</feed>

http://services.odata.org/V2/Northwind/Northwind.svc/Products?$format=json
http://services.odata.org/V2/Northwind/Northwind.svc/Products

only first 2:$top=2

http://services.odata.org/V2/Northwind/Northwind.svc/Products?$format=json&$top=2

no need first 5 columns,got 2 columns:
http://services.odata.org/V2/Northwind/Northwind.svc/Products?$format=json&$top=2&$skiptoken=5

sorted  by product id default,now sorted by product name,got first 2 rows:&$orderby=ProductName
http://services.odata.org/V2/Northwind/Northwind.svc/Products?$format=json&$top=2&$orderby=ProductName

sorted by descending:%20desc=[space]desc
http://services.odata.org/V2/Northwind/Northwind.svc/Products?$format=json&$top=2&$orderby=ProductName%20desc


fei999filter:$filter=Discontinued%20eq%20true=[space]eq[space]conditon
http://services.odata.org/V2/Northwind/Northwind.svc/Products?$format=json&$orderby=ProductName&$filter=Discontinued%20eq%20true

$filter=Discontinued eq false and UnitPrice gt 100. Here, gt stands for “greater than”.

http://services.odata.org/V2/Northwind/Northwind.svc/Products?$format=json&$orderby=ProductName&$filter=Discontinued%20eq%20false%20and%20UnitPrice%20gt%20100
http://services.odata.org/V2/Northwind/Northwind.svc/Products?$format=json&$orderby=ProductName&$filter=Discontinued%20eq%20false%20and%20UnitPrice%20gt%20100












