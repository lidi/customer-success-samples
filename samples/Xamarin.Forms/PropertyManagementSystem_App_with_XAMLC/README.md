##Property Management System App with XamlC

PMS_Forms_App was created to demonstrate how to create Property Management System User Interface using Xamarin.Forms 

In [App.cs] (./App.cs), it includes XamlC, and the app displays the page load times on the top of the page. When commenting out XamlC, the main pages takes about 150ms to load. When implementing XamlC, them main page load time decreases to appx 30ms.

`[assembly: XamlCompilation (XamlCompilationOptions.Compile)]`

On the main Grid Options screen, only the Rooms button is wired up to an action.

![Sample Gif] (./Screen\ Shots/SampleGif.gif)
