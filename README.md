# learn-md
In an Ecommerce start-up, Tokonyadia, you work as a Backend Developer. Tokonyadia will soon launch its apps, you are asked to create a backend that can provide a REST API for store management purposes. As for the API that must be made, it must meet the following features:

> # API
> Use the `postman` to test API.
>> ##
>> - [x] 1. Can register a store with information on store name, store address, phone number, SIUP number, and NPWP :tada:

`Request on POST Endpoint`
Here, we have one `API` which is used to `register` a new `store`:
Use the `postman` to test API.

-`POST`
```sh
  localhost:8080/tokonyadia/store
```

Enter the `URL` in the postman endpoint bar, and press Send.

`Now in the Body tab, select raw and select JSON as the format type from the drop-down menu`

-`BODY`
```sh
  {
  
  }
```
> ##
>> - [x] 2. Can display a list of existing stores :tada:

`Request on GET Endpoint`
Here, we have one `API` which is used to `get all list of store`:
Use the `postman` to test API.

-`GET`
```sh
  localhost:8080/tokonyadia/store
```

Enter the `URL` in the postman endpoint bar, and press Send.
> ##
>> - [x] 3. Can delete shop :tada:

`Request on DELETE Endpoint`
Here, we have one `API` which is used to `delete a strore`:
Use the `postman` to test API.

-`DELETE`
```sh
  localhost:8080/tokonyadia/store/{id}
```

Enter the `URL` in the postman endpoint bar, and press Send.
> ##
>> - [x] 4. Can update store information :tada:

`Request on PUT Endpoint`
Here, we have one `API` which is used to `update a store`:
Use the `postman` to test API.

-`PUT`
```sh
  localhost:8080/tokonyadia/store/{id}
```

Enter the `URL` in the postman endpoint bar, and press Send.
> ##
>> - [x] #739 5. Can do store search by store name, address, phone number 

