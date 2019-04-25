# react-native-otp-inputs  v2.0.1 errors
To display react-native-otp-inputs  library problem

to setup project
npm install 

and start on mobile or emulator using 
react-native run-android


issue is marked here  : https://github.com/dsznajder/react-native-otp-inputs/issues/20

error : 
Loading dependency graph, done.
error: bundling failed: Error: While trying to resolve module `react-native-otp-inputs` from file `F:\SampleProject\App.js`, the package `F:\SampleProject\node_modules\react-native-otp-inputs\package.json` was successfully found. However, this package itself specifies a `main` module field that could not be resolved (`F:\SampleProject\node_modules\react-native-otp-inputs\lib\index.tsx`. Indeed, none of these files exist:

  * `F:\SampleProject\node_modules\react-native-otp-inputs\lib\index.tsx(.native||.android.js|.native.js|.js|.android.json|.native.json|.json)`
  * `F:\SampleProject\node_modules\react-native-otp-inputs\lib\index.tsx\index(.native||.android.js|.native.js|.js|.android.json|.native.json|.json)`
    at ResolutionRequest.resolveDependency (F:\SampleProject\node_modules\metro\src\node-haste\DependencyGraph\ResolutionRequest.js:103:15)
    at DependencyGraph.resolveDependency (F:\SampleProject\node_modules\metro\src\node-haste\DependencyGraph.js:272:4579)
    at dependencies.map.relativePath (F:\SampleProject\node_modules\metro\src\DeltaBundler\traverseDependencies.js:376:19)
    at Array.map (<anonymous>)
    at resolveDependencies (F:\SampleProject\node_modules\metro\src\DeltaBundler\traverseDependencies.js:374:16)
    at F:\SampleProject\node_modules\metro\src\DeltaBundler\traverseDependencies.js:212:33
    at Generator.next (<anonymous>)
    at step (F:\SampleProject\node_modules\metro\src\DeltaBundler\traverseDependencies.js:297:313)
    at F:\SampleProject\node_modules\metro\src\DeltaBundler\traverseDependencies.js:297:473
    at process._tickCallback (internal/process/next_tick.js:68:7)
 BUNDLE  [android, dev] ./index.js ▓▓▓▓▓▓▓▓▓▓░░░░░░ 67.2% (396/483), failed


 
