# GetRandomIpAdress

``` cs
 public static string GetRandomIpAddress()
 {
     var random = new Random();
     return $"{random.Next(1, 255)}.{random.Next(0, 255)}.{random.Next(0, 255)}.{random.Next(0, 255)}";
 }
```
