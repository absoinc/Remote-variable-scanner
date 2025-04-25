# Remote-variable-scanner
This is a FIgma plugin for scanning a selection and reporting any remote variables. These variables are not in any linked files and if you are working on a design system, you'd only want local variables assigned to your components.

## How it works
1. Select a layer, component or frame and invoke the plugin
2. The plugin scans recursively through the layers of the selection and generates a tabular report of all the remote variables, their values, and where possible, which collection and any modes from that collection.
