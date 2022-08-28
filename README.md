# DockGuiBrowser

This is an example of GUI app container streamed inside a browser.

## Installation

To test it out simply download the dockerfile, move to its location and run.

```bash
docker build -t chrome-vnc .
docker run --name vnc-container -p8080:80 chrome-vnc
```
