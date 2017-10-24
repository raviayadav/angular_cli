# angular_cli

* ng new ProjectName //Creates a new cli project
* ng serve --open or -o //Opens the project in default web browser.
* ng serve --port or -p portNo. // specifies a port, default is 4200
* ng serve live-reload or -lr // specifies live reload. Default is enabled
* ng new ProjectName --skip install // this will skip installing the dependencies(auto running of npm i wont happen)
* ng new ProjectName --dry-run or -d // this will give as a dry run without actually creating the files on disk
* ng new demoApp3 --skip-install --directory newProjectName --source-dir ReplacementForSrcFolderName. // project name changes to newProjectName and src folder name changes to newProjectName
* ng new demoApp4 --skip install --prefix demo --style scss // will change the app prefix to demo and default files for styles are .scss
* ng new demoApp5 --inline-template true --inline-style true --skip-install  // if html and css parts isto be written inside component we use this
* ng g c --flat:true or false // boolean, default false, when true generate component files in src/app instead of a folder with component name
* ng g c componentName --inline-template or -it // defualt false
* ng g c componentName --inline-style or -is // defualt false
* ng g c componentName --prefix:true/false // defualt true, is taken from angularcli.json eg. --prefix my 
* ng g c componentName --spec:boolean // defualt true. creates files for unit testing
* ng g d directiveName --flat:boolean // def true, generates files in src/app
* ng g d directiveName --prefix:boolean // def true, uses prefix in angularcli.json
* ng g d directiveName --spec:boolean // def true
* ng g s serviceName --flat:boolean // def true
* ng g s serviceName --spec // def true
* ng g p pipeName --flat:boolean //def true
* ng g p pipeName --spec:boolean //def true
* ng g cl className // to generate a class
* ng g i interfaceName // to generate an interface
* ng g e directions // to generate enumerations
* ng g cl models/contact // will generate inside models folder
* ng g m moduleName // to generate modules eg. ng g m admin
* ng g c login -m admin/admin.module // will update the admin.module file and not app.module for login component
* ng new ProjectName --routing // will create a routing module which will be inside root module i.e app.module
* 
