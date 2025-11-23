---
description: Customize the look and feel of the widget to match the design of your website
---

# 2️⃣ Select Widget Design Variants

BlockBot Widget comes in three variants - `large`, `compact`, and `qrcode`. Variants provide a way to optimize the presentational style of the Widget for the space available in your application.

#### Variants

{% hint style="info" %}
You can select the themes you prefer to use. Simply do this:&#x20;

`theme=light`  for light-themed widget

`theme=dark`for dark-themed widget
{% endhint %}

1. `large` variant

```html
<iframe src="https://developerblockbotwidgetv1.vercel.app/?type=large&theme=light" style="height: 600px; width: 500px; border-radius: 20px; box-shadow: 0px 0px 15px 1px #00000021;" frameborder="0"></iframe>
```

You will notice the type is set to `large`. Also, the Iframe `width` = `600px` & `height` = `500px`. This ensures the widget component fits within the Iframe, but you can customize it to your preference. This variant is the maximum widget size, and it can be fully expanded to fit the size of a page.

***

2. `compact` variant

```html
<iframe src="https://developerblockbotwidgetv1.vercel.app/?type=compact&theme=light" style="width: 300px; height: 300px; border-radius: 20px; box-shadow: 0px 0px 15px 1px #00000021;" frameborder="0"></iframe>
```

You will notice the type is set to `compact`. Also, the Iframe `width` = `300px` & `height` = `300px`. This ensures the widget component fits within the Iframe and has a clean look, but you can customize it to your preference. This variant is a mini widget, and it can be used when there's not much space on your website.

***

3. `qrcode` variant

```html
<iframe src="https://developerblockbotwidgetv1.vercel.app/?type=qrcode&theme=light" style="width: 400px; height: 400px; border-radius: 20px; box-shadow: 0px 0px 15px 1px #00000021;" frameborder="0"></iframe>
```

You will notice the type is set to `qrcode`. Also, the Iframe `width` = `400px` & `height` = `400px`. This displays the QR code within the Iframe and a little padding for the container background, but you can customize the `width` and `height` to your preference (e.g., 300px \* 300px). This variant only displays a QR code whose URL link redirects to BlockBot WhatsApp bot.

***

{% hint style="info" %}
Remember, you can easily resize all the widgets to suit your style! Have fun customizing!
{% endhint %}
