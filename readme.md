![Logo of the project](./logo.png)

# Awesome Project Template

> Based on the React-Native Awesome Project template with some addons that will help to streamline a project initiation

## Installing / Getting started

Copy the code using your `git` desktop application or by:

```shell
gh repo clone wiezmankimchi/basic-rn-project
cd basic-rn-project
npm install
cd ios
pod install
```

- We clone the project to the `basic-rn-project` folder
- Installing all dependencies in the project root folder
- Installing iOS specific `cocoapods` dependencies

### What add-ons are includes

The project includes the following:

- React-Native [_Link_](https://reactnative.dev/)
- React Navigation [_Link_](https://reactnavigation.org/)
- NativeBase [_Link_](https://nativebase.io/)
- React Native Vector Icons [_Link_](https://github.com/oblador/react-native-vector-icons)`/`[_Icons Directory_](https://oblador.github.io/react-native-vector-icons/)

## Basic Structure

The project includes:

1. Home Screen
2. Navigation to 'Details' screen
3. Home Icon Navigation

And state what happens step-by-step.

### Building

If your project needs some additional steps for the developer to build the
project after some code changes, state them here:

```shell
./configure
make
make install
```

Here again you should state what actually happens when the code above gets
executed.

### Deploying / Publishing

In case there's some step you have to take that publishes this project to a
server, this is the right time to state it.

```shell
packagemanager deploy awesome-project -s server.com -u username -p password
```

And again you'd need to tell what the previous code actually does.

## Features

What's all the bells and whistles this project can perform?

- What's the main functionality
- You can also do another thing
- If you get really randy, you can even do this

## Configuration

Here you should write what are all of the configurations a user can enter when
using the project.

#### Argument 1

Type: `String`  
Default: `'default value'`

State what an argument does and how you can use it. If needed, you can provide
an example below.

Example:

```bash
awesome-project "Some other value"  # Prints "You're nailing this readme!"
```

#### Argument 2

Type: `Number|Boolean`  
Default: 100

Copy-paste as many of these as you need.

## Contributing

When you publish something open source, one of the greatest motivations is that
anyone can just jump in and start contributing to your project.

These paragraphs are meant to welcome those kind souls to feel that they are
needed. You should state something like:

"If you'd like to contribute, please fork the repository and use a feature
branch. Pull requests are warmly welcome."

If there's anything else the developer needs to know (e.g. the code style
guide), you should link it here. If there's a lot of things to take into
consideration, it is common to separate this section to its own file called
`CONTRIBUTING.md` (or similar). If so, you should say that it exists here.

## Links

Even though this information can be found inside the project on machine-readable
format like in a .json file, it's good to include a summary of most useful
links to humans using your project. You can include links like:

- Project homepage: https://your.github.com/awesome-project/
- Repository: https://github.com/your/awesome-project/
- Issue tracker: https://github.com/your/awesome-project/issues
  - In case of sensitive bugs like security vulnerabilities, please contact
    my@email.com directly instead of using issue tracker. We value your effort
    to improve the security and privacy of this project!
- Related projects:
  - Your other project: https://github.com/your/other-project/
  - Someone else's project: https://github.com/someones/awesome-project/

## Licensing

One really important part: Give your project a proper license. Here you should
state what the license is and how to find the text version of the license.
Something like:

"The code in this project is licensed under MIT license."