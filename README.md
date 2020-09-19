# ZipCoords

[![NuGet version (ZipCoords)](https://img.shields.io/nuget/v/ZipCoords.svg?style=flat-square)](https://www.nuget.org/packages/ZipCoords/)

### .GetCoordinates(zipcode)
```csharp
var zipcode = "90201";
var coordinates = ZipCoords.GetCoordinates(zipcode);

var latitude = coordinates[0];  // 33.971609
var longitude = coordinates[1];  // -118.171234
```

### .GetMileage(originZipcode, destinationZipcode)
```csharp
var originZipcode = "90201";
var destinationZipcode = "97201";
var mileage = ZipCoords.GetMileage(originZipcode, destinationZipcode);

Console.WriteLine(mileage);  // 1041.7590375429163
```
