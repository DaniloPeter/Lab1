[![CI/CD GitHub Actions](https://github.com/DaniloPeter/Lab1/actions/workflows/cmake.yml/badge.svg)](https://github.com/DaniloPeter/Lab1/actions/workflows/cmake.yml)
[![Coverage Status](https://coveralls.io/repos/github/DaniloPeter/Lab1/badge.svg?branch=main)](https://coveralls.io/github/DaniloPeter/Lab1?branch=main)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=danilopeter&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=danilopeter)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=danilopeter&metric=bugs)](https://sonarcloud.io/summary/new_code?id=danilopeter)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=danilopeter&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=danilopeter)

This project is designed for testing and validating services, providing a robust framework for service testing with comprehensive test coverage and quality assurance. It includes automated testing, continuous integration, and code quality monitoring.

- Automated testing framework
- CI/CD pipeline
- Code coverage reporting
- Code quality monitoring through SonarCloud
- Automated build and test workflows

### Prerequisites

- Qt development environment
- CMake
- Google Test framework
- SonarCloud account (for code quality monitoring)

### Building the Project

2. Build the project:
   ```bash
   qmake
   make
   ```

### Running Tests

To run the test suite:

```bash
./tests/tests
```

- Code coverage is monitored through Coveralls
- Code quality is analyzed using SonarCloud
- Automated testing through GitHub Actions
- Continuous integration ensures code quality and stability
