+++
title = "Test Automation with .NET Core 6, RestSharp 1.07+ and NUnit"
description = "Exploring .NET Core 6 with REST API Test Automation..."
author = "Chris Ryan"
date = ""
tags = [".NET Core 6", "REST API", "testing"]
categories = ["Testing",".NET"]
[[images]]
  src = "img/dotnet6.png"
  alt = "Test Automation with .NET Core 6"
  stretch = "horizontal"
+++

**Test Automation with .NET Core 6**, time to investigate .NET Core 6 and RESTSharp 1.07+ for Test Automation.  NET CORE 6 is now stable and production ready, so I felt it was time to jump in and implement some test automation with it...
<!--more-->

I've implemented a couple of basic smoke tests using https://api.zippopotam.us/ for some UK Postcode lookup and typicode.com for a POST test.

I'm using RestSharp, which since version 1.07 had undergone a major upgrade, which contains quite a few breaking changes. I'm using 1.08 here and System.Text.Json.Serialization in place of Newtonsoft for some JSON framework speed improvement.

I've added a couple of performance tests using System.Diagnostics.Stopwatch with a very generous test assertion that REST requests will complete in under 1000 milliseconds. 

### The Code

Check my code here on GitHub.

[GitHub chrisrryan/autotest_dotnet6](https://github.com/chrisrryan/autotest_dotnet6)

### Demo

{{< youtube l8yG1b66wiU >}}

_Article by Chris Ryan_
