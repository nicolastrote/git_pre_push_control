# GIT PRE-PUSH CONTROL

Control and stop a push by files changed and insertions made.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You need to install 
- GIT https://git-scm.com/downloads
- and a decent development environment :)

### Installing

Add your project in git
```
$ cd my_foo_project
$ git init
```
Make your commit
```
$ git commit -am "création du premier fichier"
```

Open your local file \.git\hooks\pre-push and replace the code by git_pre_push_control/pre-push
```
(see git_pre_push_control/pre-push)
```

## Running the tests

Now you can push your code and control how many files changed and insertions made.
```
git push
```

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Nicolas Trote** - *Initial work* - [nicolastrote](https://github.com/nicolastrote)

See also the list of [contributors](https://github.com/nicolastrote/git_pre_push_control/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

