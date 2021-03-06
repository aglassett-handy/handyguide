---
description: Banners display important messages.
---

# Banners

## Usage of Banners

Banners are used to confirm an action taken or reflect a status.  Banners can be sticky or temporary banners and will share the same styling.

![](../.gitbook/assets/banner-overview.png)

## Anatomy of Banners \(banner\)

Banners use color and iconography to indicate the nature of the action or messaging.

![](../.gitbook/assets/banner-view.png)

![](../.gitbook/assets/banner.png)

**1. Label Icon**  
[**Font Awesome \(a-icon-line\)**](../brand-guidelines/line-icons.md#fontawesome-guidelines) is used for the label icon**.**

```text
font: font-awesome
font-size: 16px
font-weight: light
font-color: white or slate-dark

padding-left: 16px
padding-right: 8px

font-awesome codes:
[check-circle] - used for confirmations or positive actions
[exclamation-cirlce] - used for errors or negative actions
[calendar-times] - used when there is an issue with availability/bookings
[sync] - used when the app is reloading
```

**2. Text \(a-text-paragraph\)**

```text
font-weight: book
font-size: 16px
font-color: white or slate-dark
padding-left: 8px
padding-right: 16px
padding-top: 12px
padding-bottom: 12px
```

**3. Container**

```text
max-width: 100%

Confirmations: green-medium
Warnings: yellow-medium-dark
Errors: red-medium
Neutral: off-white
```

## Temporary Banner Animation

Temporary banners will slide under the header and slide back up. 

![](../.gitbook/assets/banner2.gif)

