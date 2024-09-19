## Testing Multi-stage container for Spring boot application.

With multi-stage builds, a Docker build uses one base image for compilation, packaging, and unit tests and then a separate image for the application runtime.
As a result, the final image is smaller in size since it doesn’t contain any development or debugging tools.
By separating the build environment from the final runtime environment, you can significantly reduce the image size and increase the security of your final images.
