---
layout: post
title: Driver Navigation module begins
comments: True
---

Driver navigation module is one of the most important modules that's required in the GEAR Systems project, building a modular structure for this tool which would be solely dependant on an API system request was the best way to do this. Keeping this module standalone was one of the most important decisions so as to avoid a cluttered cumbersome repository of data.

The UI/UX and the API details have been added to the required application and it has the following functionality and views.
```
1. A simulation of a logged in page where a driver / person incharge to resolve the problem is shown.
2. Showing the details of all the issues assigned to the person as tabs.(Resolved)(Unresolved)(Administrative)
3. A data API request sample which categorizes the issues accordingly and gives the route to the final issue location.
4. Route procedure through waypoints in between and the other navigation details in real time
```

![UI]({{site.url|append:site.baseurl}}/public/img/issues.png)
```
Requirements yet to be implemented
1. Voice over functionality for reading the navigation instructions to the final location in real time
2. Login functionality
3. Direct route GET request procedures
```

![UI]({{site.url|append:site.baseurl}}/public/img/drivernavigation.png)

Looks like it's been good progress forward, There's more to look forward to.