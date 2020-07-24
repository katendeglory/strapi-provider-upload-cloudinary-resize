# strapi-provider-upload-cloudinary-resize

## Configurations

**Example**

`./config/plugins.js`

```js
module.exports = ({ env }) => ({
  // ...
  upload: {
    provider: 'cloudinary-resize',
    providerOptions: {
      cloud_name: env('CLOUDINARY_NAME'),
      api_key: env('CLOUDINARY_KEY'),
      api_secret: env('CLOUDINARY_SECRET'),
      optimize: {
        width: 750,
        height: 750,
        quality: 75
      },
    },
  },
  // ...
});
```

## Resources

- [License](LICENSE)

## Links

- [Strapi website](http://strapi.io/)
- [Strapi community on Slack](http://slack.strapi.io)
- [Strapi news on Twitter](https://twitter.com/strapijs)"# strapi-provider-upload-cloudinary-resize" 
