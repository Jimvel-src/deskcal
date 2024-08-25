# DeskCal
 Repo of my latest project, a digital planner, which is modular. It runs in the browser. It might require some additional modifications

Feel free to leave suggestions...


## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)
The main page

## Installation
* Start off by cloning the repo

```bash
  git clone https://github.com/jimvel-src/deskcal
```
    
>  If you're planning on running this on a Pi, then 
> * Get a copy of "Full Page OS" (Not mine)
> * Flash it onto a SD card
> * The Pi must be atleast a Raspberry Pi 2 or above ( Non-Main cards like the Pi2w or others may not have proper support)  
> * Next, you may have to serve the file locally on a server or sometimes, you can use the file locally, without putting it onto a server...

Or, you can just run the Index.html and just about turn any device with a display into a Digital planner, although having a touch screen is helpful


> If you want to use it as planner with tasks and events, you can just go into the Index.html and in the area, just replace the
> ```html
>   <iframe src="https://calendar.google.com/calendar/embed" aria-required="<==  put your email after the embed to use your own calander" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>
> ```
>with
> ```
> https://calendar.google.com/calendar/embed?src=<mail>%40<mail-site>.com&ctz=<continent>%2F<Location, ig, idk>
> ```
> and now you have access to your own tasks and events, which you can add in the Google Calander app or website on another device (Or if you want, you can just oven it on the Pi, dont forget remove Kiosk mode tho...)