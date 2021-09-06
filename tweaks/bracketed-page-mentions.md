# bracketed-page-mentions
**last tested/working:** Sep 6, 2021 </br>
**Author(s):** [@Blueder](https://github.com/Blueder)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/5XjRfnx.png"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/ZTFoR75.png"></td>
 </tr>
</table>

## CSS
```css
/*makes page mentions have brackets [[page_name]]*/
.notion-page-mention-token__title:before {
        content: "[[";
}
.notion-page-mention-token__title:after {
        content: "]]";
}
```
