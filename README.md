# Omnis Studio and Heroicons

[Heroicons](https://github.com/tailwindlabs/heroicons), a popular set of free, MIT-licensed, high-quality icons designed specifically for user interfaces, have emerged as a valuable resource for modern software development. Created by the team at Tailwind Labs, Heroicons offer a comprehensive collection of clean and customizable SVG icons that are well-suited for a wide range of applications. With their minimalist aesthetic and consistent design principles, Heroicons provide developers with a versatile toolkit to enhance the visual appeal and usability of their applications.

You can now leverage this fantastic set of icons in your Omnis Studio application in three simple steps.

### Getting the icons

You can download Heroicons at version `2.0.18` inside an already simplified folder structure that works with Omnis Studio from [here](https://github.com/andreiaugustin/omnis-heroicons/archive/refs/heads/main.zip).


### Installing the icons

As per Omnis Studio's documentation, a folder containing the SVG icons needs to be placed inside the `iconsets` folder which is located in the read/write location: this location can differ between systems and installations, but you will usually find it in the `Application Support` folder on macOS and `AppData` on Windows.

After unzipping the icons, you will find three folders:

Folder Name | Contents
---|---
heroicons_20_solid | 292 SVG icons at 20x20 pixels with a filled appearance, ideal for smaller elements like buttons, form elements and to support text
heroicons_24_outline | 292 SVG icons at 24x24 pixels with an outlined appearance using a 1.5 pixels stroke, ideal for primary navigation and marketing sections 
heroicons_24_solid | 292 SVG icons at 24x24 pixels with a filled appearance, ideal for primary navigation and marketing sections

You can preview the icons on [Heroicons' website](https://heroicons.com/). Once you've chosen your preferred style, you can copy the respective folder into Omnis Studio's `iconsets` folder. You have the option to copy all three folders or select only the icons you need and create a new folder specifically for those icons!


### Using the icons

Once the icons are in Omnis Studio's `iconsets` folder, you need to set your library's `$iconsets` property to the name of the folder. For exmaple, if you are importing all three folders, the `$iconsets` should be set to `heroicons_20_solid,heroicons_24_outline,heroicons_24_solid`.

At this point, select your component and look for the `$iconid` property: here you can select an icon from our new Heroicons sets!