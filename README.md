<h1 align="center">Double Pendulum Using Curses in Python.</h1>

<p align="center"><a href="https://forthebadge.com" target="_blank"><img src="https://forthebadge.com/images/badges/built-with-love.svg" alt="Build with <3" /></a>&nbsp;<a href="https://forthebadge.com" target="_blank"><img src="https://forthebadge.com/images/badges/made-with-python.svg" alt="Made with python" /></a>&nbsp;<a href="https://forthebadge.com" target="_blank"><img src="https://forthebadge.com/images/badges/powered-by-coffee.svg"/></p>

  
<p align="center"><a href="https://github.com/psf/black" target="_blank"><img src="https://img.shields.io/badge/code%20style-black-000000.svg" alt="Code style: black" /></a>&nbsp;<a href="http://makeapullrequest.com" target="_blank"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=shields"/></p>
  
  
<h2 align="center">Does NOT work on Windows (yet), UNIX only.</h1>
<p align="center">A nice relaxing double pendulum simulation using ASCII, able to simulate multiple pendulums at once, and provide tracing of pendulums.</p>

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Quickstart](#demo)
- [Args](#args)
- [TODO](#todo)

## Features
- As mentioned, able to simulate multiple pendulums at once. 
- Able to specify the weight and mass of pendulums to create different butterfly effects.
- Uses equations from [here.](https://www.myphysicslab.com/pendulum/double-pendulum-en.html)
- Obviously a lot could be done to it (see below the Args), Any contributions are appreciated)

## Demo: 
https://user-images.githubusercontent.com/11583852/127576299-a97625a4-69bc-4887-8793-972192db6086.mov

## Quickstart:

__Dependencies:__ Python 3.2+, UNIX system.

- Clone using `https://github.com/Nekurone/double-pendulum-ascii.git` or download the zip. 
- Extract if necessary and head inside the file
- ```python3 double_pendulum.py [args]```

## Args
|short|long|help|default
|--|---|--|--|
|-h| --help | shows help message |N/A|
|-t| --trace | enables the trace functionality | off|
|-p| --pendulums |  Number of pendulums | 1|
|-m| --mass | Starting mass of pendulums | 100.0|
|-l| --length | Starting length of the arms | 250.0|
---------------------------------------------------

## TODO

Note I will not be updating the words on this TODO, but rather just checking them off, as a nice front page reminder of the work done :) 

- [ ] Add windows functionality
- [ ] Add more functionality to arguments (epsilon, weight1, weight2)
- [ ] General cleanup of variable names 
- [ ] Improve efficiency (esp in lists)
- [ ] Ddd colors :)

<h3 align="center">If you have any suggestions, or anything you'd like to add, just open a PR :)</h3>
