# unfollow-all

## Unfollow All Pages which we have been following since stone ages
temporary i'm unfollowing all of my facebook pages which i've been following without unlike them.
so for this 
we have to go to here: (https://www.facebook.com/pages/?category=liked&ref=bookmarks)

then go to the end of the list of pages. 
open console. paste this code. done.
```javascript
function clickfollowedButton(){
const unfollowButton = document.querySelectorAll('div[aria-label="Following"]');
    for(let element of unfollowButton){
    if(element){
        element.click()
    }else{
         console.log("Unfollow button not found.");
    }
    }
}
clickfollowedButton()
```
