# FreeAssertions

**FreeAssertions** is a NuGet meta-package that ensures compatibility with version 7.x of FluentAssertions, which is licensed under Apache 2.0. This package prevents accidental upgrades to later versions of FluentAssertions, which may have different licensing terms.

## Why This Package?

FluentAssertions, up to version 7.x, was licensed under Apache 2.0. Starting with later versions, licensing changes introduced potential fees for developers. To avoid these changes, this package locks the dependency to version 7.x.

## How It Works

- This meta-package declares a dependency on FluentAssertions 7.x (`[7.1.0,8.0.0)`).
- It ensures that FluentAssertions remains on version 7.x and does not upgrade to later versions.

## Usage

Add the FreeAssertions package to your project, and it will automatically resolve FluentAssertions to a version within the 7.x range.

## Legal Disclaimer

- This package is not affiliated with or endorsed by the authors of FluentAssertions.
- FluentAssertions is a trademark of its respective owners.
- This package exists solely to assist developers in maintaining compatibility with version 7.x under the Apache 2.0 license.
- For the latest information about FluentAssertions, visit the [official repository](https://github.com/fluentassertions/fluentassertions).

## License

This meta-package is licensed under the MIT License. FluentAssertions itself is licensed under the Apache 2.0 license (for version 7.x). For details, refer to the respective licenses.
