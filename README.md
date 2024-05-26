# Beginner-CLJS-Airgapped
These are notes and instructions on how to build a Clojurescript React dev environment in an airgapped environment

## Challenge
### Requirements
1. You want to use Clojurescript to build a responsive webpage
2. React is required
3. YOU ARE UNABLE (or don't want to) USE NPM

### NPM concern
Development is fast in this day an age, but there is a real concern about using external libraries.
Constantly updating or bringing in code from the internet, enables more methods to bring in malicious code or break the system when an update happens.

This repo answers the question, is it possible to build using Clojurescript and Reagent without requiring npm or other node.js package system (that is not frozen)
