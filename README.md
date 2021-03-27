# grpc-basictutorial
🐕 A basic tutorial introduction to gRPC in Python.

# Install

Use [poetry](https://python-poetry.org/) to create environment and install dependencies.

`poetry install`

# Usage

Compile proto: `poetry run python -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. route_guide.proto`

Run server: `poetry run python route_guide_server.py`

Run client: `poetry run python route_guide_client.py`

Or async:

Run server: `poetry run python asyncio_route_guide_server.py`

Run client: `poetry run python asyncio_route_guide_client.py`


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/)
