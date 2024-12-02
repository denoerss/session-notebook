Combining Media Features

#

You can combine multiple media features with and.

@media (min-width: 600px) and (orientation: landscape) {
/_ CSS rules that are only applied when the screen is at least 600px wide and in landscape orientation _/
}

Testing for multiple Media Features

#

You can use a comma-separated list to apply styles when the user's device matches any one of various media types using ,

@media (min-width: 600px), (orientation: portrait) {
/_ CSS rules that are only applied when the screen is either at least 680px high or in portrait orientation _/
}

.box--em {
background-color: lightslategrey;
font-size: 32px;
width: 5em;
height: 5em;
}
