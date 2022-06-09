# Nullified ALT text
There are situations where ALT text for images must be provided to satisfy SEO requirements, yet rendered hidden for screen reader and other assistive technology users. In this situations applying the `aria-hidden` attribute can nullified the image and remove it from the accessibiltiy tree.

### Expected behaviour
Image with ALT text is rendered hidden

### Screen reader compatibility
|   | JAWS <sup>v2021</sup> | NVDA <sup>v2020</sup>  |VoiceOver   |Talkback   | Narrator <sup>Win 10</sup> |
|---|:-:|:-:|:-:|:-:|:-:|
| Edge <sup>v100</sup>  | :white_circle:  |:white_circle:  | :white_circle:  | :white_circle:  |:white_circle: |
| Chrome <sup>v100</sup>  |:white_circle:   |:white_circle:   |:white_circle:   | :white_circle:  |  :white_circle: |
| FireFox <sup>v99</sup>  | 	:white_circle: |:white_circle: | :white_circle:  | :white_circle:  | :white_circle:  |
| iPhone 13 <sup>v15.3.1</sup> | :white_circle:  | :white_circle:  | :white_circle: | :white_circle:  |  :white_circle: |
| Galaxy* Tab A7 <sup>Android v11</sup> | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:   | :white_circle:  |
| MacOS** <sup>Monterey v12.2.1</sup>  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  |

