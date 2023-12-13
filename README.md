## Foundry Fund Me

This is a simple project to demonstrate how to use the Foundry framework to build a simple crowdfunding application.

Important elements in this project are:
- the unit and integration tests
- the use of scripts for deployment as well as managing the funds of the contract
- the use of keystore based accounts using the --account parameter

The Makefile does all the heavy lifting for you. It will install all the dependencies, build the project, run the tests and deploy the contract to the specified network.


## Documentation

## Usage

### Build

```shell
$ make build
```

### Test

```shell
$ make test
```

### Format

```shell
$ make fmt
```

### Gas Snapshots

```shell
$ make snapshot
```

### Deployment

To deploy locally

```shell
$ make deploy
``` 

To deploy to Sepolia

```shell
$ make deploy --network sepolia
```

### Funding

To fund the contract on a local network

```shell
$ make fund
```

To fund the contract on Sepolia

```shell
$ make fund --network sepolia
```

To withdraw from the contract on a local network

```shell
$ make withdraw
```

To withdraw from the contract on Sepolia

```shell
$ make withdraw --network sepolia
```

