# Issue of XAML F7

F7 / Shift+F7 is not working for switching between designer and code

## Issue Description

### `F7` / `Shift + F7` is lost

We use `F7` to switch from the XAML designer to the attached .xaml.cs code and use Shift + F7 to switch back to the XAML designer.

But since Visual Studio 2019 (16.0.0) the F7 was lost but the Shift + F7 still worked. A few months later, since 16.6.0, the Shift + F7 also lost. So I can’t switch from and to the XAML designer through the keyboard anymore.

### The mouse not works

What makes things worse is that there comes another bug since 16.4, the mouse stops working in the XAML designer (and other tool windows). See the issues here:

The mouse cannot hit anything inside Visual Studio (but the keyboard can do) - Developer Community
Mouse stops working in VS with Win10 builds 19575 and up - Developer Community
So I can’t use a mouse to operate the XAML designer because of the above issues. Furthermore, I can’t use a keyboard to fully operate the XAML designer due to this new issue as the keyboard shortcuts lost.

I HAVE NO WAYS TO DEVELOP ANY XAML PROGRAMS CONVENIENTLY!

### I hope this issue can be fixed

Any reply is appreciated.

## Tested Visual Studio Versions

All of these versions can reproduce this issue:

- [x] Visual Studio 2019 16.6.0
- [x] Visual Studio 2019 16.6.1
- [x] Visual Studio 2019 16.6.2
- [x] Visual Studio 2019 16.7.0 Preview 1
- [x] Visual Studio 2019 16.7.0 Preview 2

The folders naming as VS versions are projects that are created using the specified version of Visual Studio.
