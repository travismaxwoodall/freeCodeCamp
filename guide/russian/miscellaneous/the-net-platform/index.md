---
title: The Net Platform
localeTitle: Сетевая платформа
---
**Платформа .NET** - это большой и всеобъемлющий набор фреймворков и библиотек, которыми управляет [Microsoft](https://www.microsoft.com/net) . C # - самый популярный язык, используемый для разработки ряда приложений .NET, таких как [веб-приложения](http://www.asp.net/) , [приложения](http://www.asp.net/) [windows aps](https://dev.windows.com/en-us/) , [Mac и iPhone](https://www.xamarin.com/platform) .

Мы начнем с изучения языка программирования C # и познакомим вас с средой разработки, структурами проектов, методами и передовыми методами, которые вы будете выполнять в качестве профессионального разработчика.

Сначала давайте начнем с кратким обзором платформы .NET и избавьтесь от некоторых жаргонов. Не волнуйтесь, вам не нужно знать подробно об этом в этот момент.

*   [.NET Framework](https://msdn.microsoft.com/en-gb/library/w0x726c2(v=vs.110) .aspx): ( _произносится dot net_ ) обеспечивает конфигурацию вашего приложения для работы поверх нее. Он предоставляет все услуги, необходимые приложениям; например, связь с базой данных, сетями, файловыми системами, которые обычно используются для создания консольных, настольных, сетевых, мобильных и игровых приложений.
    
    *   [CLR (Common Language Runtime)](https://msdn.microsoft.com/en-us/library/8bs2ecf4(v=vs.100) .aspx): это среда исполнения для вашего приложения, которая управляет жизненным циклом. CLR предоставляет службы, такие как управление памятью, и:
    
    1\. реализация [стандарта CLI (Common Language Infrastructure)](http://www.ecma-international.org/publications/standards/Ecma-335.htm) 2. Предназначен для независимой от платформы. Платформа относится к компьютерной архитектуре и операционной системе. 3. независимый язык, например, может использоваться для C #, C ++, [VB.NET\] \[vbnet\] и \[F #\] \[fsharp\].](https://msdn.microsoft.com/en-us/library/system.io(v=vs.110)
    
*   Компилятор C-Sharp: `csc.exe` - это компилятор, который преобразует код C # в Microsoft Intermediate Language (MSIL), обычно называемый IL. Он определяет инструкции, которые CLR может понять. Задача CLR состоит в том, чтобы прочитать эти инструкции и преобразовать их в понятные машиной инструкции.
    
*   Библиотеки классов: он содержит тысячи встроенных классов для использования вашего приложения, например \[ `System.IO` .aspx) для чтения / записи потоков данных, [`HttpClient`](https://msdn.microsoft.com/en-us/library/system.net.http.httpclient(v=vs.118) .aspx) отправляет данные по сети, [`ASP.NET`](http://www.asp.net/) для веб-приложений, [`ADO.NET`](https://msdn.microsoft.com/en-us/library/h43ks021(v=vs.110) .aspx) для доступа к данным для реляционных баз данных (например, Microsoft SQL Server и MySQL) и [Windows Communication Foundation (WCF)](https://msdn.microsoft.com/en-us/library/ms735119(v=vs.90) .aspx) для сервис-ориентированных приложений, которые обмениваются данными с такими протоколами, как HTTP, REST, SOAP и TCP и т. Д.
    
*   Язык программирования C # ( _произносится как «C-sharp»_ ): C # имеет синтаксис, подобный Java, C ++ и Javascript. Это:
    
    1.  используется для написания приложений, служб и библиотек многократного использования.
    2.  разработанный для работы с платформой .NET.
    3.  строго типизированный, высокоуровневый объектно-ориентированный язык.
    
    *   [.NET Core](https://blogs.msdn.microsoft.com/dotnet/2014/12/04/introducing-net-core/) : недавнее стремление Microsoft перейти к open source, кросс-платформенной разработке, поставляемой как пакеты [Nuget](https://www.nuget.org/) . Они работают с сообществом [Mono](http://www.mono-project.com/) , которое представляет собой реализацию платформы Microsoft .NET для создания приложений в Windows, Linux и iOS.
        
    *   [Silverlight](https://www.microsoft.com/silverlight/) : в первую очередь предназначен для фокусировки на подключаемом модуле веб-браузеров, чтобы обеспечить обогащение мультимедиа.
        
    *   [.NET для приложений Windows](https://dev.windows.com/en-us/) : используется для создания приложений Windows 8.x с помощью C #.
        

## Язык программирования C #

Следующий шаг, чтобы изучить язык программирования C # .