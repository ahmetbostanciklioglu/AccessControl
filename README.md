<div align="center">

# 🔐 Swift Basics: Access Control

**A concise, runnable playground demonstrating Swift access-control levels.**

![Platform](https://img.shields.io/badge/Platform-iOS-000000?style=flat-square&logo=apple)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Playground](https://img.shields.io/badge/Xcode-Playground-1575F9?style=flat-square&logo=xcode&logoColor=white)
![Stars](https://img.shields.io/github/stars/ahmetbostanciklioglu/AccessControl?style=flat-square&color=6E48AA)
![Last Commit](https://img.shields.io/github/last-commit/ahmetbostanciklioglu/AccessControl?style=flat-square&color=4776E6)

</div>

## 📖 Overview

Access control in Swift restricts access to parts of your code from code in other source files and modules, letting you hide implementation details and expose only the interface you intend. This repository is a concise, runnable Xcode playground learning example: it defines a small `AccessControl` struct with a `private` stored property and a `public` method, then creates an instance and calls the method to illustrate how the different access levels behave.

## 📚 What it covers

- The `private` access level, applied to the struct's `number` stored property so it is not visible outside the enclosing scope.
- The `public` access level, applied to a method (`publicFunc()`) intended to be exposed as part of the type's interface.
- Defining a `struct` with a custom `init(number:)` initializer.
- Instantiating the type and calling one of its methods in a live Swift playground.

## 🚀 Getting Started

```bash
git clone https://github.com/ahmetbostanciklioglu/AccessControl.git
cd AccessControl
unzip ControlTypes.playground.zip
open ControlTypes.playground
```

Open `ControlTypes.playground` in Xcode; the playground evaluates automatically and shows results inline in the sidebar.

## 📋 Requirements

- Xcode 12 or later
- Swift 5+
- iOS playground target (as configured in `contents.xcplayground`)

## 🧑‍💻 Author

**Ahmet Bostancıklıoğlu** — [@ahmetbostanciklioglu](https://github.com/ahmetbostanciklioglu) · ahmetbostancikli@gmail.com

---

> ⭐ If this helped you, consider giving the repo a star!
