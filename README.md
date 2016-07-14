# angular-template-cache
When using template-url to load angular directives, it will fire multiple XHR. Most browsers have limitation 
on concurrent XHR calls hence the performance is not good on first load with lots of directives.
