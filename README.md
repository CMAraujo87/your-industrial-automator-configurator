# your-industrial-automator-configurator

Welcome!

This initial version of readme is supposed to be an initial thought of how the software is supposed to work.

This module is meant to be the installator of the solution, managing the git operations for cloning, building deploying and offering a basic user-friendly environment for the configuration.

This module is also meant to be the configurator of the solution, guiding and handling the user towards the proper structure and data configuration of the user's scenario.

The other planned modules (for now) are:
- Communication manager: This module will manage a list of connections and its properties(tags). This module is meant run once per configured driver/connection.
  - OPC-UA driver: this driver will connect and translate data from-to OPC-UA connections, by setting internal aliases to external tags.
- Business flow manager: This module is responsible for developing and deploying flows to the runtime business flow modules.
- Runtime flow module: this module is responsible for executing and monitoring an specific range of workflows.
- Visualization  manager module: This module is responsible for developing UIs to run under the Runtime visualization module.
- Runtime visualization module: This module is intended to graphically present the infomation to the end-user.
- Data collection manager module: Responsible for the data collection engineering.
- Runtime data collector module: Responsible for collecting data and storing for later analysis.
- Reporting agent module: Respnsible for periodically reading the stored data and processing, making it available to the user.