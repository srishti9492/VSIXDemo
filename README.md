# VSIXDemo
Vsix Demo 

Misc:
>>https://stackoverflow.com/questions/19427333/how-to-find-a-projectitem-by-the-file-name

>>
https://msdn.microsoft.com/en-us/library/envdte._solution.open.aspx

>>
https://www.codeproject.com/Articles/36219/Exploring-EnvDTE

>>
ContextMenu:
https://www.viva64.com/en/b/0169/

>>
https://dvanderboom.wordpress.com/page/8/

>>
https://msdn.microsoft.com/en-us/library/d790tay6.aspx

>>
https://abhijitjana.net/2011/05/02/customizing-visual-studio-extension-icon-in-visual-studio-2010/

****************************************************************************************************************

VSIX PROJECT:

command-login.cs>Button
tools>Button

custom command>
extensibility> 

application config:
>>>>>>>>>>>
Modifications running from Folder named 14
C:\Users\srsolank\AppData\Local\Microsoft\VisualStudio\14.0Exp\Extensions\Srishti Solanki\TestVSIX_1\1.0\App.config 

Topic reference:
1.Add custom configuration file:
https://social.msdn.microsoft.com/Forums/vstudio/en-US/5c209891-de27-4ff3-91f7-8598d4c7a705/how-to-read-data-from-a-configuration-file-in-visual-studio-plugin?forum=vsx


2.
https://yaozhenhua.wordpress.com/2012/05/28/copy-app-config-in-the-project-reference/


3.
https://github.com/Microsoft/msbuild/issues/1307


4.Make changes to MSBuild:
https://github.com/Microsoft/msbuild/blob/fd25bc9c7deb56dbfe51621afb1021056f410241/src/XMakeTasks/Microsoft.Common.CurrentVersion.targets#L578-L582


http://kitsula.com/Article/How-to-exclude-xml-doc-files-from-msbuild


MsBuild.exe build.file /p:AllowedReferenceRelatedFileExtensions=none


1.
First output files get copied to path on running in debug mode>>>>
C:\Users\srsolank\AppData\Local\Microsoft\VisualStudio\14.0Exp\Extensions\Srishti Solanki\VSIXProjectADC\1.0

2.
After installing extension>>>>
C:\Users\srsolank\AppData\Local\Microsoft\VisualStudio\14.0\Extensions\mqbjogem.d4f
>>>>gets created where changes can be made to app.config


