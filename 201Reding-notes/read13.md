
# The Past, Present & Future of Local Storage for Web Applications


persistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions. 


---


- Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over



- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)



- Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful 



## A Brief History of Local Storage Hacks Before HTML5



In the beginning, there was only Internet Explorer. Or at least, that’s what Microsoft wanted the world to think. To that end, as part of the First Great Browser Wars, Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars, Internet Explorer. One of these things was called DHTML Behaviors, and one of these behaviors was called userData. 



```

function supports_html5_storage() {

  try {

    return 'localStorage' in window && window['localStorage'] !== null;

  } catch (e) {

    return false;

  }

}

```




| Property       | Type         | Description  |

| :------------- | :----------: | -----------: |

|key | string    | he named key that was added, removed, or modified |

|oldValue   |any | the previous value (now overwritten), or null if a new item was added  |



  [go to this link](http://diveinto.html5doctor.com/storage.html)