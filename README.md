# Flow
A custom theme for the [Homer Dashboard](https://github.com/bastienwirtz/homer) designed to increase layout flexability.

Light Mode Preview
![Light Mode Preview](/previews/light-wide-column.png)

Dark Mode Preview
![Light Mode Preview](/previews/dark-wide-column.png)

[More preview images here.](previews)


## Included Customizations
General
- Added additional variables in the [config.yml](assets/config.yml) to provide easy accessability to modify the theme from the yml.
  - Also includes corisponding default variable values in [flow.css](assets/flow.css)
- Custom background image(s)
- Custom font
- Radiuses everywere
- Background tinting (usefull for darkening or brightening background images for dark/light modes)
- Dark/light mode transitions
- Placed header title above header subtitle
- Made searchbox maintain customized color when active
- Re-formatted navbar layout to use less virtical space in mobile view
- Allowed wrapping of navbar links when many links are present
- Dynamic number of columns based on available screen width

Groups and Cards
- Hover annd press animations for cards and links
- Added Spacing between cards and groups
- Allow linewrapping and newlines in card sub-title (up to 3 lines)
- Allow compressed icon-only cards in column view
- Added "tooltip" on icon-only cards show when hovered or pressed on the card
- Added outline to cards in row view
- Allowed creating extra space between cards in column view (can be used to add sepparation between card sub-groups within a group in column view)
- Added backgrounds to groups in column view
- Added background to groups title in row view


## Customizations:
Most customizations are done via the light and dark variables under "colors" just like you would for Homer normally. There are additional variables provided with this theme for customizing the theme without needing to dive into the css. The extra variables should be self explanitory via thier names.

