
# About regional-environment

## What is regional-environment?

As a developer, I have encountered many situations where I have to set a complex environment for the editor to deploy, test, build, debug... every time I switch to my project. Because of this, I want a tool that helps me to do that, automatically.

Hence, I created this organization which contains a set of tools that follow the following [convention](#convention) and suggest people to create tools like so.

## Convention

 1. A *configuration item* is a file or directory which is placed in any directory whose name end with `.regional-environment`.

 2. A regional-environment plugin should uses every configuration items whose names satisfy some rules (*item filter rule*) that the plugin proposes.

 3. It's recommended for plugins to make their item filter rules based on this [npm package](https://www.npmjs.com/package/regional-environment).
