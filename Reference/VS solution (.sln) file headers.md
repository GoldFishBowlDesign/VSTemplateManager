# Visual Studio Solution File Headers
## VS versions 2002-2017
### Header text generated by Microsoft Visual Studio for `.sln` files

Below is the header text found at the top of each `.sln` file produced by each version of Microsoft Visual Studio from 2002 through 2017.

By default, each of these headers is preceeded by a new line character (`CRLF`) in the `.sln` file, although my testing indicates that this blank line _may_ be omitted without making the solution unreadable.

---

### VS2002
```

Microsoft Visual Studio Solution File, Format Version 7.0
```

### VS2003
```

Microsoft Visual Studio Solution File, Format Version 8.0
```

### VS2005
```

Microsoft Visual Studio Solution File, Format Version 9.0
```

### VS2005 (Beta 1)
```

Microsoft Visual Studio Solution File, Format Version 9.0
# Visual Studio 2005
```

### VS2008
```

Microsoft Visual Studio Solution File, Format Version 10.00
# Visual Studio 2008
```

### VS2010
```

Microsoft Visual Studio Solution File, Format Version 11.00
# Visual Studio 2010
```

### VS2012
```

Microsoft Visual Studio Solution File, Format Version 12.00
# Visual Studio 2012
```

### VS2013*
<pre>

Microsoft Visual Studio Solution File, Format Version 12.00
# Visual Studio 2013
<i><b>VisualStudioVersion = 12.0.31101.0</b></i>
<i><b>MinimumVisualStudioVersion = 10.0.40219.1</b></i>
</pre>

### VS2015*
<pre>

Microsoft Visual Studio Solution File, Format Version 12.00
# Visual Studio 14
<i><b>VisualStudioVersion = 14.0.25420.1</b></i>
<i><b>MinimumVisualStudioVersion = 10.0.40219.1</b></i>
</pre>

### VS2017*
<pre>

Microsoft Visual Studio Solution File, Format Version 12.00
# Visual Studio 15
<i><b>VisualStudioVersion = 15.0.27130.2027</b></i>
<i><b>MinimumVisualStudioVersion = 10.0.40219.1</b></i>
</pre>

*-_The **`VisualStudioVersion`** and **`MinimumVisualStudioVersion`** lines in the headers for VS2013, VS2015 and VS2017 appear to be optional. I can't say if they will remain so in future VS releases, but `.sln` files without these lines for these VS versions seem to work normally in my own testing._

Additional Sources:
* [JamesSkemp/Visual Studio solution file headers](https://gist.github.com/JamesSkemp/bbe17351ecdf6b1d6e07) (_gist_)
* [Hack the Project and Solution Files](http://www.onjava.com/pub/a/dotnet/excerpt/vshacks_chap1/index.html?page=4) (_O'Reilly Media_)