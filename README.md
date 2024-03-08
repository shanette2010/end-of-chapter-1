# end-of-chapter-1

Reading the end of chapter 1 Eloquent JavaScript. It was basically talking about Empty Values and Automatci type conversations.
Empty Vaules can either be Null or Undefind. Normally used to denote the absense of a meaninful vaule.

### EMPTY VAULES AND AUTOMATIC TYPE CONVERSATIONS
When an operator is applied to the wrong type of value. Javascript will correct the vaule to the type it needs to be!
The Null in the expression will be come a 0. And the number in the 2nd expression will become a sting. 
But once you add a 3rd expression plus a sting concatenation (addition) it will convert to a 1. (from numbers to sting)

Also once something dosent map to a number such as "5" or undefind the vaule becomes NaN.
When the null or undefined occures on either side of the operator, it produces ture only.
If both side are one of null or undefinded.

## Examples
  1. console.log(8*null)
     // 0
  2. console.log(5-1)
     // 4
  3. console.log(null == undefind);
     // ture
  4. console.log(null == 0);
     // false
