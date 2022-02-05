# Restful-services



Rest ===>  Representational State Transfer

Using rest we can perform CRUD opertion on server.
(CRUD--> {create,read,update,delete})


HTTP Methods ===>  GET, POST, PUT, DELETE


TO perform operation like Customers
 
       Request                       Response

GET    /api/customers           ====>    [{id:1, name:'xyz'},
                                          {id:2, name:'abc'}]


GET    /api/customer/1          ====>     {id:1, name:'xyz'}

PUT    /api/customer/1          ====>     {id:1, name:''}
          {name:''}


POST    /api/customers          ====>    [{id:1, name:'xyz'},
          {name:'ijk'}                    {id:2, name:'abc'},
                                          {id:3, name:'ijk'}]
         

DELETE  /api/customer/1          


