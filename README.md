# gatsby-source-untappd-json

A Gatsby Source to Transform an Untappd JSON Export into a Gatsby GraphQL Data Source.

## Getting Started

1. Install the package with **yarn** or **npm**

`yarn add gatsby-source-untappd-json gatsby-source-filesystem gatsby-plugin-sharp gatsby-transformer-sharp`

2. Add to plugins in your gatsby-config.js

```javascript
module.exports = {
    plugins: [
        "gatsby-plugin-sharp",
        "gatsby-transformer-sharp",
        {
            resolve: "gatsby-source-untappd-json",
            options: {
                src: "path/to/json/file.json"
            }
        }
    ]
};
```

## Contributing

Every contribution is very much appreciated.
Feel free to file bugs, feature- and pull-requests.

❤️ If this plugin is helpful for you, star it on [GitHub](https://github.com/codevachon/gatsby-source-untappd-json).
