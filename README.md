# API Testing with newman

### Install newman and Verify Installation
- Install newman
```ssh
npm install -g newman
```

- Verify installation
```ssh
newman -v
```

---
#### Run Newman

```sh
newman run Zipmex.postman_collection.json --environment "environment\production.postman_environment.json"
```

![Screenshot](https://raw.githubusercontent.com/korakrit-c/api-test-with-newman/main/img/Zipmex.postman_collection.json%20-%20Zipmex2%20-%20Visual%20Studio%20Code.png)
