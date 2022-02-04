---
description: Host web content in your Win32, .NET, UWP apps with the Microsoft Edge WebView2 control
title: Introduction to Microsoft Edge WebView2
author: MSEdgeTeam
ms.author: msedgedevrel
ms.date: 05/06/2021
ms.topic: conceptual
ms.prod: microsoft-edge
ms.technology: webview
keywords: IWebView2, IWebView2WebView, webview2, webview, win32 apps, win32, edge, ICoreWebView2, CoreWebView2, ICoreWebView2Host, browser control, edge html, Windows Forms, WinForms, WPF, .NET, WinUI, Project Reunion
---
# Introduction to Microsoft Edge WebView2

The Microsoft Edge WebView2 control allows you to embed web technologies (HTML, CSS, and JavaScript) in your native apps.  The WebView2 control uses [Microsoft Edge][MicrosoftedgeinsiderMain] as the rendering engine to display the web content in native apps.  With WebView2, you can embed web code in different parts of your native app, or build all of the native app within a single WebView instance.  For information on how to start building a WebView2 app, navigate to [Get Started](#get-started).

:::image type="complex" source="./media/WebView2/what-webview.png" alt-text="What is WebView?" lightbox="./media/WebView2/what-webview.png":::
   What is WebView?
:::image-end:::


<!-- ====================================================================== -->
## Hybrid app approach

Developers must often decide between building a web app or a native app.  This decision hinges on the tradeoff between reach and power.
*  Web apps allow for a broad reach.  As a Web developer, you can reuse most of your code across different platforms.
*  To access all the capabilities of a native platform, use a native app.

:::image type="complex" source="./media/WebView2/web-native.png" alt-text="Web native" lightbox="./media/WebView2/web-native.png":::
   Web native
:::image-end:::

Hybrid apps allow developers to enjoy the best of both worlds: the ubiquity and strength of the web platform, combined with the power and full capabilities of the native platform.


<!-- ====================================================================== -->
## WebView2 benefits

<!--
In the below table, keep two trailing spaces after each image line and after each heading line, to keep card elements tight but not concatenated.
Similar table: [Overview of Progressive Web Apps (PWAs)](..\progressive-web-apps-chromium\index.md#characteristics-of-a-pwa)
-->

:::row:::
    :::column:::
        :::image type="icon" source="./media/webview-reasons-web-ecosystem-skillset-small.msft.png":::  
        **Web ecosystem & skillset**  
        Utilize the entire web platform, libraries, tooling, and talent that exists within the web ecosystem.
    :::column-end:::
    :::column:::
        :::image type="icon" source="./media/webview-reasons-rapid-innovation-small.msft.png":::  
        **Rapid innovation**  
        Web development allows for faster deployment and iteration.
    :::column-end:::
    :::column:::
        :::image type="icon" source="./media/webview-reasons-windows-7-8-10-support-small.msft.png":::  
        **Windows 7, 8, and 10 support**  
        Support for a consistent user experience across Windows 7, Windows 8, and Windows 10.
    :::column-end:::
:::row-end:::
:::row:::
    :::column:::
        :::image type="icon" source="./media/webview-reasons-native-capabilities-small.msft.png":::  
        **Native capabilities**  
        Access the full set of Native APIs.
    :::column-end:::
    :::column:::
        :::image type="icon" source="./media/webview-reasons-code-sharing-small.msft.png":::  
        **Code-sharing**  
        Add web code to your codebase allows for increased reuse across multiple platforms.
    :::column-end:::
    :::column:::
        :::image type="icon" source="./media/webview-reasons-microsoft-support-small.msft.png":::  
        **Microsoft support**  
        Microsoft provides support and adds new feature requests when WebView2 releases at Generally Availability (GA).
    :::column-end:::
:::row-end:::
:::row:::
    :::column:::
        :::image type="icon" source="./media/webview-reasons-evergreen-small.msft.png":::  
        **Evergreen distribution**  
        Rely on an up-to-date version of Chromium with regular platform updates and security patches.
    :::column-end:::
    :::column:::
        :::image type="icon" source="./media/webview-reasons-fixed-small.msft.png":::  
        **Fixed Version distribution**  
        Optionally package a specific version of the Chromium bits in your app.
    :::column-end:::
    :::column:::
        :::image type="icon" source="./media/webview-reasons-incremental-adoption-small.msft.png":::  
        **Incremental adoption**  
        Add web components piece-by-piece to your app.
    :::column-end:::
:::row-end:::

<!-- In the above table, keep two trailing spaces after each image line and after each heading line, to keep card elements tight but not concatenated. -->


<!-- ====================================================================== -->
## Get started

To build and test your app using the WebView2 control, you need to have <!--both [Microsoft Edge][MicrosoftedgeinsiderDownload] and -->the [WebView2 SDK][NugetPackagesMicrosoftWebWebView2] installed.  Select one of the following options to get started.

*   [Get started with WebView2 in Win32 apps][Webview2GetStartedWin32]
*   [Get started with WebView2 in WPF apps][Webview2GetStartedWpf]
*   [Get started with WebView2 in WinForms apps][Webview2GetStartedWinforms]
*   [Get started with WebView2 in WinUI 2 apps (Preview)][Webview2GetStartedWinui2]
*   [Get started with WebView2 in WinUI 3 apps (Preview)][Webview2GetStartedWinui]

The [WebView2 Samples][GithubMicrosoftedgeWebview2samples] repository contains samples that demonstrate all of the WebView2 SDK features and API usage patterns.  As more features are added to the WebView2 SDK, the sample apps will be updated.


<!-- ====================================================================== -->
## Supported platforms

A General Availability (GA) or Preview version of WebView2 is available for the following programming environments.

*   Win32 C/C++ (GA)
*   .NET Framework 4.5 or later
*   .NET Core 3.1 or later
*   .NET 5
*   .NET 6 (Preview)
*   [WinUI 3.0][UwpToolkitsWinui3]

WebView2 apps can run on the following versions of Windows.

*   Windows 10
*   Windows 10 IoT Enterprise LTSC x32 2019
*   Windows 10 IoT Enterprise LTSC x64 2019
*   Windows 10 IoT Enterprise 21h1 x64
*   Windows 8.1
*   Windows 7 \*\*
*   Windows Server 2019
*   Windows Server 2016
*   Windows Server 2012
*   Windows Server 2012 R2
*   Windows Server 2008 R2 \*\*

> [!IMPORTANT]
> \*\* WebView2 support for Windows 7 and Windows Server 2008 R2 has the same support cycle as Microsoft Edge.  For more information, navigate to [Microsoft Edge supported Operating Systems][DeployedgeMicrosoftEdgeSupportedOS].


<!-- ====================================================================== -->
## See also

*  [Understand WebView2 SDK versions][Webview2ConceptsVersioning]
*  [Distribute a WebView2 app and the WebView2 Runtime][Webview2ConceptsDistribution]
*  [Best practices for developing secure WebView2 apps][Webview2ConceptsSecurity]
*  [Manage User Data Folder in WebView2 apps][Webview2ConceptsUserDataFolder]
*  [How to Debug with WebView2][Webview2HowToDebug]
*  [Automating and testing WebView2 with Microsoft Edge Driver][Webview2HowToWebdriver]


<!-- ====================================================================== -->
<!-- links -->
[Webview2ConceptsDistribution]: ./concepts/distribution.md "Distribute a WebView2 app and the WebView2 Runtime | Microsoft Docs"
[Webview2ConceptsSecurity]: ./concepts/security.md "Best practices for developing secure WebView2 apps | Microsoft Docs"
[Webview2ConceptsUserDataFolder]: ./concepts/user-data-folder.md "Manage the user data folder | Microsoft Docs"
[Webview2ConceptsVersioning]: ./concepts/versioning.md "Understand WebView2 SDK versions | Microsoft Docs"

[Webview2GetStartedWin32]: ./get-started/win32.md "Get started with WebView2 in Win32 apps | Microsoft Docs"
[Webview2GetStartedWinforms]: ./get-started/winforms.md "Get started with WebView2 in WinForms apps | Microsoft Docs"
[Webview2GetStartedWinui2]: ./get-started/winui2.md "Get started with WebView2 in WinUI 2 apps | Microsoft Docs"
[Webview2GetStartedWinui]: ./get-started/winui.md "Get started with WebView2 in WinUI 3 apps (Preview) | Microsoft Docs"
[Webview2GetStartedWpf]: ./get-started/wpf.md "Get started with WebView2 in WPF apps | Microsoft Docs"

[Webview2HowToDebug]: ./how-to/debug.md "Get started debugging WebView2 apps | Microsoft Docs"
[Webview2HowToWebdriver]: ./how-to/webdriver.md "Automating and testing WebView2 with Microsoft Edge Driver | Microsoft Docs"
[Webview2ReleaseNotes]: ./release-notes.md "Release notes for WebView2 SDK | Microsoft Docs"
<!-- external links -->
[UwpToolkitsWinui3]: /uwp/toolkits/winui3/index "Windows UI Library 3 Preview 2 (July 2020) | Microsoft Docs"
[DeployedgeMicrosoftEdgeSupportedOS]: /deployedge/microsoft-edge-supported-operating-systems "Microsoft Edge supported Operating Systems | Microsoft Docs"

[GithubMicrosoftedgeWebview2samples]: https://github.com/MicrosoftEdge/WebView2Samples "WebView2 Samples - MicrosoftEdge/WebView2Samples | GitHub"
[GithubMicrosoftedgeWebviewfeddback]: https://github.com/MicrosoftEdge/WebViewFeedback "WebView Feedback - MicrosoftEdge/WebViewFeedback | GitHub"

[MicrosoftedgeinsiderMain]: https://www.microsoftedgeinsider.com "Microsoft Edge Insider"

[NugetPackagesMicrosoftWebWebView2]: https://www.nuget.org/packages/Microsoft.Web.WebView2 "Microsoft.Web.WebView2 | NuGet Gallery"
