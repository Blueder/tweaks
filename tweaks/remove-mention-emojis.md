# remove-mention-emojis
**last tested/working:** Sep 6, 2021 </br>
**Author(s):** [@Blueder](https://github.com/Blueder)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/pdVPAW1.png"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/ZTFoR75.png"></td>
 </tr>
</table>

## CSS
```css
*remove emojis in mentions*/
.notion-page-mention-token span:nth-child(2) {
  display: none !important;
}
/* Remove left over page icons which didn't disappear from previous tweak */
img.notion-emoji .page{
  display: none !important;
}
```
