## What I added?
```
add extra host params to make dynamic hostname 
[
  {
    url: `/posts/${resource.id}`,
    host: `https://${resource.subdomain_name}.abc.io/`,
    lastmod: resource.updated_at,
  }

]
```


[📖 **Release Notes**](./CHANGELOG.md)

## License

[MIT License](./LICENSE)

## Contributors

- [Nicolas Pennec](https://github.com/NicoPennec)
- [Pooya Parsa](https://github.com/pi0)
