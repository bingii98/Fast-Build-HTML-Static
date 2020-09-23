# Fast Build HTML Static
**Manage your task when build html static or something same**\
*This source used bootstrap, so remove if don;t use it.*\
### First run Node install package needed:
> npm i

***Structure folder***
>**Folder**\
>__assets\
>____css\
>____js\
>____images\
>____sass\
>________assets\
>____________bootstrap4.scss\
>____________font-awesome.scss\
>________theme\
>____________theme.scss\
>________theme.scss\
>__gulpconfig.json\
>__gulpfile.js\
>__package.json\
\
*Create your **SCSS** file and **Import** it in theme.scss file*\
*Ex: @import "theme/theme";*\
\
***Manage your task in gulpfile.js***\
All your task has config in this file. \
Please watch and short learn gulp task.\
If you only want run for your work so forward after code.\
**Code for only complite all**\
> gulp watch\
\

**Code for complite from scss to css and syns browser**\
> gulp watch-bs\
\
\

**Code for complite from scss to css and syns browser**\
> gulp sass\
\

**Wacth task name and funtion in gulpfile.js**\
