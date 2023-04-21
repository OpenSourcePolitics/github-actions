# Custom actions

### Continous integration related actions
#### [Rspec action](https://github.com/OpenSourcePolitics/rspec-action)
Allows to run RSpec tests in a GitHub workflow.
- Uses:
  - cache-precompile-action to speed up the tests suite.

#### [Lint action](https://github.com/OpenSourcePolitics/lint-action)
Allows to run Rubocop, JS Lint and ERB lint in a GitHub workflow.

#### [Cache precompiled assets](https://github.com/OpenSourcePolitics/cache-precompile-action)
Allows to cache precompiled assets in a GitHub workflow.

### Continous deployment related actions
#### [Publish gem action](https://github.com/OpenSourcePolitics/publish-gem-action)
Allows to release and publish a Ruby gem on RubyGems.org.

### [Deploy container action](https://github.com/OpenSourcePolitics/deploy-container-action)
Allows to deploy a Docker container on a Scaleway serverless service.
- Uses:
  - Scaleway CLI to deploy the container.
  - Build and push images action to build and push the Docker image.

### Docker and Kubernetes related actions
#### [Build and push images action](https://github.com/OpenSourcePolitics/build-and-push-images-action)
Allows to build and push Docker images to a Docker registry.

#### [Build and test images action](https://github.com/OpenSourcePolitics/build-and-test-images-action)
Allows to build and test Docker images.
- Uses:
  - Build and push images action to build the Docker image. (Without pushing it to the registry)

#### [Clean tag action](https://github.com/OpenSourcePolitics/clean-tag-action)
Allows to clean a tag on a Docker registry.
