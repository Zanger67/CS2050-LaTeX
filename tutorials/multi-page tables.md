# Multi-Page Tables -- Using `Longtable`
${{\color{gray}\textnormal{Click here for a regular table\:}}}$ _[link](tables.md)_

If you want a table to spill onto a new line vertically while maintaining the previous appearance (e.g. column widths, center, etc.), you can use the package `longtable`.


At the top with the rest of the packages, make sure to have longtable imported.
```latex
\usepackage{longtable}
```

Besides that, the useage is extremly similar to `tabular`

<!-- <table border="0">
 <tr>
    <td><b style="font-size:25px">Tabular</b></td>
    <td><b style="font-size:25px">Longtable</b></td>
 </tr>

 <tr>
    <td>
    something
    </td>
    <td>
    something2
    </td>
 </tr>
</table> -->




```latex
% {rc|c} means right-alight, centre, separating line, centre for the columns
% I usually have the rc|c so I have a column for the number lines 1, 2, 3...
\begin{longtable}[c]{rc|c}
    # & \textbf{Statement} & \textbf{Reason} \\
    \hline
    
    1. & left column & right column \\
    % insert more rows...
    
    % "&" tells LaTeX to go to the next column 
    % "\\" tells it to the next line
\end{longtable}
```







## Example

```latex
this

```
would yield this:
*insert image
