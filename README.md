# KNXGSCSS

KNXGSCSS is a custom CSS framework used for static resources on knxggles.xyz. The framework focuses predominanently on bold typographical elements and high-contrast muted colour palettes.

##### Author and License
Licensed under the [Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt) license.
Developed by Callum Booth ({me} at {knxggles.xyz}) (@knxggles)

## Colours
The framework defines a restricted yet varied palette of mostly muted colours.

### Text Colours
The following text colours are available by adding the `.<name>-text` class to the container element.

 - Dark - #212121
 - Light - #FEFEFE

### Background Colours
The following backgound colours are available by adding the `.<name>-background` class to the container element.

 - White - #FEFEFE
 - Grey - #212121
 - Teal - #142625
 - Blue - #141D26

### Accent Colours
The following accent colours are available by adding either the `.<name>-accent-text` class or the `.<name>-accent-background` class to the container element, and adding the `.accent` class to the relevant element.

- Red - #f16464
- Orange - #f1aa64
- Yellow - #f1d064
- Lime - #c2f164
- Green - #66f164
- Teal - #64f1aa
- Cyan - #64f1de
- Blue - #6493f1
- Violet - #9364f1
- Magenta - #d264f1
- Pink - #f164d9

### Alert Colours
The following alert colours are available by adding either the `.<name>-alert-text` class or the `.<name>-alert-background` class to the container element.

- Failure - #E53018
- Warning - #E5B218
- Success - #22E518
- Info - #18BCE5

### Themes
The framework also defines the following themes, available by adding the `.<theme-name>` class to the document `<body>`.

 - Paper - Grey text on light background with blue accent.
 - Knxg - Default theme; White text on blue background with yellow accent.

## Typography
The framework uses the `Oswald` font face from Google Fonts, with a fall-back onto Bootstrap's native system font stack should the default not be loadable.

### Typographical styles
|Element|Size   |Weight|
|-------|-------|------|
|h1     |9vh    |600   |
|h2     |4vh    |400   |
|h3     |3vh    |400   |
|h4     |2vh    |400   |
|h5     |2vh    |200   |
|h6     |2vh    |200   |
|p      |1vh    |200   |
|small  |0.44em |200   |

### Transforms

- `.upper` - Transform all text to uppercase
- `.header` - Transform any `<small>` tag content into lower case within the container.

## Layout
Defines a single centered column layout

|Class  |Width|Gutter|
|-------|-----|------|
|`.w100`|100% |0%    |
|`.w90` |90%  |5%    |
|`.w80` |80%  |10%   |
|`.w70` |70%  |15%   |
|`.w60` |60%  |20%   |
|`.w50` |50%  |25%   |

