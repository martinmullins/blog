
After a fair bit of work, I was able to get the open sourced [Serious Sam Engine](https://github.com/ptitSeb/Serious-Engine) working in the browser.
This project was a great learning experience and the result is runs fairly smoothly.
* [Github source](https://github.com/martinmullins/Serious-Engine)
* I have embedded the game below or you can load it [directly here](https://martinmullins.github.io/ssam)

Things that don't work in the build:
* Mutliplayer
* Splitscreen
* There is a small audio delay

The overall process is to use [Emscripten](emscripten.org) to compile the engine source code into wasm/js runtime.
Here's a quick summary of the steps involved porting the code base to emscripten:
* Remove threaded code (already done)
* Ensure the can be built as 32bit (already done)
* Ensure the game can be built statically (except for libraries provided by emscripten)
* Use [gl4es](https://github.com/ptitSeb/gl4es/) library to map the opengl calls to openglES
* Replace the infinite main loop with function to be called at the desired FPS from emscripten (`emscripten_set_main_loop(..)`)

{% include iframe.html src='https://martinmullins.github.io/ssam' %}
