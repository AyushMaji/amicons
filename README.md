
![Logo](https://github.com/AyushMaji/amicons/blob/main/assets/others/banner.png?raw=true)




<h1 align="left">Amicons - Free Flutter icons <a target="_blank" href="https://www.linkedin.com/in/ayushmaji/"></a><img src="https://raw.githubusercontent.com/AyushMaji/amicons/refs/heads/main/assets/amination/Hi.gif" width="30px"></h1></h1>

Amicons is a Flutter icons hub that brings together popular icon sets in one place, including `Iconly`, `Remix`, `Vuesax`, `Lucide`, `Flaticon`. With this package, there's no need to download multiple icon packages for a single project—simply install Amicons and gain access to all these icon sets effortlessly.


We also provide a [Figma Link](https://www.figma.com/design/Fuq1umo7X3kyFzSjJPEW3H/amicons?node-id=0-1&t=l8UzOsSvRiIKO40G-1) where you can preview and use the icons instantly.
<br/><br/>

## Features

- **Extensive Collection**: Access over 10000+ stroke icons for free, ready to use in your projects.
- **Scalable Icons**: Easily adjust the size of icons to fit your design perfectly.
- **Color Customization**: Apply any color to icons to match your brand or design theme.
- **Rotation and Animation**: Add a dynamic touch with rotation and animation options.
- No need to install multiple icon libraries. <br/>
<br/>

|<img src="https://raw.githubusercontent.com/AyushMaji/amicons/refs/heads/main/assets/others/b1.png"/>|<img src="https://raw.githubusercontent.com/AyushMaji/amicons/refs/heads/main/assets/others/b3.png"/>|
|---|---|

<br/>

## Platform Support

| Android | iOS | macOS | Web | Linux | Windows |
| :-----: | :-: | :---: | :-: | :---: | :-----: |
|   ✅    | ✅  |   ✅   | ✅  |  ✅    |   ✅    |

<br />

## Installation

To install and start using Hugeicons Flutter Icons in your project, follow the steps below:

```dart
dependencies:
  amicons: ^0.0.1
```

Then run:

```bash
$ flutter pub get
```

## Usage Examples

To use Amicons Flutter Icons in your project, import the package and call the desired icon using the `Icon` widget. You can customize the icon size, color, and other properties as needed.

```dart
import 'package:amicons/amicons.dart';

Icon(
  Amicons.flaticon_wifi_alt_rounded,
  color: Colors.red,
  size: 30.0,
),
```


## 1. AntDesign
AntDesign provides three types of icons: Fill, Outline, and TwoTone icons. To use Fill icons, simply append `_fill` as a suffix. For example, for a fill, you can use `Icon(AntDesign.gitlab_fill)`, while `Icon(AntDesign.sketch_outline)` and `Icon(environment_twotone)` are used for Outline and TwoTone, respectively.

![AntDesign](https://github.com/chouhan-rahul/icons_plus/assets/82075108/b079fa57-6130-499f-b441-d9a612b0e4aa)

```dart
  Icon(AntDesign.gitlab_fill),
  Icon(AntDesign.sketch_outline),
  Icon(AntDesign.environment_twotone),
```

## 2. Bootstrap
Bootstrap offers two types of icons: Outline and Fill icons. If you prefer using fill icons, simply add `_fill` as a suffix. For instance, if you want a filled heart, use `Icon(Bootstrap.heart_fill)`, whereas for an outlined heart, use `Icon(Bootstrap.heart)`.

![Bootstrap](https://github.com/chouhan-rahul/icons_plus/assets/82075108/70852984-2897-432a-a10d-ec50c7166c86)

```dart
  Icon(Bootstrap.google),
  Icon(Bootstrap.bootstrap),
  Icon(Bootstrap.github),
```

## 3. BoxIcons
BoxIcons provides three types of icons: Regular, Solid, and Logo icons. To use Regular icons, simply add `bx_` as a prefix. For example, for a regular, you can use `Icon(BoxIcons.bx_git_branch)`, while `Icon(bxs_cookie)` and `Icon(BoxIcons.bxl_apple)` are used for Solid and Logo, respectively.

![BoxIcons](https://github.com/chouhan-rahul/icons_plus/assets/82075108/db324cab-6663-4ab2-af48-9d3bc3e9a42a)

```dart
  Icon(BoxIcons.bxl_apple),
  Icon(BoxIcons.bx_git_branch),
  Icon(BoxIcons.bxs_cookie),
```

## 4. Brands
Here's an example showing how to use Brands Logo.

![Brands](https://github.com/chouhan-rahul/icons_plus/assets/82075108/c0bb0ed8-25c4-4035-82a9-db8ab71af12d)

```dart
  Brand(Brands.icons8),
  Brand(Brands.the_big_bang_theory),
  Brand(Brands.android_studio),
```

## 5. Clarity
Clarity provides three types of icons: Outline, Solid, and Line icons. To use Outline icons, simply append `_outline` as a suffix. `_solid` and `_line` are used for Solid and Line, respectively.

![Claity](https://github.com/chouhan-rahul/icons_plus/assets/82075108/3e3995de-0318-4a15-9390-6de4bad05601)

```dart
  Icon(Clarity.map_outline_badged),
  Icon(Clarity.application_solid),
  Icon(Clarity.camera_line),
```

## 6. EvaIcons
EvaIcons offers two types of icons: Outline and Fill icons. If you prefer using outline icons, simply add `_outline` as a suffix.

![EvaIcons](https://github.com/chouhan-rahul/icons_plus/assets/82075108/0540c185-e843-4429-9eb6-339894f3eed3)

```dart
  Icon(EvaIcons.clipboard),
  Icon(EvaIcons.flash),
  Icon(EvaIcons.clipboard_outline),
```

## 7. Flag
Here's an example showing how to use Flags.

![Flags](https://github.com/chouhan-rahul/icons_plus/assets/82075108/4cb2060c-6a4e-415f-be64-95504cfbf7f9)

```dart
  Flag(Flags.india),
  Flag(Flags.united_kingdom),
  Flag(Flags.united_states_of_america),
```

## 8. FontAwesome
FontAwesome provides three types of icons: Regular, Solid, and Brand icons. To use Solid icons, simply append `_solid` as a suffix. For example, for a solid, you can use `Icon(FontAwesome.bug_solid)`, while `Icon(FontAwesome.folder_open)` and `Icon(FontAwesome.stripe_brand)` are used for Regular and Brand, respectively.

![FontAwesome](https://github.com/chouhan-rahul/icons_plus/assets/82075108/604352ab-b725-49ca-acf4-bd4c5e092cd9)

```dart
  Icon(FontAwesome.stripe_brand),
  Icon(FontAwesome.folder_open),
  Icon(FontAwesome.bug_solid),
```

## 9. HeroIcons
Here's an example showing how to use HeroIcons.

![HeroIcons](https://github.com/chouhan-rahul/icons_plus/assets/82075108/15ec217a-9567-4b2d-8057-13a76bdac507)

```dart
  Icon(HeroIcons.printer),
  Icon(HeroIcons.pencil_square),
  Icon(HeroIcons.play_circle),
```

## 10. Iconsax
Iconsax provides three types of icons: Bold, Bulk, and Outline icons. To use Bold icons, simply append `_bold` as a suffix. For example, for a bold, you can use `Icon(Iconsax.cake_bold)`, while `Icon(Iconsax.clock_bulk)` and `Icon(Iconsax.dollar_circle_outline)` are used for Bulk and Outline, respectively.

![Iconsax](https://github.com/chouhan-rahul/icons_plus/assets/82075108/1318d2cf-0323-4e4f-9a45-a282b8542e40)

```dart
  Icon(Iconsax.cake_bold),
  Icon(Iconsax.clock_bulk),
  Icon(Iconsax.dollar_circle_outline),
```

## 11. IonIcons
Here's an example showing how to use IonIcons.

![IonIcons](https://github.com/chouhan-rahul/icons_plus/assets/82075108/d117fe37-24a9-4b8a-9a15-57bd55cb9b5d)

```dart
  Icon(IonIcons.bug),
  Icon(IonIcons.finger_print),
  Icon(IonIcons.logo_react),
```

## 12. LineAwesome
Here's an example showing how to use LineAwesome icons.

![LineAwesome](https://github.com/chouhan-rahul/icons_plus/assets/82075108/617c19c6-dd2b-4ff3-928b-2918d0e62319)

```dart
  Icon(LineAwesome.amazon),
  Icon(LineAwesome.birthday_cake_solid),
  Icon(LineAwesome.cc_visa),
```

## 13. MingCute
Here's an example showing how to use MingCute icons.

![MingCute](https://github.com/chouhan-rahul/icons_plus/assets/82075108/39edffb1-1020-4d7c-9d48-23e19d50fa5d)

```dart
  Icon(MingCute.knife_line),
  Icon(MingCute.badminton_line),
  Icon(MingCute.currency_bitcoin_fill),
```

## 14. OctIcons
Here's an example showing how to use OctIcons.

![OctIcons](https://github.com/chouhan-rahul/icons_plus/assets/82075108/fb6a8253-c837-4d9d-8831-50c9cf6bf712)

```dart
  Icon(OctIcons.code_of_conduct),
  Icon(OctIcons.copilot),
  Icon(OctIcons.verified),
```

## 15. PixelArtIcons
Here's an example showing how to use PixelArtIcons.

![PixelArtIcons](https://github.com/chouhan-rahul/icons_plus/assets/82075108/37c0d860-26ac-4eaf-a030-22873bf92f30)

```dart
  Icon(PixelArtIcons.gif),
  Icon(PixelArtIcons.human),
  Icon(PixelArtIcons.heart),
```

## 16. TeenyIcons
Here's an example showing how to use TeenyIcons.

![TeenyIcons](https://github.com/chouhan-rahul/icons_plus/assets/82075108/d60b3997-0434-49b1-ac72-ef87b4f53ff8)

```dart
  Icon(TeenyIcons.google_play_store),
  Icon(TeenyIcons.heart),
  Icon(TeenyIcons.android),
```

## 17. ZondIcons
Here's an example showing how to use ZondIcons.

![ZondIcons](https://github.com/chouhan-rahul/icons_plus/assets/82075108/f0c0ac16-7a08-47dd-93dc-ef3380c0273f)

```dart
  Icon(ZondIcons.shield),
  Icon(ZondIcons.trophy),
  Icon(ZondIcons.coffee),
```


<h2>Libery of Amicons</h2>
<br />
<code><img height="50" src="https://raw.githubusercontent.com/AyushMaji/amicons/refs/heads/main/assets/others/flaticon.png"></code>
<code><img height="50" src="https://raw.githubusercontent.com/AyushMaji/amicons/refs/heads/main/assets/others/iconly.jpg"></code>
<code><img height="50" src="https://raw.githubusercontent.com/AyushMaji/amicons/refs/heads/main/assets/others/lucide.png"></code>
<code><img height="50" src="https://raw.githubusercontent.com/AyushMaji/amicons/refs/heads/main/assets/others/remix.png"></code>
<code><img height="50" src="https://raw.githubusercontent.com/AyushMaji/amicons/refs/heads/main/assets/others/vuesax.png"></code>
<code><img height="50" src="https://raw.githubusercontent.com/AyushMaji/amicons/refs/heads/main/assets/others/figma.png"></code>
<br /><br />
<br />
<img src="https://github.com/AyushMaji/amicons/blob/main/assets/others/theme_banner.png?raw=true" />
<br /><br />

> Copyright © **[Ayush Maji](https://github.com/AyushMaji)**. Licensed under the _[MIT LICENSE](https://github.com/chouhan-rahul/icons_plus/blob/main/LICENSE)_
> 





