# Decisions

I selected most of the stack because I have experience working with these technologies and also because they are community-backed technologies.

I decided to divide the system into two parts, one for the back-end (ABility Services) and one for the front-end (SBitly App) because I think it's the best way to simulate a microservice environment, a service focused on solving a specific problem and a client, both isolated from the processes and errors from other services.

All my services use a Dockerfile and also in this repository I provide a Docker Compose to run all the services together.

I made a CI pipeline for the two projects to test, lint and generate a new version of the Docker images saved in Docker Hub.

- ABitly Services

  - Flask - A micro-frame that provides only what is necessary to avoid using an unnecessary stack because always is easier to work and maintain small things.
  - Pytest - Provides useful tools and a really good integration to tests flask apps using Pytest Flask.
  - Virtual Env - It is the best way to isolate the dependencies and the processes of the project.
  - Pylama - This tool really enforces the best practices of Python, combines the following tools: pycodestyle, pydocstyle, PyFlakes, Mccabe, Pylint, Radon, gjslint, and Mypy. Also, it has good integration with Pytest.

- ABitly App

  - Node Version Manager - It is the best tool to handle node versions and enforce to the team members to use an specific version of Node.js this project uses the latest version of Node.js LTS.
  - React - Provides a good and mature environment to develop Single Page Applications and is focused not only to reuse components also Logic with React Hooks and HOC.
  - ESLint and Prettier - These tools really enforces the best practices of JavaScript.
  - Redux - Redux is useful to handle the state of the application and I don't mean to the Redux Store. I mean when you use Redux you know exactly what is the current process of the application and what should be shown in the UI.
  - Immutable - Improves the performance of the app providing immutable structures.
  - Redux Sagas - Avoid the side effects in asynchronous actions.
  - Note: The store structure is based on Redux Docks, is the way to manage redux parts in modules.
