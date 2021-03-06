HeadlesService

========================================================================
Sample Description.

In this example we'll learn how to create a long-running headless service.

WARNING: This is not a standalone sample, and should not be deployed to device directly.
It is used (packaged) in the headlesserviceui sample bar file as a captive library. If deployed
directly, it will prevent headlesserviceui from deploying it a second time, meaning that you might
experience faulty app behaviour.
!!!!!!!!!!Do not deploy this as a standalone sample!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

You will learn how to:
- Create a long-running background service and launched via system startup.
- Communicate with it through the QSettings instance. This is only one of
  many communication choices (ie. sockets, pps service, etc).

========================================================================
Requirements:

BlackBerry 10.2 Native SDK

========================================================================
Running the example:

1. Clone the Sample repository.
2. Launch BlackBerry 10.2 Native SDK, and from the File menu, select Import.
3. Expand General, and select Existing Projects into Workspace. Click Next.
4. Browse to the location of your sample directory, and then click OK.
5. The sample project should display in the Projects section. 
   Click Finish to import the project into your workspace.
6. In the Project Explorer pane, Right-click the project (for example hellocascades)
   and select Build Project.
7. In the Project Explorer pane, Right-click the project (for example hellocascades)
   and select Run As > BlackBerry C/C++ Application.
8. The application will now install and launch on your device. If not, you might
   have to set up your environment:
   http://developer.blackberry.com/native/documentation/getting_started/setting_up.html
