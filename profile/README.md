# 🧱 Bazel Starters

Welcome to **bazel-starters** — a collection of ready-to-go, language-specific starter repos for getting productive with [Bazel](https://bazel.build) fast.

## Why is Bazel so hard to get started with?

Bazel is a powerful, fast, and scalable build system — but it's famously tricky to adopt. The learning curve comes from:

- 🧩 Its highly customizable nature (and endless config options)
- 🔄 Needing to re-learn tooling (formatting, linting, testing, dependency management)
- 🧱 Writing a lot of boilerplate before you even build "Hello, World"
- 🐛 Getting your `.bazelrc`, toolchains, and external deps just right

We’ve been there. That’s why these starter repos exist.

## What's Included

Each starter repo includes:

- 📦 **Curated `bazelrc` flags** via [`bazelrc-preset.bzl`](https://github.com/bazel-contrib/bazelrc-preset.bzl)
- 🧰 **Developer environment setup** with [`bazel_env.bzl`](https://github.com/buildbuddy-io/bazel_env.bzl)
- 🎨 **Formatting and linting** built-in, using [`rules_lint`](https://github.com/aspect-build/rules_lint)
- ✅ **Pre-commit hooks** for automatic linting and formatting
- 📚 **Language-specific package manager** integration (e.g. `pip`, `go.mod`, `npm`, etc.)
- 🧱 **Latest Bazel version** pinned and working
- 🐳 **Docker container** support using [`rules_img`](https://github.com/bazel-contrib/rules_img)
- 🧪 **Code generation tools** (e.g. [`copier`](https://copier.readthedocs.io), `scaffold`, `yeoman`) to help you and your team **stamp out new services or components quickly**

## Get Started

1. Pick the repo for your preferred language
2. Click the big green **“Use this template”** button on the repo homepage
3. Name your new repo and start coding — Bazel is ready to go!

You can also choose a subset of the features and languages.
Install the [scaffold](https://hay-kot.github.io/scaffold/) tool and run
`scaffold new github.com/aspect-build/aspect-workflows-template` to launch an interactive wizard.

## Multi-language project?

If you need to build a full-stack monorepo with multiple languages, check out:

➡️ [`starter-kitchen-sink`](https://github.com/bazel-starters/kitchen-sink)

It includes everything wired together — perfect for full-featured Bazel exploration.

## Contributing

We welcome contributions!

The source-of-truth for these templates is https://github.com/aspect-build/aspect-workflows-template
That repo has a GitHub Actions automation to run the Scaffold tool on a number of [pre-defined "presets"](https://github.com/aspect-build/aspect-workflows-template/blob/c5d65f53dba2359ab2ec797e33a418cf1b946cc6/scaffold.yaml#L147-L191),
and each of these is simply pushed to the corresponding Git repo on every commit to `main`.

Please create your issues or PRs over there.

---

Built with ❤️ by folks at Aspect Build who want Bazel to Just Work™️.
