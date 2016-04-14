# ViperTyphoon

##*Generamba:* [get generamba](https://github.com/rambler-ios/Generamba)

### My version realization Generamba with using Viper + Typhoon

### Overview

[![Build Status](https://travis-ci.org/rambler-ios/Generamba.svg)](https://travis-ci.org/rambler-ios/Generamba)
[![Gem Version](https://badge.fury.io/rb/generamba.svg)](https://badge.fury.io/rb/generamba)

**Generamba** is a code generator made for working with Xcode. Primarily it is designed to generate VIPER modules but it is quite easy to customize it for generation of any other classes (both in Objective-C and Swift).

*We keep evolving Generamba:* [changelog](https://github.com/rambler-ios/Generamba/blob/develop/CHANGELOG.md), [release notes](https://github.com/rambler-ios/Generamba/releases).

### Usage
1. Run [`generamba setup`](https://github.com/rambler-ios/Generamba/wiki/Available-Commands#basic-generamba-configuration) in the project root folder. This command helps to create [Rambafile](https://github.com/rambler-ios/Generamba/wiki/Rambafile-Structure) that define all configuration needed to generate code. You can modify this file directly in future.
2. Add all templates planned to use in the project to the generated [Rambafile](https://github.com/rambler-ios/Generamba/wiki/Rambafile-Structure). You can begin with one of the templates from our catalog: `{name: 'rviper_controller'}`.
3. Run [`generamba template install`](https://github.com/rambler-ios/Generamba/wiki/Available-Commands#template-installation). All the templates will be placed in the '/Templates' folder of your current project.
4. Run [`generamba gen [MODULE_NAME] [TEMPLATE_NAME]`](https://github.com/rambler-ios/Generamba/wiki/Available-Commands#module-generation) - It creates module with specific name from specific template.