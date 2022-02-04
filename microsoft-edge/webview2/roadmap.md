---
description: Learn about what's coming next for WebView2
title: Roadmap for Microsoft Edge WebView 2
author: MSEdgeTeam
ms.author: msedgedevrel
ms.date: 01/07/2021
ms.topic: conceptual
ms.prod: microsoft-edge
ms.technology: webview
keywords: IWebView2, IWebView2WebView, webview2, webview, win32 apps, win32, edge, ICoreWebView2, ICoreWebView2Host, browser control, edge html
---
# Microsoft Edge WebView2 roadmap  

> [!NOTE]
> Last Updated:  July 2021  

The WebView2 control allows developers to embed web technologies in their native applications.  The following page outlines the prospective roadmap for WebView2.  

> [!NOTE]
> WebView2 is under active development and the roadmap continues to evolve based on market changes and customer feedback, so please note that the plans outlined here are not exhaustive and are subject to change.  

If you have concerns or questions about the Roadmap, provide your feedback in the [feedback repo][GithubMicrosoftedgeWebviewfeedbackMain].  

The WebView2 team is planning the following major efforts for future updates.  

* UWP Preview
* MacOS Preview
* Xbox Preview
* HoloLens Preview

## WebView2 Runtime and Installer  

[Evergreen distribution model][ConceptDistributionEvergreenModel] allows you to target or chain install the WebView2 Runtime onto your user's machine.  The Evergreen WebView2 Runtime and installer has reached General Availability \(GA\).  

## Fixed version  

[Fixed version distribution model][ConceptsDistributionFixedVersionModel] allows you to package the Microsoft Edge binaries inside your native application.  The Fixed Version has reached General Availability \(GA\).  

## General availability  

### Win32 C/C++  

The Win32 C/C++ SDK has reached GA.  

### .NET  

The .NET SDK has reached GA. 

### Windows UI Library 3

You can access WebView2 controls in your applications using [Windows UI Library 3 (WinUI3)][UwpToolkitsWinui3Index] with the Windows App SDK. This is currently in preview. For more information, navigate to the [Windows App SDK roadmap][WindowsAppSDKRoadmap].

 
<!-- links -->  

[WindowsAppSDKRoadmap]: https://github.com/microsoft/WindowsAppSDK/blob/main/docs/roadmap.md "Roadmap"
[ConceptDistributionEvergreenModel]: ./concepts/distribution.md#evergreen-distribution-mode "Evergreen distribution model - Distribution of applications using WebView2 | Microsoft Docs"  
[ConceptsDistributionFixedVersionModel]: ./concepts/distribution.md#fixed-version-distribution-mode "Fixed version distribution model - Distribution of applications using WebView2 | Microsoft Docs"  

[UwpToolkitsWinui3Index]: /uwp/toolkits/winui3/index "Windows UI Library 3.0 Preview 1 (May 2020) | Microsoft Docs"  

[GithubMicrosoftedgeWebviewfeedbackMain]: https://github.com/MicrosoftEdge/WebViewFeedback "WebView Feedback - MicrosoftEdge/WebViewFeedback | GitHub"  

[GithubMicrosoftUiXamlRoadmap]: https://github.com/microsoft/microsoft-ui-xaml/blob/master/docs/roadmap.md "Windows UI Library Roadmap - microsoft/microsoft-ui-xaml | GitHub"  
