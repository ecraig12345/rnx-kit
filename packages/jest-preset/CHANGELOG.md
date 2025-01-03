# Change Log - @rnx-kit/jest-preset

## 0.2.1

### Patch Changes

- cc2556c: Support ESM config files
- Updated dependencies [cc2556c]
  - @rnx-kit/tools-react-native@2.0.3

## 0.2.0

### Minor Changes

- 3afb5fa: Bump minimum Node version to 16.17

## 0.1.18

### Patch Changes

- 44e8dab: Look for `@react-native/babel-preset` before falling back to
  `metro-react-native-babel-preset`

## 0.1.17

### Patch Changes

- 5115f16: Support new `loadConfig` signature from
  `@react-native-community/cli-config`

## 0.1.16

### Patch Changes

- dafd4e95: Resolve `react-native` starting from project root
- 91b10ad1: Resolve presets so Jest can find them in pnpm setups

## 0.1.15

### Patch Changes

- 55756581: Resolve correct `@react-native-community/cli` instance through
  `react-native`
- Updated dependencies [55756581]
  - @rnx-kit/tools-node@2.1.0

## 0.1.14

### Patch Changes

- a98b0421: Add support for react-native 0.71

## 0.1.13

### Patch Changes

- 6c59f781: Add support for react-native-windows

## 0.1.12

### Patch Changes

- a1c819b7: `@office-iss/react-native-win32` and `react-native-macos` need to be
  transformed because they contain Flow typed files

## 0.1.11

### Patch Changes

- 641d8978: Use `@ts-ignore` instead since we don't know which
  `@react-native-community/cli` version is used

## 0.1.10

### Patch Changes

- 78a6c4ed: Use publicly exported `loadConfig` if it exists

## 0.1.1

Wed, 04 Aug 2021 10:08:23 GMT

### Patches

- Fix incorrect peer dependencies: added `@babel/core` and made the others
  optional since this package can be used without react-native.
  (4123478+tido64@users.noreply.github.com)

## 0.1.0

Thu, 29 Jul 2021 19:42:04 GMT

### Minor changes

- @rnx-kit/jest-preset is a Jest preset for React Native
  (4123478+tido64@users.noreply.github.com)
