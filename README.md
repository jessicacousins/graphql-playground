# GraphQL-Playground

- install dependencies: `npm install`
- start port 4000: `node index.js`
- navigate to: `http://localhost:4000/graphql`

## GraphQL query:

```
{
  games {
    id
    title
    publisher
    developer
    releaseDate
    platforms {
      id
      name
    }
    esrbRating {
      id
      code
      name
    }
  }
}
```
