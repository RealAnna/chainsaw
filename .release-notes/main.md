# Release notes

Release notes for `TODO`.

<!--
## ‼️ Breaking changes ‼️

## 💫 New features 💫

## ✨ UI changes ✨

## ⭐ Examples ⭐

## ⛵ Tutorials ⛵

## 📚 Docs 📚

## 🎸 Misc 🎸
-->

## 💫 New features 💫

- Allowed passing test folders by args (`chainsaw test ./folder` instead of `chainsaw test --test-dir ./folder`)

## 🔧 Fixes 🔧

- Fixed an issue when running `chainsaw migrate kuttl tests` twice on the same folder
- Fixed an issue with `chainsaw migrate kuttl tests` potentially incorrect when a `TestStep` is present

## 📚 Docs 📚

- Improved API docs for types coming from Kyverno-JSON
