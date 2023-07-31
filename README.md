# XUnit_Curso_Mteherandev VisualStudioCode


Paquetes a instalar de nuget en test.csproj : 

Microsoft.NET.Test.Sdk 

xunit

xunit.runner.visualstudio

Recordar crear la referencia en test del proyecto al que se le está haciendo el testing en el test.csproj


Extensiones VSCode utilizadas

C#

.NET Install Tool for Extension Authors

.NET Core Snippet Pack

.NET Core Test Explorer


Agregar En los settings del ícono de test: Me busca los test que hayan en todo el proyecto. Mismo nombre de la carpeta de tests:
En este caso test en singular

{
    "dotnet-test-explorer.testProjectPath": "**/test.@(csproj|vbproj|fsproj)"
}

