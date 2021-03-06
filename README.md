# Query provider for SuperOffice CRM (SuperLinq)
SuperLinq is a (linq) query provider for [SuperOffice CRM](http://www.superoffice.com). 
The goal of the library is to make querying with the NetServer Web Services a lot easier, more straightforward and with less code. 
By default it utilizes the dynamic archive provider to query any table in the SuperOffice database but it can actually be used to query any archive provider.

## Getting started
In order to get started with SuperLinq simply install the NuGet package:

`install-package InfoBridge.SuperLinq` 

Then, make sure you are authenticated with NetServer and start querying:
```
    List<Contact> contacts = new Queryable<Contact>()
        .Where(x => x.Name.Contains("Super"))
        .ToList();
```

## Documentation
Documentation is currently not yet available.

## Requirements
.NET Framework 4.5.1

## License
SuperLinq is released under the MIT License.

## InfoBridge Software B.V.
SuperLinq is an [InfoBridge Software B.V.](http://www.infobridge.com) project.