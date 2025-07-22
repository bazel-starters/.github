# 🧱 Bazel Starters

Welcome to **bazel-starters** — a collection of ready-to-go, language-specific starter repos for getting productive with [Bazel](https://bazel.build) fast.

---

## 🤔 Why is Bazel so hard to get started with?

Bazel is a powerful, fast, and scalable build system — but it's famously tricky to adopt. The learning curve comes from:

- 🧩 Its highly customizable nature (and endless config options)
- 🔄 Needing to re-learn tooling (formatting, linting, testing, dependency management)
- 🧱 Writing a lot of boilerplate before you even build "Hello, World"
- 🐛 Getting your `.bazelrc`, toolchains, and external deps just right

We’ve been there. That’s why these starter repos exist.

---

## 🚀 How to Use

1. Pick the repo for your preferred language
2. Click the big green **“Use this template”** button on the repo homepage
3. Name your new repo and start coding — Bazel is ready to go!

---

## 🧪 What's Included

Each starter repo includes:

- 📦 **Curated `bazelrc` flags** via [`bazelrc-preset.bzl`](https://github.com/bazel-contrib/bazelrc-preset.bzl)
- 🧰 **Developer environment setup** with [`bazel_env.bzl`](https://github.com/buildbuddy-io/bazel_env.bzl)
- 🎨 **Formatting and linting** built-in, using [`rules_lint`](https://github.com/aspect-build/rules_lint)
- ✅ **Pre-commit hooks** for automatic linting and formatting
- 📚 **Language-specific package manager** integration (e.g. `pip`, `go.mod`, `npm`, etc.)
- 🧱 **Latest Bazel version** pinned and working
- 🐳 **Docker container** support using [`rules_oci`](https://github.com/bazel-contrib/rules_oci)
- 🧪 **Code generation tools** (e.g. [`copier`](https://copier.readthedocs.io), `scaffold`, `yeoman`) to help you and your team **stamp out new services or components quickly**

---

## 🧪 Multi-language project?

If you need to build a full-stack monorepo with multiple languages, check out:

➡️ [`starter-kitchen-sink`](https://github.com/bazel-starters/kitchen-sink)

It includes everything wired together — perfect for full-featured Bazel exploration.

---

## 📣 Contributing

We welcome contributions!

The source-of-truth for these templates is https://github.com/aspect-build/aspect-workflows-template
That repo has a GitHub Actions automation to run the Scaffold tool on a number of "presets", and each of these is simply pushed to the corresponding Git repo.

Please create your issues or PRs over there.

---

Built with ❤️ by folks who wanted Bazel to just work.


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
