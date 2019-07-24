{
  "title": "BookPaxInput",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "name",
      "url": "/hotel-x/reference/scalars/string",
      "description": "The guest's first  name",
      "args": null
    },
    {
      "typeString": "String!",
      "name": "surname",
      "url": "/hotel-x/reference/scalars/string",
      "description": "The guest's last name",
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "age",
      "url": "/hotel-x/reference/scalars/int",
      "description": "The guest's age",
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "BookPaxInput",
  "hideGithubLink": true
}
Input BookPax contains basic information abaout pax suach as name, surname and age.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}