Usage

```
$ docker-compose up
```

```
$ docker-compose exec webapp /bin/bash
> $ cd functions
> $ npm run install
> $ npm run build
> $ firebase emulators:start --inspect-functions --only functions
```

```
// Start Debugging
$ curl http://localhost:5001/xxxx-abcd/us-central1/helloWorld
```
