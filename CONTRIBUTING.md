# Contributing to SecureShield Extensions

> Maintained by [Naveen Parmar](https://github.com/NaveenParmar0)

## Changelog

The relevant changes done to each add-on are tracked in its own `CHANGELOG.md` file, when doing a
pull request consider updating it with the change done. The changes should be added to the
Unreleased section.

## Help

The help of each add-on should be updated accordingly to the changes done. The help files are under
`addOns/<addOnId>/src/main/javahelp/`, only the main files (English, under `help` directory) need
to be changed.

## Contribution Guidelines

- Fork the repository: [NaveenParmar0/secureshield-extensions](https://github.com/NaveenParmar0/secureshield-extensions)
- Create a feature branch and submit a pull request with a clear description of your changes
- Ensure all unit tests pass before submitting: `./gradlew :addOns:<addon>:test`
- Follow the code style conventions enforced by Spotless (`./gradlew spotlessCheck`)
