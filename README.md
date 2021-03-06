# Conference Planner

This repository contains a GraphQL schema that can be used to build a Conference Planner application.

You can use it with [`graphql-up`](https://graph.cool/graphql-up/), a tool that let's you quickly get started with a GraphQL API. You can install it via [npm](https://www.npmjs.com/package/graphql-up).

```
npm install -g graphql-up # install graphql-up, if you haven't already
```

Then it's as simple as calling the tool from the command line and passing in the schema file:

```
git clone https://github.com/nikolasburk/ConferencePlanner.git
cd ConferencePlanner
graphql-up conference_planner.schema
```

Or if you don't want to clone the repository:

```
graphql-up https://github.com/nikolasburk/ConferencePlanner/blob/master/conference_planner.schema
```

Or simply click this button:

[![graphql-up](http://static.graph.cool/images/graphql-up.svg)](https://www.graph.cool/graphql-up/new?source=https://raw.githubusercontent.com/nikolasburk/ConferencePlanner/master/conference_planner.schema)
