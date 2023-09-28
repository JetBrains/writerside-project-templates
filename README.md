[![JetBrains incubator project](https://jb.gg/badges/incubator-flat-square.svg)](https://confluence.jetbrains.com/display/ALL/JetBrains+on+GitHub)

A collection of new project templates for [Writerside](https://lp.jetbrains.com/writerside/).

Every branch has its own template: a fully working Writerside project to start with.

To add a template project, create a new branch from the `main` branch and configure it as necessary.

Keep the `createZip` script in every branch, only update the name of the output file.
Use it to archive the project from a specific branch into a ZIP file,
which can be added to Writerside resources
along with the relevant code for the New Project wizard.

- `main` is the basic starter project with one help instance and one topic to get you started with Writerside.
- `playground` is a starter project where users can play around with various features.
  It includes two help instances with topics that cover content re-use,
  as well as examples of combining MD with semantic markup.
- `apidocs` is a starter project that shows off how automatic API doc generation works.