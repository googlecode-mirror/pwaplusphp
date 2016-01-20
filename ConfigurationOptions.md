# Settings / Options #

| **Name** | **Description** |
|:---------|:----------------|
|Picasaweb User|Enter your Picasaweb username. This is the username you use to login to view your albums.|
|GData Token|This token was generated during Step 1 and it allows PWA+PHP to access and display your private (unlisted) Picasa albums. The value cannot be changed.|
|Site Language|Select the language you wish to use. More may be available on the PWA+PHP download page|
|Images Per Page|Set the number of thumbnails to display per page. Value of 0 means don't paginate.|
|Image Size|Set the display size for full images. These values are supported by the Picasaweb API.|
|Album Thumbnail Size|Sets the album thumbnail size. May need to alter overlay CSS if value < 160. These values are supported by the Picasaweb API.|
|Photo Thumbnail Size|Set the thumbnail size. These values are supported by the Picasaweb API.|
|Album Details|Setting this to TRUE will overlay the album details on the gallery thumbnails when the user hovers the mouse over the image.|
|Truncate Album Names|Album names are truncated by default on the gallery page to ensure the div-based layout displays properly -- long album titles that don't fit beneath the thumbnail can break the fluid, div-based layout. Set this to FALSE to show the full album name.|
|Description Length|Trim display length of description to specific number of characters to ensure the on-hover description overlaid on the album fits in the available space over the thumbnail|
|Show Photo Caption|This option allows you to specify whether or not captions are displayed under photos. Options are always, never, or only when the user hovers over the space below the thumbnail. Click the caption to save the image if PERMIT\_IMG\_DOWNLOAD is set to TRUE. Captions work best with largr thumbnail sizes.|
|Caption Length|Trim display length of captions to specific number of characters to ensure the caption fits beneath the photo thumbnail|
|Require Filter|Set this to FALSE unless you want to **require** a search filter in the URL -- you can still filter albums with this set to FALSE. Setting to TRUE **requires** a filter string in the URL to prevent certain users from seeing certain albums.|
|Public Albums Only|This option allows you to specify whether to display only public or both public and private albums of the user specified above.|
|Show Drop Box|The Drop Box is a special Picasa album that stores images uploaded by email. Setting this variable to TRUE forces diplay of the drop box on all pages, even when a filter is specified.|
|Permit Image Download|This option determines whether the user can download the original full-size image by clicking on the caption under the photo. Set to TRUE to enable and FALSE to disable.|
|Show Footer Message|Setting this to true allows PWA+PHP to display a 'generated by' message at the bottom of the page, so other users can learn about it.|