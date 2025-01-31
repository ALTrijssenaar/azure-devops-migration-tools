## Endpoints: TfsEndpoint

>**_This documentation is for a preview version of the Azure DevOps Migration Tools._ If you are not using the preview version then please head over to the main [documentation](https://nkdagility.com/docs/azure-devops-migration-tools).**

[Overview](.././index.md) > [Reference](../index.md) > [Endpoints](./index.md) > **TfsEndpoint**

missng XML code comments

### Options

| Parameter name         | Type    | Description                              | Default Value                            |
|------------------------|---------|------------------------------------------|------------------------------------------|
| Organisation | String | missng XML code comments | missng XML code comments |
| Project | String | missng XML code comments | missng XML code comments |
| AuthenticationMode | AuthenticationMode | missng XML code comments | missng XML code comments |
| AccessToken | String | missng XML code comments | missng XML code comments |
| ReflectedWorkItemIdField | String | missng XML code comments | missng XML code comments |
| LanguageMaps | TfsLanguageMapOptions | missng XML code comments | missng XML code comments |
| EndpointEnrichers | List | missng XML code comments | missng XML code comments |
| RefName | String | missng XML code comments | missng XML code comments |


### Example JSON

```JSON
{
  "$type": "TfsEndpointOptions",
  "Organisation": "https://dev.azure.com/nkdagility-preview/",
  "Project": "NeedToSetThis",
  "AuthenticationMode": "AccessToken",
  "AccessToken": "6i4jyylsadkjanjniaydxnjsi4zsz3qarxhl2y5ngzzffiqdostq",
  "ReflectedWorkItemIdField": "Custom.ReflectedWorkItemId",
  "LanguageMaps": {
    "$type": "TfsLanguageMapOptions",
    "AreaPath": "Area",
    "IterationPath": "Iteration"
  },
  "EndpointEnrichers": null
}
```