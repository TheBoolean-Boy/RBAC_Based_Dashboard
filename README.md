
# RBAC BASED DASHBAORD

I developed a simple and easy to use RBAC based UI as a solution to my VRV Security frontend developer Internship.


## Documentation

[Checkout The Live Deployement](https://linktodocumentation)

### **Tech stack**

*NextJs* , *Primsa* , *PostgreSQL* ,  *Neondb* , *Tailwind* .


### **Features as described in Assignment**


    - Add, Edit, or Delete users.
    - Assigning roles to users
    - Managing their status (Active/Inactive).
    - To be able to edit roles.
    - Allowed roles to include permissions(Read, Write, Delete)
    - Also included additional permissions such as to manage and block users.
    - Designed a method to assign or modify permissions for roles.
    - Displayed permissions clearly for ease of understanding and modification.
    - Mock API calls for CRUD operations on users like to create new users, Delete users.

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

 **DATABASE_URL** : Signup for any postgresql based db like Neon or Supabase. Connect your db to your prisma schema using connection string provided the the db you created. Assign the string value to this variable.




## Deployment

To install all the dependencies run the following command


```bash
  pnpm install
```

To migrate prisma schema to your online db run the follwing command


```bash
  pnpm prisma migrate dev
```

To finalize run the following commands


```bash
  pnpm db:push
  pnpm db:seed
```
To deploy it locally use the following command
```bash
  pnpm run dev
```
