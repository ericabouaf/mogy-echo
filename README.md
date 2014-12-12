# mogy-echo

Dummy echo activity for [mogy](https://github.com/neyric/mogy).

## Installation

In your mogy project, install the dependency using npm :

    $ npm install mogy-echo --save

To register the `echo` activity to Amazon Simple Workflow :

    $ mogy register

## Config

No config

## Sample Decider Usage

````javascript
activity({
    name: 'my-task',
    activity: 'echo',
    input: "Hello world !"
})
````
