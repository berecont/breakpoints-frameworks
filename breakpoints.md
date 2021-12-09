# Breakpoints in diversen Frameworks  
**to be continued ...**

## bulma  
[bulma.io](https://bulma.io/documentation/overview/responsiveness/#breakpoints)  
* `mobile`: up to `768px`  
* `tablet`: from `769px`  
* `desktop`: from `1024px`  
* `widescreen`: from `1216px`  
* `fullhd`: from `1408px`  

[responsive mixins](https://bulma.io/documentation/utilities/responsive-mixins/)  
* Mobile: Up to `768px`  
* Tablet: Between `769px` and `1023px`  
* Desktop: Between `1024px` and `1215px`  
* Widescreen: Between `1216px` and `1407px`  
* FullHD: `1408px` and above  

## contao-grid-bundle | euf_nutshell | Erdmann & Freunde  
[euf_nutshell - mixins - _responsive.scss](https://github.com/erdmannfreunde/euf_nutshell/blob/master/files/nutshell/scss/mixins/_responsive.scss)  
[contao-grid-bundle](https://github.com/erdmannfreunde/contao-grid-bundle)  
viewport|min|max|  
---|---|---  
xs|0|`549px`   
sm|`550px`|`767px`  
md|`768px`|`939px`  
lg|`940px`|`1099px`  
xl|`1100px`|none  
example:  
```
@import media-query(screen-lg){ ... }
```  
```
media-query(screen-lg) ... ab 'lg' sichtbar
media-query(screen-md-max) ... von 0 bis 'md' sichtbar
media-query(screen-md,screen-md-max) ... innerhalb 'md' sichtbar
```
## Bootstrap 4  
[Responsive breakpoints](https://getbootstrap.com/docs/4.0/layout/overview/#responsive-breakpoints)
viewport|min|max|mark  
---|---|---|---  
xs|0|`575px`|&lt;`576px`  
sm|`576px`|`767px`|&ge;`576px`  
md|`768px`|`991px`|&ge;`768px`  
lg|`992px`|`1199px`|&ge;`992px`  
xl|`1200px`|max container width `1140px`|&ge;`1200px`  

## Bootstrap 5  
[available breakpoints](https://getbootstrap.com/docs/5.0/layout/breakpoints/#available-breakpoints)
viewport|min|max|mark  
---|---|---|---  
xs|0|`575px`|&lt;`576px`  
sm|`576px`|`767px`|&ge;`576px`  
md|`768px`|`991px`|&ge;`768px`  
lg|`992px`|`1199px`|&ge;`992px`  
xl|`1200px`|`1399px`|&ge;`1200px`  
xxl|`1400px`||&ge;`1400px`  

