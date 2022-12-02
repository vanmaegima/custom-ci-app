# Sample Compose App For A Custom CI Pipeline

This is a sample compose App is used for an example of a custom CI pipeline integration with a FoundriesFactory.

In particular, it provides guidance to accomplish the following in a scope of a github actions workflow:

- building multi-arch container images and pushing them to [Foundries Registry](https://hub.foundries.io);
- building [Foundries Compose App](https://docs.foundries.io/latest/tutorials/compose-app/compose-app.html) and pushing it to [Foundries Registry](https://hub.foundries.io);
- composing [TUF Target role metadata](https://theupdateframework.io/metadata/#targets-metadata-targetsjson) compliant with FoundriesFactory TUF requirements;
- adding the composed TUF Targets to [FoundriesFactory's Targets](https://docs.foundries.io/latest/tutorials/creating-first-target/what-is-a-target.html).
