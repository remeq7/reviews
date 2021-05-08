# Description

List of photos with info and you can toggle them.

# Code

```javascript
// show next person
nextBtn.addEventListener("click", function () {
  currentItem++;
  if (currentItem > reviews.length - 1) {
    currentItem = 0;
  }
  showPerson(currentItem);
});
```

## View

![Alt text](img/screen.png "Title")
