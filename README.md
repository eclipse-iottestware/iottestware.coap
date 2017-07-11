# Eclipse CoAP test suite

A conformance test suite for the IoT protocol CoAP written in TTCN-3.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

* Latest version of Java
* Latest version of **Eclipse Titan**. For installation details please consult the official [Titan documentation package](https://projects.eclipse.org/projects/tools.titan/downloads)
* Your SUT implementing the CoAP protocol (one default CoAP server is provided with this project)

### Installing Quickstart
#### LINUX

First you need to make sure that alle the prerequisites are met. Especially you should make sure that you installed the [Eclipse Titan Core](https://github.com/eclipse/titan.core) properly. This includes setting the environment variables for Titan.

Afterwards you simply run the *install.sh* script. It will load all dependencies and build the project. It will also run all existing test cases (optional: make the script executable if not already done):
```bash
chmod +x install.sh
./install.sh
```

#### Windows
TODO

## Deployment

TODO

## Built With

TODO

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on building the project, our code of conduct, and the process for submitting pull requests to us.

## Versioning

TODO

## Authors

* **Sascha Kretzschmann** - *Initial work* - [Fraunhofer FOKUS](https://www.fokus.fraunhofer.de/)
* **Axel Rennoch** - *Initial work* - [Fraunhofer FOKUS](https://www.fokus.fraunhofer.de/)
* **Avdoot Chalke** - *Initial work* - [Fraunhofer FOKUS](https://www.fokus.fraunhofer.de/)

## License

[Eclipse Public License 1.0 (EPL-1.0)](https://opensource.org/licenses/EPL-1.0)

## Acknowledgments

TODO

