# old-keycloak-admin-console

This is the old AngularJs version of the Keycloak Admin Console - Do not use in production!

**THIS VERSION IS NOT MAINTAINED AND IS CONSIDERED TO BE INSECURE**

To use, simply unzip the file into your `/themes` directory. Then set the admin theme to `keycloak`.

## Special instructions for newer builds of Keycloak

Changes to the server caused a bug in the old console which will not be fixed. However, there is a workaround. For Keycloak builds created after August 17, 2023 you will need to specify an application route in your URL. So instead of accesing the console with something like:

http://localhost:8180/admin/master/console/

you will need to say something like:

http://localhost:8080/admin/master/console/#/master/realm-settings
