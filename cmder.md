# CMDER

[~~In Progress~]

<!-- After a some time using the original windows CMD with sometimes PowerShell. I decided to check other command lines. -->

- [CMDER](#cmder)
  - [Introduction](#introduction)
  - [Themes](#themes)
  - [Git](#git)

## Introduction

After listening to the episode "**[The Command Line for Web Developers]**" from the great podcast: "_[Syntax FM]_", I decided to give a try to [CMDER].

![cmder-image-site](http://cmder.net/img/main.jpg)

CMDER is as the site say:
> Portable console emulator for Windows

From what I understand it run above exists command lines such as the regular **CMD** and **PowerShell**.

The CMDER have all of these project in it:

- [Conemu] - Console emulator.
- [Clink] - Cmd.exe enhancements.
- [Git for windows] - Unix tools on windows.

## Themes

First thing first, themes!!
So the first thing I did is to add and change to the [Dracula Theme](https://draculatheme.com/conemu/).


Here how to do that:
<!-- TODO: Add links for dracula sites and github, and see if there were another way to use it -->

- Under the `<key>` with the attribute `name="Colors"`, add this code:

    ```xml
    <key name="Palette1" modified="2017-10-10 22:34:43" build="161206">
      <value name="Name" type="string" data="Dracula"/>
      <value name="ExtendColors" type="hex" data="00"/>
      <value name="ExtendColorIdx" type="hex" data="0e"/>
      <value name="TextColorIdx" type="hex" data="10"/>
      <value name="BackColorIdx" type="hex" data="10"/>
      <value name="PopTextColorIdx" type="hex" data="10"/>
      <value name="PopBackColorIdx" type="hex" data="10"/>
      <value name="ColorTable00" type="dword" data="00362a28"/>
      <value name="ColorTable01" type="dword" data="00bc4354"/>
      <value name="ColorTable02" type="dword" data="003dde66"/>
      <value name="ColorTable03" type="dword" data="00fbd677"/>
      <value name="ColorTable04" type="dword" data="003c3cee"/>
      <value name="ColorTable05" type="dword" data="00f993bd"/>
      <value name="ColorTable06" type="dword" data="006cb8ff"/>
      <value name="ColorTable07" type="dword" data="00f2f8f8"/>
      <value name="ColorTable08" type="dword" data="005a4744"/>
      <value name="ColorTable09" type="dword" data="00a47262"/>
      <value name="ColorTable10" type="dword" data="007bfa50"/>
      <value name="ColorTable11" type="dword" data="00fde98b"/>
      <value name="ColorTable12" type="dword" data="005555ff"/>
      <value name="ColorTable13" type="dword" data="00c679ff"/>
      <value name="ColorTable14" type="dword" data="008cfaf1"/>
      <value name="ColorTable15" type="dword" data="00f2f8f8"/>
      <value name="ColorTable16" type="dword" data="00000000"/>
      <value name="ColorTable17" type="dword" data="00800000"/>
      <value name="ColorTable18" type="dword" data="00008000"/>
      <value name="ColorTable19" type="dword" data="00808000"/>
      <value name="ColorTable20" type="dword" data="00000080"/>
      <value name="ColorTable21" type="dword" data="00800080"/>
      <value name="ColorTable22" type="dword" data="00008080"/>
      <value name="ColorTable23" type="dword" data="00c0c0c0"/>
      <value name="ColorTable24" type="dword" data="00808080"/>
      <value name="ColorTable25" type="dword" data="00ff0000"/>
      <value name="ColorTable26" type="dword" data="0000ff00"/>
      <value name="ColorTable27" type="dword" data="00ffff00"/>
      <value name="ColorTable28" type="dword" data="000000ff"/>
      <value name="ColorTable29" type="dword" data="00ff00ff"/>
      <value name="ColorTable30" type="dword" data="0000ffff"/>
      <value name="ColorTable31" type="dword" data="00ffffff"/>
    </key>
    ```
    And in `<value>` with the attribute `name="Count"` change the attribute `<data>` to `2`:
    ```xml
    <value name="Count" type="long" data="2"/>
    ```

## Git

In the regular **CMD** it show which branch you are, while in **PowerShell** you will need first install **posh-git**.

-------------------

Unfortunately I need more time to test and check it out and I will update this page, however, it looks very promising.

<!--reference links-->
[CMDER]: http://cmder.net/
[Syntax FM]: https://syntax.fm/
[The Command Line for Web Developers]: https://syntax.fm/show/013/the-command-line-for-web-developers
[Conemu]: https://conemu.github.io/
[Clink]: https://mridgers.github.io/clink/
[Git for windows]: https://git-for-windows.github.io/