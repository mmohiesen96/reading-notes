# Local storage :
- History of local storage : we can implement local storage a long time ago using xml files and other formats the concept local storage represents
cookies which was invented early in web applications.

- Cons of Cookies :
    - They are included in every HTTP request that will slow your web application by transmitting information needlessly, and transmits data unencrypted through the web unless it is using SSL .
    - They are limited 4 kb which is enough to slow down the application .


- First the cookies was limited to IE by Microsoft which was limited to 64 kb then to 640 kb .
- Then adobe invented the flash cookies which allowed to save 100 kb by domain .
- Alot of technologies came in after that like AMASS java script built storage and Gears by Google .

## HTML5 Storage :
- This means that there is a local storage unlike cookies saves the data (key,value) for example , and stores them on the browser and can't be transmitted on the web .

- Using HTML5 Storage for example this code can implement storage and stores it :
    -   interface Storage {
        getter any getItem(in DOMString key);
        setter creator void setItem(in DOMString key, in any data);
        };
    - also we hav functions to remove saved data like : removeItem() .

- Tracking HTML storage : event listeners are used to track and handle storage using the storage and on storage events ex .

    - if (window.addEventListener) {
        window.addEventListener("storage", handle_storage, false);
        } else {
        window.attachEvent("onstorage", handle_storage);
        };

- Storage in HTML can hold up to 5 mb and if excceded it will through quota_exceeded_err .


- Google introduced gears which is a database like buil with sqlite language alike .