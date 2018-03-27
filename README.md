# Mobile Web Specialist Certification Course
---

## Project Overview: Stage 2

For the **Restaurant Reviews projects**, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage Two**, you will take the responsive, accessible design you built in Stage One and connect it to an external server. You’ll begin by using asynchronous JavaScript to request JSON data from the server. You’ll store data received from the server in an offline database using IndexedDB, which will create an app shell architecture. Finally, you’ll work to optimize your site to meet performance benchmarks, which you’ll test using Lighthouse.

### How to use the project

1. Go to the project directory

2. In this folder, start up a simple HTTP server to serve up the site files on your local computer. You can start a webserver with Python. In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

3. With your HTTP server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.

P.s. You need first to start the server for the restaurants!

### How to start the server for the restaurants

1. Download this repository from GitHub: https://github.com/udacity/mws-restaurant-stage-2

2. Navigate to the folder where you downloaded the repository

3. Run `npm install` to install the dependencies

4. Run `node server` to start the server