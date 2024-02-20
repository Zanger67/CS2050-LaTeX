# Fontsizes -- Larger and Smaller


Sometimes you might find a need to shrink items to make sure they fit in the page. This has especially applied to making `tables` because rows are too long.

For the official Overleaf documentation, click [here](https://www.overleaf.com/learn/latex/Font_sizes%2C_families%2C_and_styles).

```latex
\begin{INSERT}
    ...
\end{INSERT}
```

Replace ***INSERT*** with one of the following:
- `tiny`
- `scriptsize`
- `footnotesize`
- `small`
- `normalsize`
- `large`
- `Large`
- `LARGE`
- `huge`
- `HUGE`

> ❗️ We recommend only using `footnotesize` or larger. 
> Readability can be difficult at smaller levels, especially with equations and tables. 
> 
> Unless needed or for emphasis, you should stick to the default size however.


#### Example
```latex
This text WON'T be affected

\begin{footnotesize}
    This text WILL be affected
    $This equation WILL be affected$
    This text WILL be affected
\end{footnotesize}

This text WON'T be affected
```

## Directly using `\something`
Alteratively, you can also use the command itself directly. 

```latex
\tiny
\scriptsize
\footnotesize
\small
\normalsize
\large
\Large
\LARGE
\huge
\HUGE
```

Note that this will propogate and continue until it hits the end of a `{}` bracket pair. When you use these, you should surround the area you want affected with `{}` brackets.

#### Example
```latex
this text WON'T be affect

{\tiny this text WILL be affected} this text WON'T be affect

this text WON'T be affect
```



## Related Stuff
This is similar to how you would change font colour or font style. See [here](font%20colour.md) for font colour notes.