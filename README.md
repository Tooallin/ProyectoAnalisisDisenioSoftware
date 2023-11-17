Migraciones en Sequelize:

-npx sequelize model:create --name Client --attributes nombre:string,apellido:string,rut:string,email:string,password:string
-npx sequelize model:create --name Analyst --attributes nombre:string,apellido:string,rut:string,email:string,password:string
-npx sequelize model:create --name Supervisor --attributes nombre:string,apellido:string,rut:string,email:string,password:string
-npx sequelize model:create --name LoanRequest --attributes monto_prestamo:integer,n_cuotas:integer,id_client:integer
