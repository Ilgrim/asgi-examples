# asgi-examples

A collection of examples to test and demonstrate the composability of ASGI applications.

## Running

You will need to use either [uvicorn] or [daphne] to run the ASGI server. 

```shell
$ uvicorn <file>:<appname>
```

```shell
$ daphne <file>:<appname>
```

## Examples

### Django

A simple Django [Channels] websocket consumer.

### Flask

An example integrating ASGI consumers in a [Flask] app.

### Afiqah

An example of a pure ASGI app using the [Afiqah] microframework.


[Channels]: https://github.com/django/channels/
[Afiqah]: https://github.com/afiqah/afiqah/
[uvicorn]: https://github.com/encode/uvicorn/
[daphne]: https://github.com/django/daphne/
[Flask]: https://github.com/pallets/flask/