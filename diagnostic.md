# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
The backend is responsible for storing and accessing data.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
The controller communicates with the model, which fetches the data.
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
The controller.
```
List at least 5 standard actions that C.R.U.D corresponds to?

```bash
Create, Reading index, reading single, update, delete.
```

A user action fires a `PATCH` request for `pets/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list,
please include information on dynamic segments, the params hash and seralizers).

```bash
- The router receives the request for an update, and finds the PetsController.
- The instance method def update is called and passes the pets_params method as
the parameter.
- The model class Pet is chosen by the controller.
-The serializer will customize the JSON to not include unneeded information.
- The database updates the database.
- The model communicates with the model that the request was correct, or that
an error occured and gives a status of :unprocessable_entity.

```

What is the command to scaffold a `medicalRecords` join table which holds
refrences to a `pets` and a `vets` table?

```bash
// your response here
```

What is the point of having a join table?

```bash
// your response here
```

Give an example of a one-to-many relationship and a many-to-many relationship:

```bash
// your response here
```
