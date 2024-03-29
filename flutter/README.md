# WebSocket Counter Flutter

[![build][ci_badge]][ci_link]
![coverage][coverage_badge]
[![style: very good analysis][very_good_analysis_badge]][very_good_analysis_link]
[![License: MIT][license_badge]][license_link]

Generated by the [Very Good CLI][very_good_cli_link] 🤖

A Flutter real-time counter which integrates with [Dart Frog][dart_frog_link] and WebSockets.

Learn about [how it was made](https://verygood.ventures/blog/dart-frog-full-stack-tutorial).

![demo](./assets/demo.gif)

---

## Getting Started 🚀

To run the app either use the launch configuration in VSCode/Android Studio or use the following command:

```sh
# Run the Flutter app.
flutter run
```

Then, clone and run the Dart Frog WebSocket Counter backend:

```sh
# Install Dart Frog CLI
dart pub global activate dart_frog_cli

# Clone the GitHub Repository.
git clone https://github.com/VeryGoodOpenSource/dart_frog

# Change into the web_socket_counter example directory.
cd dart_frog/examples/web_socket_counter

# Install the dependencies.
dart pub get

# Run the development server.
dart_frog dev
```

[ci_badge]: https://github.com/VGVentures/web_socket_counter_flutter/actions/workflows/main.yaml/badge.svg
[ci_link]: https://github.com/VGVentures/web_socket_counter_flutter/actions/workflows/main.yaml
[coverage_badge]: coverage_badge.svg
[dart_frog_link]: https://dartfrog.vgv.dev
[license_badge]: https://img.shields.io/badge/license-MIT-blue.svg
[license_link]: https://opensource.org/licenses/MIT
[very_good_analysis_badge]: https://img.shields.io/badge/style-very_good_analysis-B22C89.svg
[very_good_analysis_link]: https://pub.dev/packages/very_good_analysis
[very_good_cli_link]: https://github.com/VeryGoodOpenSource/very_good_cli
