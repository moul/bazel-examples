
# These are example snippets and BUILD files for [Bazel](github.com/google/bazel).

[![GuardRails badge](https://badges.production.guardrails.io/moul/bazel-examples.svg)](https://www.guardrails.io)

  * A [recipe](android-prebuilts/README.md) for configuring AOSP
    prebuilt toolchains for Bazel.

  * A [recipe](protobuf-2.5.0/README.md) for compiling the
    protobuf 2.5.0 compiler with Bazel. We used this with AOSP i686
    toolchain to produce the `protoc` binary in the Bazel repo.

  * A [BUILD file](re2/BUILD) for compiling RE2.

  * An example of setting up a [cross-compiler](android-ndk/README.md)
