# Exercise Swagger.io REST requests

REST requests for a fictional photo storing website

| Request| URL |
|---|---|
|Return information about all albums, send the following request| ''GET https://phantasticfoto.com/api/v1/album/''|
| Return information about a specific album, send the following request | ''GET https://phantasticfoto.com/api/v1/album/album_ID''|
| Create a new album (data for the new album will be in the body), send the following request| ''POST https://phantasticfoto.com/api/v1/album/''|
| To update an existing album (data for the modification will be in the body), send the following request | ''PUT https://phantasticfoto.com/api/v1/album/album_ID''|
| To delete data from an album, send the following request | ''DELETE  https://phantasticfoto.com/api/v1/album/album_ID''|
| To print an album, send the following request | ''POST https://phantasticfoto.com/api/v1/album/album_ID''|