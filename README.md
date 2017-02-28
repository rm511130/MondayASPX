# MondayASPX
Simple ASPX .NET Example

- Visual Studio 2015 .NET Sample Application
- Small memory footprint
- 'cf push' leverages manifest.yml
- Requires Windows Stack on PCF
- 'cf push' will generate a random-route for the Application
`
$ cf push
Using manifest file /work/MondayASPX/manifest.yml

Using stack windows2012R2...
OK
Creating app Simple_ASPX in org cardinal / space development as admin...
OK

Creating route simple-aspx-procivilian-toggle.apps.pcf4u.com...
OK

Binding simple-aspx-procivilian-toggle.apps.pcf4u.com to Simple_ASPX...
OK

Uploading Simple_ASPX...
Uploading app files from: /Users/rmeira/work/src/github.com/user/MondayASPX
Uploading 1.3M, 115 files
Done uploading               
OK

Starting app Simple_ASPX in org cardinal / space development as admin...

0 of 1 instances running, 1 starting
1 of 1 instances running

App started
OK

App Simple_ASPX was started using this command ..\tmp\lifecycle\WebAppServer.exe

Showing health and status for app Simple_ASPX in org cardinal / space development as admin...
OK

requested state: started
instances: 1/1
usage: 512M x 1 instances
urls: simple-aspx-procivilian-toggle.apps.pcf4u.com
last uploaded: Tue Feb 28 23:13:39 UTC 2017
stack: windows2012R2
buildpack: binary_buildpack

     state     since                    cpu    memory      disk      details
#0   running   2017-02-28 06:14:09 PM   0.0%   0 of 512M   0 of 1G
`

- In this example, you can test the App by going to:  https://simple-aspx-procivilian-toggle.apps.pcf4u.com/webform1.aspx
