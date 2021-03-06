# Contributing In General

Our project welcomes external contributions. If you have an itch, please feel
free to scratch it.

To contribute code or documentation, please submit a [pull request](https://github.com/IBM/nodejs-idb-connector/pulls).

A good way to familiarize yourself with the codebase and contribution process is
to look for and tackle low-hanging fruit in the [issue tracker](https://github.com/IBM/nodejs-idb-connector/issues).

**Note: We appreciate your effort, and want to avoid a situation where a contribution
requires extensive rework (by you or by us), sits in backlog for a long time, or
cannot be accepted at all!**

## Proposing new features

If you would like to implement a new feature, please [raise an issue](https://github.com/IBM/nodejs-idb-connector/issues)
before sending a pull request so the feature can be discussed. This is to avoid
you wasting your valuable time working on a feature that the project developers
are not interested in accepting into the code base.

## Fixing bugs

If you would like to fix a bug, please [raise an issue](https://github.com/IBM/nodejs-idb-connector/issues) before sending a
pull request so it can be tracked.

## Legal

We have tried to make it as easy as possible to make contributions. This
applies to how we handle the legal aspects of contribution. We use the
same approach - the [Developer's Certificate of Origin 1.1 (DCO)](https://github.com/hyperledger/fabric/blob/master/docs/source/DCO1.1.txt) - that the Linux® Kernel [community](https://elinux.org/Developer_Certificate_Of_Origin)
uses to manage code contributions.

We simply ask that when submitting a patch for review, the developer
must include a sign-off statement in the commit message.

Here is an example Signed-off-by line, which indicates that the
submitter accepts the DCO:

```sh
Signed-off-by: John Doe <john.doe@example.com>
```

You can include this automatically when you commit a change to your
local git repository using the following command:

```sh
git commit -s
```

## Communication

Please feel free to connect with us on our [Ryver forum](https://ibmioss.ryver.com/index.html#forums/1000127).

You can join the Ryver community [here](https://ibmioss.ryver.com/application/signup/members/9tJsXDG7_iSSi1Q).

## Setup

Ensure that all dependencies are installed.

From the root of the project directory run:

`npm install`

## Testing

This project uses mocha for its tests.

From the root of the project directory run:

`npm test test/`
