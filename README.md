# RESTful-routes

|Name       | Path              | Verb    | Purpose |
|:----------|   :---:           | :---:   | :------------ |
| `Index`   | /comments         | `GET`   | `Displayy all comments`|
| `New`     | /comments/new     | `GET`   | `Form to create new comments`|
| `Create`  | /comments         | `POST`  | `Create new comments on server`|
| `Show`    | /comments/:id     | `GET`   | `Details for one specific comment`|
| `Edit`    | /comments/:id/edit| `GET`   | `Formt to edit specific comment`|
| `Update`  | /comments/:id     | `PATCH` | `Updates specific comments on server`|
| `Destroy` | /comments/:id     | `DELETE`| `Deletes specific item on server`|
