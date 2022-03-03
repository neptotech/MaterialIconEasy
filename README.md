# MaterialIconEasy
just one import line for all material icon(filled, outline, rounded, sharp, two tone)

-----

### Method 1
- put the css file from here to the folder where your html exists
- in html add `<link rel="stylesheet" type="text/css" href="MaterialIconEasy.css">` ,
- now any code like below will work
```
<span class="material-icons-outlined">
home
</span>
<span class="material-icons">
home
</span>
<span class="material-icons-round">
home
</span>
<span class="material-icons-sharp">
home
</span>
<span class="material-icons-two-tone">
home
</span>
```
### Method 2
- copy the css file(hover the below code) from here to your main css file(linked to html)
```

/* fallback */
@font-face {
  font-family: 'Material Icons';
  font-style: normal;
  font-weight: 400;
  src: url(https://fonts.gstatic.com/s/materialicons/v125/flUhRq6tzZclQEJ-Vdg-IuiaDsNc.woff2) format('woff2');
}

.material-icons {
  font-family: 'Material Icons'!important;
  font-weight: normal;
  font-style: normal;
  font-size: 24px;
  line-height: 1;
  letter-spacing: normal;
  text-transform: none;
  display: inline-block;
  white-space: nowrap;
  word-wrap: normal;
  direction: ltr;
  -webkit-font-feature-settings: 'liga';
  -webkit-font-smoothing: antialiased;
}
/* fallback */
@font-face {
  font-family: 'Material Icons Round';
  font-style: normal;
  font-weight: 400;
  src: url(https://fonts.gstatic.com/s/materialiconsround/v99/LDItaoyNOAY6Uewc665JcIzCKsKc_M9flwmP.woff2) format('woff2');
}

.material-icons-round {
  font-family: 'Material Icons Round' !important;
  font-weight: normal;
  font-style: normal;
  font-size: 24px;
  line-height: 1;
  letter-spacing: normal;
  text-transform: none;
  display: inline-block;
  white-space: nowrap;
  word-wrap: normal;
  direction: ltr;
  -webkit-font-feature-settings: 'liga';
  -webkit-font-smoothing: antialiased;
}
/* fallback */
@font-face {
  font-family: 'Material Icons Sharp';
  font-style: normal;
  font-weight: 400;
  src: url(https://fonts.gstatic.com/s/materialiconssharp/v100/oPWQ_lt5nv4pWNJpghLP75WiFR4kLh3kvmvR.woff2) format('woff2');
}

.material-icons-sharp {
  font-family: 'Material Icons Sharp' !important;
  font-weight: normal;
  font-style: normal;
  font-size: 24px;
  line-height: 1;
  letter-spacing: normal;
  text-transform: none;
  display: inline-block;
  white-space: nowrap;
  word-wrap: normal;
  direction: ltr;
  -webkit-font-feature-settings: 'liga';
  -webkit-font-smoothing: antialiased;
}
/* fallback */
@font-face {
  font-family: 'Material Icons Two Tone';
  font-style: normal;
  font-weight: 400;
  src: url(https://fonts.gstatic.com/s/materialiconstwotone/v103/hESh6WRmNCxEqUmNyh3JDeGxjVVyMg4tHGctNCu0.woff2) format('woff2');
}

.material-icons-two-tone {
  font-family: 'Material Icons Two Tone' !important;
  font-weight: normal;
  font-style: normal;
  font-size: 24px;
  line-height: 1;
  letter-spacing: normal;
  text-transform: none;
  display: inline-block;
  white-space: nowrap;
  word-wrap: normal;
  direction: ltr;
  -webkit-font-feature-settings: 'liga';
  -webkit-font-smoothing: antialiased;
}
/* fallback */
@font-face {
  font-family: 'Material Icons Outlined';
  font-style: normal;
  font-weight: 400;
  src: url(https://fonts.gstatic.com/s/materialiconsoutlined/v100/gok-H7zzDkdnRel8-DQ6KAXJ69wP1tGnf4ZGhUce.woff2) format('woff2');
}

.material-icons-outlined {
  font-family: 'Material Icons Outlined';
  font-weight: normal;
  font-style: normal;
  font-size: 24px;
  line-height: 1;
  letter-spacing: normal;
  text-transform: none;
  display: inline-block;
  white-space: nowrap;
  word-wrap: normal;
  direction: ltr;
  -webkit-font-feature-settings: 'liga';
  -webkit-font-smoothing: antialiased;
}
```
- now again material icon codes will work
