            Angular  Modules

        Modules − Modules are used in Angular JS to put logical boundaries in your application. Hence, instead of coding everything into one application, you can instead build everything into separate modules to separate the functionality of your application. Let’s inspect the code which gets added to the demo application.
        In Visual Studio code, go to the app.module.ts folder in your app folder. This is known as the root module class.
        

        A module is made up of the following parts −
        
        Bootstrap array − This is used to tell Angular JS which components need to be loaded so that its functionality can be accessed in the application. Once you include the component in the bootstrap array, you need to declare them so that they can be used across other components in the Angular JS application.
        
        Export array − This is used to export components, directives, and pipes which can then be used in other modules.
        Import array − Just like the export array, the import array can be used to import the functionality from other Angular JS modules.
        

                Angular  –Architecture -

            Each application consists of Components.
                A component consists of −
            Class − This is like a C++ or Java class which consists of properties and methods.
            Metadata − This is used to decorate the class and extend the functionality of the class.
            Template − This is used to define the HTML view which is
                displayed in the application.
            
            
                    Angular  -Components

            Components are a logical piece of code for Angular JS application. A Component consists of the following
            Template − This is used to render the view for the application. This contains the HTML that needs to be rendered in the application. This part also includes the binding and directives.
            
            Class − This is like a class defined in any language such as C. This contains properties and methods. This has the code which is used to support the view. It is defined in TypeScript.
            Metadata − This has the extra data defined for the Angular class. It is defined with a decorator.
            
            
            The class decorator. The class is defined in TypeScript. The classnormally has the following syntax in TypeScript.
            class classname{
            Propertyname: PropertyType= Value
            }
            Example:
            export class AppComponent{
            appTitle: string = 'Welcome’;
            }
            

            Metadata - This is used to decorate Angular JS class with additional information.
            
            Template - This is the view which needs to be rendered in the application.
            
