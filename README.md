# static-web-server

The moment the web clicked: HTML + CSS served from my laptop with a single Python command.

```bash
python3 -m http.server
```

## Motivation

Computer science is layers of abstraction stacked on top of each other. I've built projects with npm, React and Django to learn frontend and backend, but I never fully understood what was happening underneath. Like the OSI model, I was only ever working at the top layer.

When you strip everything away, it becomes really simple: a static web server, an HTML file and a CSS file. Run one command, and like magic, your name appears on the screen.

This repo is where I explore that simple foundation and build back up from it, one layer at a time.

## How to run

```bash
git clone https://github.com/fizza1298/static-web-server.git
cd static-web-server
python3 -m http.server 8000 --bind 127.0.0.1
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

## Building it back up

- [x] Serve a static HTML + CSS page
- [ ] Add JavaScript to make the page interactive
- [ ] Replace `http.server` with a Flask backend that runs code on each request
- [ ] Save data to a file or database
- [ ] Deploy it online