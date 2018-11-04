
# Example Bazel Monorepo

<p align="center">
    <img src="https://raw.githubusercontent.com/METACEO/example-bazel-monorepo/master/README-relationships.png" alt="Nest Logo"/>
</p>

Requirements / todos to prove:

- [ ] Setup bazel properly.
- [ ] Identify a theme to base this repo around: i.e. a simple inventory management system?
- [ ] Add some example models/content to the `shared` project according to the theme.
- [ ] Build the `shared` project with bazel.
- [ ] Consume the `shared` project bazel output.
- [ ] Develop some simple API endpoints to provide themed data.
- [ ] Build the Nestjs `api` project with bazel.
- [ ] Have the `www` project interact with the `api` project's endpoint.
- [ ] Build the Angular `www` project with bazel.
- [ ] Purchase a domain to host under.
- [ ] Prepare a build server that builds with bazel and releases output of both the `api` and `www` projects.
- [ ] Prove by hosting the releases.
