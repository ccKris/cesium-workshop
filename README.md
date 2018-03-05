# cesium-workshop

<p align="center">
    <a href="http://cesiumjs.org/">
        <img src="https://github.com/AnalyticalGraphicsInc/cesium/wiki/logos/Cesium_Logo_Color.jpg" width="50%" />
    </a>
</p>

A simple JavaScript app showcasing some features of [Cesium](http://cesiumjs.org/), the open-source WebGL virtual globe and map engine. Learn more about this code by reading our [associated tutorial](https://cesiumjs.org/tutorials/Cesium-Workshop/).

**Cesium version**: [1.43](http://cesiumjs.org/downloads.html).

**License**: Apache 2.0.  Free for commercial and non-commercial use.  See [LICENSE.md](LICENSE.md).

This application is intended to introduce the main features of Cesium in context, but it is by no means exhaustive. Feel free to fork and modify this example however you'd like.

Local server
------------

A local HTTP server is required to run the app.

Have python installed?  If so, from the `cesium-workshop` root directory run
```
python -m SimpleHTTPServer
```
(Starting with Python 3, use `python -m http.server 8080`).

Browse to `http://localhost:8080/`

No python?  Use Cesium's node.js server.

* Install [node.js](http://nodejs.org/)
* From the `cesium-workshop` root directory, run
* `npm install`
* `node server.js`

Browse to `http://localhost:8080/`

What's here?
------------

* [index.html](index.html) - A simple HTML page. Run a local web server, and browse to index.html to run your app, which will show our sample application.
* [Source](Source/) - Contains [App.js](Source/App.js) which is referenced from index.html.  This is where the app's code goes.
* [ThirdParty](ThirdParty/) - A directory for third-party libraries, which here includes just Cesium.
* [server.js](server.js) - A simple node.js server for serving your Cesium app.  See the **Local server** section.
* [package.json](package.json) - Dependencies for the node.js server.
* [LICENSE](LICENSE.md) - A license file already referencing Cesium as a third-party.  This starter app is licensed with [Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0.html) (free for commercial and non-commercial use).  You can, of course, license your code however you want.
* [.gitignore](.gitignore) - A small list of files not to include in the git repo.  Add to this as needed.

Cesium resources
----------------

* [Reference Documentation](http://cesiumjs.org/refdoc.html) : A complete guide to the Cesium API containing many code snippets.
* [Sandcastle](http://cesiumjs.org/Cesium/Apps/Sandcastle/index.html) : A live-coding environment with a large gallery of code examples.
* [Tutorials](http://cesiumjs.org/tutorials.html) : Detailed introductions to areas of Cesium development.
* [Cesium Forum](http://cesiumjs.org/forum.html) : A resource for asking and answering Cesium-related questions.
