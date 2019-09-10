# EdgeSolution

## Setup

1. Setup the Simulator

  _Using VSCode and Azure IoT Edge Extension_
  Right Click on the Edge Device and execute `Setup IoT Edge Simulator`

  _Using NPM task runner_
  `npm run setup`

2. Run solution in Simulator

  _Using VSCode and Azure IoT Edge Extension_
  Right Click on the `deployment.template.json` manifest template and execute `Build and Run in Simulator`

  _Using NPM task runner_
  `npm start`

3. Debug solution in Simulator with Solution Mode

  _Using VSCode and Zure IoT Edge Extension_
  Right click on the `deployment.debug.template.json` manifest template and execute `Build and Run in Simulator`

  _Using NPM Task runner_
  `npm run attach`

  __Attach the Debugger__
  Ensure the `filtermodule Remote Debug` configuration is selected
  Set breakpoint then attach using F5

4. Debug solution using Simulator and Single Module Mode

  TODO:  Haven't been successful with this situation yet.

5. Use Windows Configuration and Containers
  
   TODO:   Haven't been successful with this situation yet.
