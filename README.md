# SmartContractTutorial
Review of the "Writing Your First Smart Contract Workshop." Originally presented on September 2, 2017

## Installation of Dependencies

### Installing npm and node
In order to install npm and node, it is best to simply install the Node Version Manager (nvm). To install or update nvm, you can use the install script provided by provided on the [nvm github][1]. You can install using either cURL:

```sh
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.4/install.sh | bash

```

or wget:

```sh
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.33.4/install.sh | bash
```

Once nvm is installed, use the following command to get the latest builds of npm and node.
```
nvm install node
```

Make sure that node is at least version 8.
```
node -v
```


### Installing the test-rpc
Now that we have npm installed, we can install the test-rpc. This tool will allow you to run a local instance of the ethereum blockchain on which to test contracts.
```
npm install -g ethereumjs-testrpc
```

### Installing the Truffle framework
We can also install the Truffle framework using npm. This will allow us to compile contracts and migrate them to the blockchain with ease. It also provides a handy interface with web3.
```
npm install -g truffle
```


[1]: https://github.com/creationix/nvm
