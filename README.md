# Custom version of RN 57 for use with tvOS

## Why 57?
- Last version to include TabBarIOS without deprecation warnings

## Why custom?
- tvOS build was broken by default on a regular init

## Using this fork:
1. `react-native init <YOUR PROJECT NAME> --version 0.57.0`
2. Change react-native version in package.json to `https://github.com/sheck/react-native#tvOS`
3. `yarn add -D @babel/runtime`
