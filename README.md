# Script for automating the Container certification tests using Travis CI

To customize our build we have used below variables in  our .travis.yml file. So make sure that you have define the environment variables in your Travis CI’s Repository Settings.

__USERNAME__ - username of your image registry(quay.io/docker.io) <br />
__PASSWORD__ - password of your image registry <br />
__IMAGE_REGISTRY__ - where you have uploaded your container image(quay.io/docker.io) <br />
__IMAGE_NAMESPACE__ - namespace of your image registry(it may be similar to the username) <br />
__IMAGE_NAME__ - the name of your container image <br />
__ARCH__ - architecture on which you want to execute the container certification test <br />
__IMAGE_TAG__ - tag attached to the container image <br />
__PYXIS_API_TOKEN__ - container API key created on the connect portal <br />
__PROJECT_ID__ - Container image project id <br />
