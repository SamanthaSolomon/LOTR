

# Lord of the Rings Map

![](https://imgur.com/IAGWicn.png)

A JQuery adventure through middle earth. Click the buttons from left to right to see the character's journey. Built as a homework assignment in week two of General Assembly bootcamp.

### Build Staus: Complete

## Code, Style & Framework

- jQuery
- JavaScript
- HTML DOM

```javascript
//CHAPTER FIVE//
const makeBuddies = () => {
   const $aside = $("<aside>")
   $aside.appendTo("#middle-earth")

  const $ul = $("<ul>")
  
  for (let index = 0; index < buddies.length; index++){
    $("<li>")
      .addClass("buddy")
      .text(buddies[index])
      .appendTo($ul)
  }

  $ul.appendTo($aside)
};
```

