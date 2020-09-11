# Youtube Unliker

# Unliker

- Access the liked videos playlist
- in the address tab add the following to the URL “&advanced_settings=1&disable_polymer=1”
- Press **F12**
- Insert the code below in your console

```javascript
var items = $('body').getElementsByClassName("pl-video-edit-remove-liked-video"); 
for(var i = 0; i < items.length; i++){
    items[i].click();
}
```

## References

- https://neseef.com/2019/04/07/youtube-how-to-delete-all-liked-videos-at-once-from-playlist/
