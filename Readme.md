WPF-Math [![Build status][badge-appveyor]][appveyor] [![NuGet][badge-nuget]][nuget]
========

WPF-Math is a library to render LaTeX formulae in a WPF environment.

Getting started
---------------

The simplest way of using WPF-Math is to render a static formula in a XAML file
like that:

```xml
<Window ... xmlns:controls="clr-namespace:WpfMath.Controls;assembly=WpfMath">
    <controls:FormulaControl Formula="\left(x^2 + 2 \cdot x + 2\right) = 0" />
</Window>
```

For a more detailed sample, check out the [example project][example]. It shows
the usage of data binding and some advanced concepts:

![Example screenshot](docs/example-screenshot.png)

History
-------

The library was originally ported from the [JMathTex project][jmathtex],
copyright 2004-2007 Universiteit Gent. The port was originally called WPF-TeX
and lead by [Alex Regueiro][alex-regueiro].

Later it was accessible as [WPF-Math on Launchpad][launchpad], but has no
commits from 2010, until it was ported to [its current location on
GitHub][github].

[example]: WpfMath.Example/

[alex-regueiro]: mailto:alexreg@gmail.com
[appveyor]: https://ci.appveyor.com/project/ForNeVeR/wpf-math/branch/master
[github]: https://github.com/ForNeVeR/wpf-math
[jmathtex]: http://jmathtex.sourceforge.net/
[launchpad]: https://launchpad.net/wpf-math
[nuget]: https://www.nuget.org/packages/WpfMath/

[badge-appveyor]: https://ci.appveyor.com/api/projects/status/b26m3rpfcgb91gdg/branch/master?svg=true
[badge-nuget]: https://img.shields.io/nuget/v/WpfMath.svg
