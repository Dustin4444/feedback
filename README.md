# Codecov Feedback Repo

[![Build Status](https://img.shields.io/github/workflow/status/codecov/feedback/CI)](https://github.com/codecov/feedback/actions)
[![License](https://img.shields.io/github/license/codecov/feedback)](LICENSE)

## Table of Contents
- [Talk to us about Codecov!](#talk-to-us-about-codecov)
- [Core Product Repos](#core-product-repos)
- [Running Locally](#running-locally)
- [Contributing](#contributing)

### Talk to us about Codecov! 

[Issues are open](https://github.com/codecov/feedback/issues) for two purposes: 

1.) Provide feedback or ask questions about Codecov

2.) For unpaid users with problems to receive input from the community and best effort support from Codecov team members.\*

### Core Product Repos

Here are our core product repos:

- [**codecov-api**](https://github.com/codecov/codecov-api): Codecov’s API layer. This is a Django / Django Rest Framework application that services our front end and public REST API.
- [**worker**](https://github.com/codecov/worker): Codecov’s asynchronous task processing layer. This is a Python and Rust application that is primarily responsible for offline task execution, managing job queues, and so on.
- [**gazebo**](https://github.com/codecov/gazebo): Codecov’s React SPA front end. This is the front end application end users interact with on the app.codecov.io subdomain.
- [**shared**](https://github.com/codecov/shared): A collection of shared functions and classes that are used by both codecov-api and worker

### Running Locally

Want to run it locally? Start here:

- [**self-hosted**](https://github.com/codecov/self-hosted): A repository that allows users to bootstrap Codecov proof of concept and small volume installations.

### Contributing

We welcome contributions! Please see our [contributing guidelines](CONTRIBUTING.md) for more information on how to get started.

_\* You may also want to see the [FAQ and knowledge base](https://codecovpro.zendesk.com/hc/en-us) to help find an answer to your problem. This is the same place for paid customers to submit support tickets._
