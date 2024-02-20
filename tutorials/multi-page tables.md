# Multi-Page Tables -- Using `Longtable`
<!-- ${{\color{gray}\textnormal{Click here for a regular table\:}}}$ _[link](tables.md)_ -->

_[Click here for regular tables (`tabular`)](tables.md)_


## Implementation

If you want a table to spill onto a new line vertically while maintaining the previous appearance (e.g. column widths, center, etc.), you can use the package `longtable`.


At the top with the rest of the packages, make sure to have longtable imported.
```latex
\usepackage{longtable}
```

Besides that, the useage is extremly similar to `tabular`.

```latex
\begin{longtable}[c]{rc|c}
    \# & \textbf{Statement} & \textbf{Reason} \\
    \hline
    
    1. & insert statement & insert reason \\
    2. & ... & ... \\
    .  & ... & ... \\
    .  & ... & ... \\
    .  & ... & ... \\
\end{longtable}
```

`{rc|c}` means right-alight, centre, separating line, centre for the columns, just like with `tabular`.

I usually have the `rc|c` structure so I have a column for the numbering lines 1, 2, 3...


**INSERT IMAGE OF THIS BEING PROCESSED**




## `Tabular` vs `Longtable`
_[Click here for `tabular`](tables.md)_

Here are the two side by side to see the differences. As you can see, it's not that much. The implementations besides the initial `\usepackage{}` and `\begin{}` header are identical. 
<table>
   <tr>
      <th>Tabular</th>
      <th>Longtable</th>
   </tr>

   
   <tr>
   <td>

   ```latex
   % no package to import

   % ...

   \begin{tabular}{rc|c}
      \# & \textbf{Statement} & \textbf{Reason} \\
      \hline

      1.  & statement & reason \\
      2.  & ... &  \\
      .   & ... &  \\
      .   & ... &  \\
      .   & ... &  \\
   \end{tabular}
   ```
   </td>

   <td>

   ```latex
   \usepackage{longtable}
   
   % ...

   \begin{longtable}[c]{rc|c}
      \# & \textbf{Statement} & \textbf{Reason} \\
      \hline
      
      1. & statement & reason \\
      2. & ... & ... \\
      .  & ... & ... \\
      .  & ... & ... \\
      .  & ... & ... \\
   \end{longtable}
   ```

   </td>
   </tr>
</table>










<!-- ## Example

```latex
this

```
would yield this:
*insert image -->
