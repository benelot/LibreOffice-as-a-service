# LibreOffice-as-a-service
Make LibreOffice available to your Java application as a service and use them with the examples.

You can use this project as a starting point to write your own applications using LibreOffice as a document manipulation service.

If you want to use Maven instead of the SDK, checkout my other repository: [benelot/LibreOffice-as-a-Maven](https://github.com/benelot/LibreOffice-as-a-Maven)

## Get started

1. Install [LibreOffice](http://www.libreoffice.org/download) & the [LibreOffice SDK](http://www.libreoffice.org/download) (5.0 or greater)
2. Install [Eclipse](http://www.eclipse.org/) IDE for Java Developers & the [LOEclipse plugin](https://marketplace.eclipse.org/content/loeclipse)
3. Import the project in Eclipse (File->Import->Existing Projects into Workspace)
4. Let Eclipse know the paths to LibreOffice & the SDK (Project->Properties->LibreOffice Properties)
5. Setup Run Configuration
    * Select the example you want to run
    * Go to Run->Run Configurations
    * Create a new run configuration of the type "Java Application"
    * Run!
    * *Hint: Show the error log to view the output of the run configuration (Window->Show View->Error Log)*
	
This has been adapted from: [https://github.com/smehrbrodt/libreoffice-starter-extension](smehrbrodt/libreoffice-starter-extension: LibreOffice extension boilerplate)
