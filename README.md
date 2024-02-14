# Cado API Reference

The documentation reference for the Cado platform's RESTful API. The API can integrate with every part of the platform, from user management, querying timeline data, and importing evidence from the cloud. We provide some [example Python scripts](https://github.com/cado-security/cado-api-examples) to help you get started.

Using the API requires an API key, which can be [obtained from the Cado platform](https://docs.cadosecurity.com/cado-response/manage/integrations/api-overview). This API key needs to be used with the Authorization header in the Bearer format. For example: `Authorization: Bearer YOUR_API_KEY`. 

Each API will have a few extra parameters listed in the description, these parameters describe how the API behaves and what it expects. The parameters we list are:

* **Feature Lifecycle**: This indicates if the API is in `beta` or `production`. If the API is in `beta`, you may need to enable it in the Experiments settings inside the platform.
* **Admin Only**: This indicates if the API requires an administrator user account.
